# Ch 3 Object Literals p 100-105
* Property
  * When a variable is part of an object it is called a property
* Method
  * If a function is part of an object it is called a method
* Key
  * Properties and methods have a name and value. In objects they are called keys???
* Creating an object: literal notation
  * `checkAvailability`
  * When setting properties, treat the values like you would for variables: strings live in quotes and arrays live in square brackets
* Accessing an object and dot notation
  * `object.checkAvailability`
  * Commonly used when:
    * The name of the property or method contains special characters
    * The name of the property is a number
    * A variable is being used in place of the property name

# Ch 5 Document Object Model p 183-242
* DOM tree
  * Tree view of html code
* Application programming interface (API)
* Dom node
  * nodes of node tree where every element gets its own box
* Document node
  * node that represents the entire page
* NodeList
  * returned when a method can return more than one node
* Collection
  * a type of object
  * NodeLists are not arrays. They are objects called a collection
* live NodeList
  * When script updates page, NodeList is also updated
* static NodeList
  * NodeList is not updated to reflect changes made by script
* Untrusted data
  * Data you do not have complete control over
* Validation
  * Data visitors input 
* Summary
  * The browser represents the page using a DOM tree
  * DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes
  * You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax
  * Whenever a DOM query can return more than one node, it will always return a NodeList
  * From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques
  * An element node can contain multiple text nodes and child elements that are siblings of each other
  * In older browsers, implementation of the DOM is inconsistent
  * Browsers offer tools for viewing the DOM tree

  # Article: Understanding the Problem Domain is the Hardest Part of Programming
  * A familiar problem
  * Why problem domains are hard
    * The world is a messy place. Problem domains are hard to understand depending on your view point.
  * Programming is easy if you understand the problem domain
    * Understanding the problem is the most critical piece to solving the problem.
  * What can you do about it?
    * Focus on a particular part of the problem, not the whole thing. Piece it out.