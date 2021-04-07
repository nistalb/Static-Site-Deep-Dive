# Static-Site-Optimization
This is a very simple and lightly styled static website that has been built using flexbox and validated for best practices using W3C Markup Validation and performance tested using Google PageSpeed Insights.  The goal of this project is to practice flexbox in making a responsive website and to learn about W3C Markup Validation and Google PageSpeed Insights.

Responsively will be used to improve the responsiveness of the site after initial creation and optimization using W3C markup validation and Google PageSpeed Insights.

# W3C Validation
https://validator.w3.org/

On the first pass through the validator this message was returned:
"Article lacks heading. Consider using h2-h6 elements to add identifying headings to all articles."

I was using an article tag for each image containing card; each article should be identified with a heading as a child of the article element.  I changed the article tag to a div tag to avoid this message.

On the second pass through the validator this message was returned:
"Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections."

Sections, like articles should have a heading that identifies the section.  The section tag was changed to a div.

On the third pass through the validator no error messages were returned.

No errors were found when using the CSS validator.

# Google PageSpeed Insights
https://developers.google.com/speed/pagespeed/insights/

Run # |First Contentful Paint | Speed Index | Largest Contentful Paint | Time to Interactive
--- | :---: | :---: | :---: | :---:
1 | 0.8 s | 0.8 s | 0.8 s | 0.9 s
2 | 0.2 s | 0.2 s | 0.8 s | 0.3 s
% improvement | 75% | 75% | 0 | 66%

The opportunities identified after the first run were to properly size images, serve images in next-gen formats, and efficiently encode images.  Prior to run 2 all images were sized using a photo editing software for the width of the image element;  the images were sized with a width of 200px.


# Responsively
https://responsively.app/

Resposively was very useful in seeing how a website would appear in 7 commonly used screen sizes (desktop and mobile).  After visualization of the webpage using Responsively, @media was used to optimize the presentation for readability.