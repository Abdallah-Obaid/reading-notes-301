# Read 01 ~ SMACSS and Responsive Web Design
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-obaid.github.io/reading-notes/).
 Read 01     | [SMACSS and Responsive Web Design](https://abdallah-obaid.github.io/reading-notes/class-01).
 Read 02     | [jQuery, Events, and The DOM](https://abdallah-obaid.github.io/reading-notes/class-02).
 Read 03     | [Flexbox and Templating](https://abdallah-obaid.github.io/reading-notes/class-03).
 Read 04     | [Responsive Web Design and Regular Expressions](https://abdallah-obaid.github.io/reading-notes/class-04).
 Read 05     | [Responsive Web Design and Regular Expressions](https://abdallah-obaid.github.io/reading-notes/class-05).
 Read 06     | [Node, Express, and APIs](https://abdallah-obaid.github.io/reading-notes/class-06).
 Read 07     | [APIs continued](https://abdallah-obaid.github.io/reading-notes/class-07).
 Read 08     | [SQL](https://abdallah-obaid.github.io/reading-notes/class-08).
 Read 09     | [Refactoring](https://abdallah-obaid.github.io/reading-notes/class-09).
 Read 10     | [The Call Stack and Debugging](https://abdallah-obaid.github.io/reading-notes/class-10).
 Read 11     | [EJS](https://abdallah-obaid.github.io/reading-notes/class-11).
 Read 12     | [Components](https://abdallah-obaid.github.io/reading-notes/class-12).
 Read 13     | [Update/Delete](https://abdallah-obaid.github.io/reading-notes/class-13).
 Read 14a    | [DB Normalization](https://abdallah-obaid.github.io/reading-notes/class-14a).
 Read 14b    | [Project Ideas & APIs](https://abdallah-obaid.github.io/reading-notes/class-14b).
 Read 15     | [Diversity and Inclusion](https://abdallah-obaid.github.io/reading-notes/class-15).
----------------------------------
# Responsive Web Design :-
----------------------------------
  > How to build websites suitable for all users.
 * RWD: Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
 * Responsive: generally means to react quickly and positively to any change.
 * Adaptive: means to be easily modified for a new purpose or situation.
 * The combination of the Responsive and Adaptive is ideal. 
 * Responsive web design is broken down into three main components, including flexible layouts, media queries, and flexible media.
 * Relative Viewport Lengths:  
   vw: Viewports width 
   vh: Viewports height 
   vmin: Minimum of the viewport’s height and width
   vmax: Maximum of the viewport’s height and width
 * formula to help identify the proportions of a flexible layout: target ÷ context = result
 * We can use em unit or % for a flexible page.
 * The flexible layout approach alone isn’t enough. At times the width of a browser viewport may be so small that even scaling the the layout proportionally will create columns that are too small to effectively display content. Specifically, when the layout gets too small, or too large, text may become illegible and the layout may begin to break. In this event, media queries can be used to help build a better experience.
 * Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example.
 * Initializing Media Queries: using the @media rule inside of an existing style sheet,or importing a new style sheet using the @import rule, or by linking to a separate style sheet from within the HTML document. Generally speaking it is recommend to use the @media rule inside of an existing style sheet to avoid any additional HTTP requests.
 * Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including and, not, and only.
 * Using the and logical operator within a media query allows an extra condition to be added.
 * The not logical operator negates the query, specifying any query but the one identified.
 * The only logical operator selects only screens in a portrait orientation that have a user agent capable of rending media queries.
 * Omitting a Media Type: When using the not and only logical operators the media type may be left off. In this case the media type is defaulted to all.
 * The orientation media feature determines if a device is in the landscape or portrait orientation. The landscape mode is triggered when the display is wider than taller, and the portrait mode is triggered when the display is taller than wider. This media feature plays a large part with mobile devices.
 * The aspect-ratio and device-aspect-ratio features specifies the width/height pixel ratio of the targeted rendering area or output device. The min and max prefixes are available to use with the different aspect ratio features, identifying a ratio above or below that of which is stated.
 * The resolution media feature specifies the resolution of the output device in pixel density, also known as dots per inch or DPI. The resolution media feature does accept the min and max prefixes. Additionally, the resolution media feature will accept dots per pixel (1.3dppx), dots per centimeter (118dpcm), and other length based resolution values.
 * Common viewport sizes as determined by different device resolutions, such as 320px, 480px, 768px, 1024px is a bad idea.
 * The mobile first approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.
 * Avoiding CSS3 shadows, gradients, transforms, and animations within mobile styles isn’t a bad idea either.

![Responsive](img/Responsive-Website-Designing.gif)
Format: ![Alt Text](url)

----------------------------------
# All About Floats:-
----------------------------------
* Float is a CSS positioning property. 
* Absolutely positioned page elements are removed from the flow of the webpage.
* Absolutely positioned page elements will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.
* The float:Inherit will assume the float value from that elements parent element.
* Floats can be used to create entire web layouts.
* While floats can still be used for layout, these days, we have much stronger tools for creating layout on web pages. Namely, Flexbox and Grid. Floats are still useful to know about because they have some abilities entirely unique to them, which is all covered in this article.
* Float's sister property is clear. An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. Again an illustration probably does more good than words do.
* If the parent element contained nothing but floated elements, the height of it would literally collapse to nothing.
* We fix collapse by clearing the float after the floated elements in the container but before the close of the container.


![Float](../img/float-problem.gif)
Format: ![Alt Text](url)