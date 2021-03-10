## form
HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.
#### ADDING TEXT:
* Text input (single-line) used for a single line of text such as email addresses and names.
* Password input like a single line text box but it masks the characters entered.
* Text area (multi-line) for longer areas of text, such as messages and comments.
#### Making Choices:
* Radio buttons for use when a user must select one of a number of options.
* Checkboxes when a user can select and unselect one or more options.
* Drop-down boxes when a user must pick one of a number of options from a list
#### Submitting Forms:
* Submit buttons to submit data from your form to another web page.
* Image buttons similar to submit buttons but they allow you to use an image.
#### Uploading Files:
* File upload allows users to upload files (e.g. images) to a website.
### How Forms Work
A user fills in a form and then presses a button to submit the information to the server.
HTML5
is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and last[3] major HTML version that is a World Wide Web Consortium (W3C) recommendation.
* HTML5 : Form Validation
*web that give users messages if the form control has not been filled in correctly; this is known as form validation.*
* HTML 5 : Date Input
*we use for it (input) with attribut (type=”date”).*
* HTML 5 : Email & URL Input
*email we use for it (input) with attribut (type=”email”).*
*URL we use for it (input) with attribut (type=”url”).*
* HTML 5 : Search Input
*we use for it (input) with attribut (type=”search”).*
## Lists, Tables and Forms
There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms
#### list-style-type : The list-style-type property allows you to control the shape or style
 of a bullet point .
* Unordered Lists
* Ordered Lists 
#### Images for Bullets
You can  specify an image to act as a bullet point using the list-style-image property.
#### Positioning the Marker
Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on  the inside or the outside of the box containing the main points.
#### List shorthand
As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called list-style, and it allows you to express the markers’ style, image and position properties in any order.
Tables properties
You  have already met several properties that are commonly used with tables. Here we will put them together in a single example using the following:
* width.
* padding.
* text-trasform.
* letter-spacing, fornt size.
* border-top, border-bottom.
* text-align.
* background-color.
* :hover.

Styling Text input :
 
*font-size* sets the size of the text entered by the user. color sets the text color, and background-color sets the background color of the input.
*border* adds a border around the edge of the input box, and border-radius can be used to create rounded corners (for browsers that support this property).
*The:focus* pseudo-class is used to change the background color of the text input when it is being used, and the :hover psuedo-class applies the same styles when the user hovers over them.
*background-image* adds a background image to the box. Because there is a different image for each input, we are using an attribute selector looking for the value of the id attribute on each input.
## Event:
When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.
### how forms works :
when user inter data to the form this data will be stored in there variables or names then this value is formed and send to the server or can be stored in data-base then the server prepare aweb page that include that data and ready to be send to the end user.
* select element: The element that users are interacting with is the text input where they enter the username.
* spacify event :When users move out of the text input, it loses focus, and the blur event fires on this element.
* call code 


