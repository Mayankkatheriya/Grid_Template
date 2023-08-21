# Grid_Template
## Hosted Link: https://mayankkatheriya.github.io/Grid_Template/
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/2db0f11f-9654-4c22-b278-1875413716d7)
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/1feebacc-2a02-48db-bc62-27dc764148d2)

HTML:\
Sure, this is an HTML document with metadata and linked resources such as stylesheets and fonts. The title of the webpage is "FEM Grid." It's using an external stylesheet named "styles.css" for styling. There's also a Google Fonts link to load the "Barlow Semi Condensed" font in a specific weight (500) for usage on the webpage.

CSS:

* Selector:

Targets all elements on the page.\
Sets margin and padding to 0 for all sides.\
Uses the border-box box-sizing to include padding and borders in the element's total width.

:root Selector:

Targets the root element (usually <html>).\
Defines CSS custom properties (variables) for colors: "--color1" and "--color2".

body Selector:

Targets the "body" element.\
Sets background color to a light blue.\
Uses the 'Barlow Semi Condensed' font from the sans-serif font family.\
Ensures a minimum height of 100% viewport height.\
Adds padding of 2rem to the body.\
Uses flex display to center content both horizontally and vertically.

h1, h3 Selectors:

Targets all "h1" and "h3" elements.\
Sets font size, line height, and margins.\
Font color is determined by the "--color1" variable.\
Font weight is set to 500 (semi-bold).

h2, h4 Selectors:

Targets all "h2" and "h4" elements.\
Sets font size, line height, and margins.\
Font color is determined by the "--color2" variable.\
Font weight is set to 500 (semi-bold).\
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/2b1d9d22-fdae-4c91-8711-534a404d653f)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/f7bbef68-0cef-4205-94d6-ca25b665721a)
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/e66bcf83-5c9d-4bb8-9507-887374215c2a)
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/a7a50da3-b074-4ebc-a573-9240eb59afc3)
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/4eff493e-7b9d-4bc0-9908-46620f658387)

HTML:\
The HTML structure represents a testimonial section on a webpage. It contains five testimonial items, each having an image, title, name, heading, and a paragraph of text. The structure is organized within a "container" division. Each testimonial is an "item" division with a unique ID ("one," "two," etc.). Inside each "item," there's a title section with an image and a name. Following that is an "h1" element for the main heading and an "h2" element for the paragraph of text. Images are referenced using "img" elements with "src" attributes pointing to image files. The images are contained within a "image" division. The structure creates a grid-like layout of testimonial items.

CSS:

.container Class:

Targets elements with the class "container".\
Uses grid display.\
Sets gap between grid items.\
Sets columns to take equal fractions of available space.\
Defines grid areas using grid-template-areas.\
Adds padding to the block axis.\
Sets width to a minimum of 95% or 70rem, centered using margin-inline.

.item Class:

Targets elements with the class "item".\
Adds padding.\
Sets border radius for rounded corners.\
Applies a box shadow for a subtle elevation effect.

.item img Selector:

Targets "img" elements within elements with the class "item".\
Sets width for circular images.\
Applies border radius for a circular appearance.

.item .title Selector:

Targets elements with the class "title" within elements with the class "item".\
Uses flex display to align items and distribute space.\
Adds margin at the bottom.

#one, #two, #three, #four, #five IDs:

Targets elements with specific IDs.\
Sets grid areas for different sections.\
Adjusts background colors and images.\
Defines grid-column placement for specific sections.

#three h3, #three h1, #five h3, #five h1 Selectors:

Targets specific heading elements within elements with the IDs mentioned.\
Sets text color to black.

#three h4, #five h4 Selectors:

Targets specific h4 elements within elements with the IDs mentioned.\
Sets text color to a semi-transparent gray.

#three h2, #five h2 Selectors:

Targets specific h2 elements within elements with the IDs mentioned.\
Sets text color to a more transparent gray.\
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/7319cac5-b71a-4895-a494-d86c5aeac5bc)
\
\
\
![image](https://github.com/Mayankkatheriya/Grid_Template/assets/128832286/47e5faef-cf5a-4bde-9b65-239e62500ffd)

@media only screen and (max-width: 527px):

Targets screens with a maximum width of 527px.\
Adjusts the grid-template-areas of .container to stack the sections vertically.

@media only screen and (min-width: 528px) and (max-width: 607px):

Targets screens with a minimum width of 528px and maximum width of 607px.\
Adjusts the grid-template-areas of .container to arrange sections in a 2x2 grid.

@media only screen and (min-width: 608px) and (max-width: 863px):

Targets screens with a minimum width of 608px and maximum width of 863px.\
Adjusts the grid-template-areas of .container to rearrange sections in a different grid pattern.

@media only screen and (min-width: 864px) and (max-width: 1199px):

Targets screens with a minimum width of 864px and maximum width of 1199px.\
Adjusts the grid-template-areas of .container to rearrange sections in another grid pattern.\
## Now web page is ready
# ThankYou
