# Introduction HTML/CSS
* Is it hard to learn?
  * According to author, no (I guess we'll find out)
* The structure of this book
  * Covers HTML, CSS, and practical
* How people access the web
  * **Web broswers**
    * firefox, chrome, ie, safari
    * Web address leads to web page
    * People don't update browsers regularly. Can't rely on visitors to your site being able to use latest functionality offered in browsers
   * **Web Server**
     * Computer that hosts website
   * **Web hosting**
     * companies who host websites for a fee
   * **Screen readers**
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

## **Structuring Web Pages with HTML**
* Understand the target audience
    * age range, men or women, country, urban or rural, income, education, etc
    * individuals or companies
* Why will people visit website?
    * Understand peoples **motivations** and **goals** for visiting your website
* What are people trying to achieve?
* What information do visitors need?
    * Offer key information and some additional supporting information that might be useful
* How often will people visit the site?
    * How often people visit can determine how often it needs to get updated.  
    * For example, a news website probably gets updated every day
* Site Maps
    * Once you know what needs to go on the page, you can begin to organize it
    * Site Map= a diagram of pages that shows structure of the site
    * Card Sorting= Placing information that visitors might need to know on separate pieces of paper and organizing them into groups
* Wireframes
    * A  sketch of important information that needs to go on each page of a site
    * Shows hierarchy of info
    * Wireframes help ensure that all necessary info for a page is included
    * **DO NOT** include color scheme, font choices, backgrounds, or images for wireframe
    * Function, not form is key at this stage
*  Getting Your Message Across Using Design
    * Goal of visual design is to communicate
    * Organization of information on a webpage helps user identify what is important
    * Content
        * Webpages have lots of info to share.  Important to **prioritize** and **organize** the info
    * Prioritizing
        * Draw attention to or away from certain pieces of content by making them **distinct**
        * Designers use **visual hierarchy** to help users focus on what's important
    * Organizing
        * **Grouping** related content into **blocks** or **chunks** simplifies the page
        * Use **similar** visual style for certain types of information to help users associate that style with a certain type of content
* Visual Hierarchy
    * Use contrast to create a visual hierarchy that gets your key message across
    * Size
        * Larger elements grab users' attention
    * Color
        * Colors can draw attention, especially brighter colors
    * Style
        * Different style from background will draw attention
* Grouping and Similarity
    * Proximity
        * Items place close together are perceived to be related
    * Closure
        * Complicated arrangements promp readers to create real or imaginary boxes around elements
    * Continuance
        * Items placed in a line or curve are perceived to be related
    * White Space
        * Less white space between items=more related and vice versa
    * Color
        * Background colors behind items can emphasize their connection
    * Borders    
        * Boxes things together
* Designing Navigation
    * Helps people find where they want to go and helps them understand how site is organized
    * Components of good navigation:
        * Concise
            * No more than eight links
        * Clear
            * Single descriptive words for each link
        * Selective
            * Should reflect sections or content of site (no log in, legal, or search info)
        * Context
            * Let user know where they are in the website
            * Use a different color scheme or visual to indicate where nav is
        * Interactive
            * Link should be big enough to click on and visually distinct from other content on the page
        * Consistent
            * Primary navigation should remain the same
* Summary
  * Understand who audience is, why they're visiting the site, what info they want, and when they are likely to return
  * Site maps allow designers to plan site structure
  * Wireframes organize the info that will go on each web page
  * Design is communication. Visual hierarchy helps express what you are trying to say
  * Color, size, and style help make information distinct
  * Grouping and similarity help simplify the info being presented

# Introduction JS

## Javascript

* How JS makes web pages more interactive
    1. **Access** content
        * js can slect any element, attribute, or text from an html page
    2. **Modify** content
        * js can add to elements, attributes, and text of page (or remove)
    3. **Program** rules
        * Create a set of steps that browser will follow which allows it to modify the page
    4. **React** to events
        * Can have a script run when a specific event occurs

# Chapter 1 JS

## The ABC of Programming

### 1A What is a script and how do I create one?
* A script is a series of instructions
  * Comparable to recipes, handbooks, and manuals
  * Scripts are made up of instructions a computer can follow step-by-step
* Writing a script
  1. Define the goal
  2. Design the script
  3. Code each step
* Designing a script: tasks
  * Once you know the goal of a script, work out the individual tasks needed to achieve it
* Designing a script: steps
  * Each task can be broken down into steps
* From steps to code
  * Computers solve problems **programmatically**
    * They follow a series of instructions, one after another
* Designing a goal and designing the script
  * First detail the goals for a script
* Sketching out the tasks in a flowchart
  * Scripts will need to perform different tasks in different situations. Use flowcharts to work out how tasks will fit together
* Summary
  * A script is a series of instructions that computer can follow in order to acheive a goal
  * When the script runs, it doesn't always use all the instructions. It might only use a subset of the instructions
  * Computers solve tasks programmatically 
  * Script writing: goal>series of tasks>step by step buide for each task (flowhcarts help)

### 1B How do computers fit in with the world around them?
* Computers create models of the world using data
  * Computers have no predefined concept of what a hotel, car, dog, cat, hot dog, pizza, etc. is
  * Models are created using data
* Objects and properties
  * **Objects**
    * Physical things can be repreesnted as objects in computer programming
    * Things
  * **Properties**
    * Each property has a **name** and **value** 
    * Characteristics
* Events
  * Computer's way of saying "A thing just happened"
  * Programmers choose which events their script responds to
* Methods
  * Represent how people interact with an object in the real world
  * Need to know how to ask the questions and how to interpret answers you might receive
* Putting it all together
  * Computers use data to create models of things in the real world
  * Events, methods, and properites of an object all relate to each other
    * Events can trigger methods, and methods can retrieve or update an object's properties
* Web browsers are programs built using objects
* The document object represents an HTML page
  * Using the `document` object, you can access and change what content users see on the page and respond to how they interact with it
* How a browser sees a web page
  1. Receive a page as html code
  2. Create a model of the page and store it in memory
  3. Use a rendering engine to show the page on screen
* Summary
  * Computers create models of the world using data
  * The models use objects to represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with the computer
  * Programmers can write code to say "When this event occurs, run that code."
  * Web browsers use html markup to create a model of the web page. Each element creates its own node (which is a kind of object).
  * To make web pages interactive, you write code that uses the browser's model of the web page
  
### How do I write a script for a web page?
* How HTML, CSS, and js fit together
  * Each language forms a separate layer with a different purpose. html>css>js
* Progressive enhancement
  * The languages build upon each other to create content
* Javascript runs where it is found in the html
* Summary
  * Keep js code in its own js file. Js files are text files but they have the .js extension
  * HTML <script> element is used in html pages to tell the browser to load the js file

  

