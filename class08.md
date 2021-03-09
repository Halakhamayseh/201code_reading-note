# HTML/CSS book, Ch. 15, “Layout” 
### What does layout ?
layouts provide a way to arrange web pages in well-mannered , well-structured , and in responsive form or we can say that HTML layout specifies a way in which the web pages can be arranged . Web-page layout works with arrangement of visual elements of an HTML document. 
### Layout position and the containing block
* The size and position of an element are often impacted by its containing block. Most often, the containing block is the content area of an element's nearest block-level ancestor.
* CSS treats each HTML element as if it is in itsown box. This box will either be a block-level box or an inline box.
* If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
### CSS has the following positioning schemes that allow you to control the layout of a page: 
* normal flow:Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one
* relative positioning:This moves an element from the position it would be in normal flow, shifting it to differnt dircations.
* absolute positioning:is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).
* fixed position: is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
*Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.*
### floating element :
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
floating property can have one of the following values:
* left - The element floats to the left of its container.
* right - The element floats to the right of its container.
* none - The element does not float (will be displayed just where it occurs in the text). This is default.
* inherit - The element inherits the float value of its parent.
### Screen Sizes:
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
### Screen Resolution:
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
### Page Sizes:
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).
### CSS Height and Width:
The CSS height and width properties are used to set the height and width of an element.
### Liquid Layouts:
Liquid Layouts designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.
### Layout Grids:
The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
### CSS Frameworks:
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.
 
 ### References:
* HTML & CSS Design link
* https://www.w3schools.com/css/css_positioning.asp
* https://developer.mozilla.org/en-US/docs/Web/CSS/Containing_block
