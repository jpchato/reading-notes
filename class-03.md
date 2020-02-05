# Ch 3 Lists 62-73

## Keywords
* **Ordered Lists**
  * `<ol></ol>`
  * Lists where each item is numbered
* **Unordered lists**
  * `<ul></ul>`
  * Lists that begin with a bullet point
* **Definition Lists**
  * `<dl></dl>`
  * Made up of a set of terms along with defintions for those terms

## Summary
* 3 types of html lists: ordered, unordered, and definition
* Ordered lists use numbers
* Unordered lists use bullet points
* Definition lists are used to define keywords
* Lists can be nested inside one another

# Ch 13 Boxes 300-329

*  Box Dimensions
  * `width, height`
* Limiting Width
  * `min-width, max-width`
* Limiting Height
  * `min-height, max-height`
* Overflowing Content
  * `overflow`
* Border, Margin & Padding
  * Every box has a border. It separates the edges of boxes from each other.
  * Margins are on the outside edge of borders. Use it to create gaps between borders of adjacent boxes
  * Padding is the space between the border of a box and the content inside of it. Padding can increase readability
* White space & vertical margin
  * The space between items on a page
* Border width
  * `border-width`
* Border style
  * `border-style`
* Border color
  * `border-color`
* Shorthand
  * `border`
* Padding
  * `padding`
* Margin
  * `margin`
* Centering content
  * `left-margin` `right-margin` set to auto
* IE6 Box Model
* Change inline/block
  * `display`
* Hiding boxes
  * `visibility`
* CSS3: Border images
  * `border-image`
* Css3: box shadows
  * `box-shadow`
* CSS3: rounded corners
  * `border-radius`
* CSS3: elliptical shapes
  * `border-radius`

## Summary
* CSS treats each html element as if it has its own box
* You can use css to control the dimensions of a box
* You can also control the borders, margins and padding for each box with css
* It is possible to hide elements using the display and visibility properties
* Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes
* Legibility can be improved by controlling the width of boxes containing text and the leading
* CSS3 has introduced the ability to create image borders and rounded borders

# Ch 4 Decisions and Loops 162-182
* **Type coercion**
  * Convert data behind the scenes to complete an operation
* **weak typing**
  * data type for a value can change
* **strong typing**
  * Specifying what data type each variable will be
* **falsy**
  * Values that are treated as if they are false
* **truthy**
  * Values that are treated as if they are true
* **unary operator**
  * returns a result with just one operand
* Summary 
  * Conditional statemnts allow your code to make decision about what to do next
  * Comparison operators `===, !==, ==, !=, <, >, <=, =>` are used to compare two operands
  * Logical operators allow you to combine more than one set of comparison operators
  * if...else statements allow you to run one set of code if a condition is true, and another if it is false
  * switch satements allow you to compare a value against possible outcomes (and also provides a default option if none match)
  * Data types can be coerced from one type to another
  * All values evaluate to either truthy or falsy
  * There are three types of loop: for, while, and do...while. Each repeats a set of statements
  * 