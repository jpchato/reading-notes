# Introduction HTML/CSS
* Is it hard to learn?
  * According to author, no (I guess we'll find out)
* The structure of this book
  * Covers HTML, CSS, and practical
* How people access the web
  * **Web broswers
    * firefox, chrome, ie, safari
    * Web address leads to web page
    * People don't update browsers regularly. Can't rely on visitors to your site being able to use latest functionality offered in browsers
   * **Web Server
     * Computer that hosts website
   * **Web hosting
     * companies who host websites for a fee
   * **Screen readers
     * Programs that read out contents of a computer screen
* How websites are created
  * HTML, CSS, JS, Flash
* How the web works
  * ISP, DNS (Domain Name System)
  * DNS is like a phone book. Connects you to the website you're looking for

# Chapter 1 HTML/CSS

## Structure
* How pages use structure
  * Structure helps readers understand how information is divided 
* Structuring word documents
  * Heading and subheadings reflect hierarchy of information. Therefore, structure helps communicate to readers what is important.
* HTML describes the structure of pages
  * HTML code is made up of **elements**.
  * Elements are *usually* made up of two **tags**: opening and closing tags
* HTML uses elements to describe the structure of pages
  * Tags are like boxes. They tell you something about the information contained between the opening and closing tags.
* A closer look at tags
  * `<p></p>`
  * < left-angle bracket, > right-angle bracket, p character, / forward slash, `<p>` opening tag, `</p>` closing tag
* Attributes tell us more about elements
  * Attributes provide additional information about the contents of an element
  * They appear on opening tag of the element and are made of two parts: **name** and **value** 
  * `<p lang="en-us"></p>` 
  * lang is the attribute name
  * en-us is the attribute value
* Body, head, & title
  * `<body></body>`
    * Everything between these tags in showing in the main browser window
  * `<head></head>`
    * This contains information about the page. 
    * Usually holds a `<title></title>` tag
  * `<title></title>`
    * Usually shown in top of browser or on page tab
* Creating a web page on a pc
  * Create in notepad and open with browser
* Looking at how other sites are built
  * right click>view source 
* Summary
  * HTML pages are text documents
  * HTML uses tags to give information special meaning 
  * Tags are referred to as elements
  * Tags come in pairs (usually). Opening and closing
  * Opening tags can carry attributes (but not always?)
  * Attributes need a name and value
  * HTML requires knowledge of tags (what they do and where they go)

# Chapter 8 HTML/CSS

## Extra Markup
* Several different versions of HTML have been used since the creation of the web (HTML 4, XHTML 1.0)
* Add comments to code so when you come back to it later the code can make sense
* Comments are not viewable on the web page, but they are viewable in the source code
* ID Attribute
    * Used to uniquely identify a specific element from other elements on the page
    * No two elements on the same page should have the same value for their id attributes (because then they would no longer be unique)
    * Giving an element a unique identity allows you to style it differently from other instances of the same element on the page
    * id attribute is known as the **global attribute** because it can be used on any element
* Class Attribute
    * When you want to identify several elements as being different from other elements on the page
    * Class attributes can be shared unlike ID attributes
* Block Elements
    * **Block level** elements always start on a new line in the browser (h1, p, ul, li)
* Inline Elements 
    * **Inline elements** continue on the same line as their neighboring elements (a, b, em, img)
* Grouping Text and Elements in a Block
    * div allows a set of elements to be grouped together in one block
    * The contents of a div element will start on a new line in the browser
    * Using an id or class attribute on the div element allows for CSS style rules to manipulate the amount of space that the div element occupies and can change the appearance of the elements contained within it
* Grouping Text and Elements Inline
    * span acts like an inline equivalent of div
    * It can be used to contain a piece of text where there is no other alternative element to help differentiate it from surrounding text
    * It can contain multiple inline elements
    * Mostly used in conjunction with CSS  to control the appearance of the elements within
* Iframes
    * An abbreviation of inline frame
    * Used to place a window in the webpage
    * src attribute specifies the url of the page to show in the frame
    * height attribute specifies the heigh of the frame
    * width attribute specifies the width
    * seamless is used when scrollbars are not needed
* Information About Your Pages
    * meta
        * The meta element lives in the head element and contains info about the webpage
        * Not visible to user but fulfills multiple purposes such as telling search engines about the page, who created it, and if it's time sensistive
        * An empty element that does not have a closing tag
        * Uses attributes to carry info
        * Name and attribute are the most common attributes in the meta tag
        * Some defined values for the name attribute: description, keywords, robots


# Chapter 17 HTML/CSS

## **HTML5 Layout**
* div is being replaced by more expressive terms such as header, page, article, paragraph, footer, etc
* List of HTML5 tags:
    * header `<header></header>`, footer `<footer></footer>`, nav `<nav></nav>`, article `<article></article>`, aside `<aside></aside>`, section `<section></section>`, hgroup `<hgroup></hgroup>`, figures `<figure><figcaption></figcaption></figure>`, div `<div></div>`
* HTML5 elements indicate the purpose of different parts of a web page as opposed to div
* Older browsers do not understand HTML5. They need to be told which elements are block-level elements
* Extra JavaScript is needed for HTML5 work in IE8


# Chapter 18 HTML/CSS

# Introduction JS

# Chapter 1 JS

