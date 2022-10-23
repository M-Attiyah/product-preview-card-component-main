THE MAIN PURPOSE OF THIS PROJECT ?
: IS SHOW THE PARFUM PRODUCT THAT CAN USER SEE THE NAME, DETAILES, PRICE, ADD TO CART BUTTON

<:> TOPICS I WANT TO REVIEW/LEARN TO BUILD THIS PROJECT
<::> HTML
- HOW TO CREATE CONTAINER
-> Div: is a container used to group the content, this element does not give any meaning, it just uses for styling 
`<div class="" id="">card</div>`

- HOW TO ADD AN IMAGE
-> img: is an element to insert element to your webpage, and this element is a void element(meaning element with only opening tag, this type of elements, we used to insert/embed content to webpage).
The img element have two main attributes:
- src: define the path of the image
- alt: stands for (alternative) this attribute define alternative text, when an image failed to load
`<img src="my-image" alt="this image contain a boy">`

- HOW TO ADD HEADING
we use headings in HTML to define a title to a sections, we have 6 different sizes from 1 to 6
1 is the most importand one
6 is the less important one.
we must use headings as a hierarchy, because the browser indexing you page depending on a heading, and this useful for search engine optimization 

- HOW TO ADD PARAGRAPH
-> p: is an element used to add paragraph to your webpage
`<p>this is paragraph</p>`

- FORMATTING (DEL)
-> del: is an element that allow us to add line over the text to make it as deleted
`<del>this is delete text</del>`

- HOW TO ADD BUTTON WITH ICON
-> button: is an interactive element, usually used to submit a form
-> icon: we can insert icon by using fontawesome or any other library
`<button>
    <i>icon</i>
    Button text
</button>`


<::> CSS
- HOW TO SELECT THE ELEMENTS TO STYLE IT
-> *: called universal selector, this select all an elements in the webpage, we usually use it to reset user agent
-> .class: this selector, used to select an element that contain a class name
-> #id: this selector, used to select an element that have a unique name
-> descendant compinator: select an element based on his parent

- HOW TO SET WIDTH, HEIGHT
-> width: this property used to add width to the box
-> height: this property used to add height to the box

- HOW TO ADD PADDING, MARGIN
-> padding: this property add space between the content and the border, we can set values like that:
padding: 10px; this will add padding for all sides
padding: 10px 20px; this will add 10px to top,bottom and 20 to left/right
padding: 8px 5px 6px; this will add 8px to top, 5px to right, 6px to bottom, and the left side will take 5px from right side
padding: 10px 20px 14px 35px; will add top 10px, right 20px, bottom 14px, left 35px,
also we can use padding-top, padding-bottom, padding-left, padding-right

-> margin: this property add space outside the box, and the details of it is same as padding

- HOW TO CENTER THE CONTAINER
-> we need to the box to be block, and add margin with value auto, to tell browser to calculate the available space in left/right

- HOW TO ROUNDED THE BORDERS
-> border-radius: this proberty allow us to round border, it takes four values(top, right, bottom, left)

- HOW TO ADD A SPACE BETWEEN LETTERS
-> letter-space: this property allow us to add space between letters

- HOW TO CHANGE THE FONT STYLE, WEIGHT, SIZE
-> font-family: this property allow us to change the font style, either @font or @import 
-> font-weight: this property allow us to change the weight, either bold or light
-> font-size: this property allow us to set the size of the font

- HOW TO CHANGE THE DEFAULT COLOR OF FONT
-> color: this property allow us to change a color

- HOW TO SET THE BACKGROUND COLOR
-> background-color: this property allow us to change the color of the background

- HOW TO CHANGE THE BACKGROUND COLOR OF THE BUTTON WHEN THE USER HOVER OVER IT
-> here we will use :hover pseudo class, pseudo class select the element based on specific state 

- HOW TO SET THE BACKGROUND IMAGE 
-> background-image: we use this to insert an image
-> background-repeat: this property used to repeat your image if your page have available space (repeat(default)/no-repeat)
-> background-position: this property allow us to change the position of an image, we can use (top, right, bottom, left) or percentages (x,y)
-> background-attachment: this property allow us to make our image fixed in container
-> background-size: this property allow us to set a size of the image, (cover)

- HOW TO USE THE COLOR WELL
-> text: this represent the color based his name (black, white)
-> hex: stands for hexadecimal #123456, we can use 3 or 6 letters, the value will be between 00 and ff
-> rgba: stands for rgba(red, green, blue, alpha), the value is between 0-255
-> hsla: stands for hsla(hue, saturation, lightness, alpha), the value is between 0-350
hue: is a degree of the color wheel 
saturation: is a percentage value, 0% means shade of gray, and 100% is the full color
lightness: is also percentage value, 0% is black, 50% neither light or dark, 100% is white

- HOW CAN MAKE TWO DIFFERENCE SIZES 
    <:> USE MOBILE TO DESKTOP TECHNIQUE
    <:> USE MEDIA QUERY TO DO THAT
    <:> IF THE SCREEN SIZE EQUAL OR LOWER THAN 375px, ADD MOBILE STYLE
    <:> IF THE SCREEN SIZE GREATER THAN 375px, ADD DESKTOP STYLE
    <:> FOCUS ON STYLE THE ELEMENTS, JUST ADD COLORS, FONTS, ANY THING CHANGABLE LEAVE IT