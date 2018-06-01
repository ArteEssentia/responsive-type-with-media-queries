# responsive-type-with-media-queries
Demonstrates how to make typography responsive for optimal viewing and user experience.

When thinking about responsive design the generic layout gets quite a lot of attention. But, as the visitor will be looking for information on most pages, typography deserves some attention as well.

### The HTML
The page has a main wrapper that sets the overall width. Keep in mind that on the web we aim for anything between 45-75 characters per line.

Inside the wrapper are just some basic html-element with placeholder text and a single image.

### The CSS
The body element is where we set the base size of the font.

All other elements now get relative sizes compared to the base size.

Remember, there are two ways to do this: using ems or using rems.
- ems are relative units from the base size of the element they are used on.
- rems are relative units from the base size of the html element.

Using rems we are able to keep layouts consistent throughout the design based on one single base typographic size. It is very important to understand that the html element gets its initial size from the user browser settings. This way, when the user chooses to enlarge or shrink the browser font size, our whole design stays intact.

Using ems allows us to keep the layout of a particular design element consistent over various screen sizes.

Important note: in this example I set the base font-size in the html-element. In real life I would not do that. I like to give the user control over the generic font-size and so I leave that alone. If I want to change the overall size of the typography, I would use a rem or em value in the html-element, so the change would still reflect the user's choice.

With media queries we then control the different breakpoints to ensure that our presentation always looks good and the typography always remains good to read.

## [Take a look at the live working version of this demo](https://VincentKlijn.github.io/responsive-type-with-media-queries/)

