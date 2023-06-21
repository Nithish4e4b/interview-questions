1.what is hoisting?
	Hoisting is a behavior in JavaScript where variable declarations and function declarations are moved to the top of their respective scopes at compile time, regardless of where they are actually written in the code. This means that a variable or function can be used before it is declared.

2.Difference between display:none and visiblity: hidden
	
	visibility:hidden hides the element, but it still takes up space in the layout.
	
	display:none removes the element from the document. It does not take up any space.

3.what is dom in html?
	The **HTML DOM** is an **Object Model** for **HTML**. It defines:

-   HTML elements as **objects**
-   **Properties** for all HTML elements
-   **Methods** for all HTML elements
-   **Events** for all HTML elements

4.what is dom in js?
	The **HTML DOM** is an **API** (Programming Interface) for **JavaScript**:

-   JavaScript can add/change/remove HTML elements
-   JavaScript can add/change/remove HTML attributes
-   JavaScript can add/change/remove CSS styles
-   JavaScript can react to HTML events
-   JavaScript can add/change/remove HTML events

5.difference between local storage vs session storage.
	**data in localStorage doesn't expire, data in sessionStorage is cleared when the page session ends**. Whenever a document is loaded in a particular tab in the browser, a unique page session gets created and assigned to that particular tab.

6.what is margin in css?
	used to create space around elements, outside of any defined borders

7.what is padding in css?
	used to generate space around an element's content, inside of any defined borders

8.what is border in css?
	**a shorthand property used to set the border on an element**.

9.Difference between display:none and visiblity: hidden
	**visibility:hidden** hides the element, but it still takes up space in the layout.
	**display:none** removes the element from the document. It does not take up any space.

10.What is Meta?
	used to specify character set, page description, keywords, author of the document, and viewport settings.

1.css box module?
	**the rectangular boxes—including their padding and margin—that are generated for elements and laid out according to the visual formatting model**.

2.what is spread operator?
	**allows us to quickly copy all or part of an existing array or object into another array or object**

3.what is splice?
	The splice() method _adds and/or removes array elements_. The splice() method overwrites the original array. Syntax

4.what is constructor?
	he `constructor()` method is a special method for creating and initializing objects created within a class.
	The `constructor()` method is called automatically when a class is initiated, and it has to have the exact name "constructor", in fact, if you do not have a constructor method, JavaScript will add an invisible and empty constructor method.

5.what is filter?
	The `filter()` method creates a new array filled with elements that pass a test provided by a function.
	The `filter()` method does not execute the function for empty elements.
	The `filter()` method does not change the original array.

6.what is forEach?
	The `forEach()` method calls a function for each element in an array.
	The `forEach()` method is not executed for empty elements.

7.what is iinclude()?
	The `includes()` method returns `true` if an array contains a specified value.
	The `includes()` method returns `false` if the value is not found.
	The `includes()` method is case sensitive.

8.what is indesof()?
	The `indexOf()` method returns the first index (position) of a specified value.
	The `indexOf()` method returns -1 if the value is not found.
	The `indexOf()` method starts at a specified index and searches from left to right.
	By default the search starts at the first element and ends at the last.
	Negative start values counts from the last element (but still searches from left to right).

9.what is map?
	`map()` creates a new array from calling a function for every array element.
	`map()` does not execute the function for empty elements.
	`map()` does not change the original array.

10.what is push?
	The `push()` method adds new items **to the end** of an array.

11.splice?
	The `slice()` method returns selected elements in an array, as a new array.

12.flex and grid
	**flexbox was designed for layout in one dimension - either a row or a column.** **Grid was designed for two-dimensional layout - rows, and columns at the same time**.




11.Prototype:

	Each object has a private property which holds a
	link to another object called its prototype.

12."this" keyword
	The popular 'this' keyword points to the gobal window object in the
	context of browsers when written inside a regualr function call. The
	'this' keyword points to the object to which the method is bond.

13.The methods - bind(), call(), apply() 
	are used to bind a function while
	passing the desired scope to the inner function.

14.Block elements:

	<div>, <p> - always starts on a new line
	browser add some space before and after the element
	Always takes up the full available width

15.Inline elements:

<span> - does not start on a new line

	Always takes up as much width as neccessary

16. Table:

	<table> - table
	
	<tr> - table row
	
	<th> - table header
	
	<td> - table data

17. inline:

	no line break without space

18. block:

	line break with space

19. inline-block:

	no line break with space

20. Pseudo-classes:

	A pseudo-class is used to define a special state of an element.

21. Position property in CSS:

	Static(default), Relative(normal flow), absolute(depends on parent),
	fixed(absolute), sticky(relative)

22. Mobile First Approach/Design:

	It is easier to scale a design up to larger screens than to scale
	it down to smaller screens. Due to the massive growth of Mobile
	browsing, this makes mobile first design a great development

workflow.

23. Bootstrap 
	is a free and open-source CSS framework directed at responsive,
	mobile-first front-end web development. It contains HTML, CSS and
	JavaScript-based design templates for typography, forms, buttons,
	navigation, and other interface components.
	Container: The container is the fundamental building block of the Bootstrap
	layout. It is used to center and align your content on the page,
	providing a responsive and fluid design.

24. DOM - Document Object Model

	The programming interface for interacting with an HTML document represented
	as a tree data structure. Each HTML element in the document is a node in
	the DOM tree, with nested content represented as children in the tree.
	--> provides an API
	--> Tree structure
	--> Elements & Text are nodes
	append --> Node + Text
	appendChild --> Only Node object

25. JavaScript is a single-threaded synchronous language which executes all the code
line by line in the order in which it is written.

26. In Asynchronous programming, you can do taks without waiting for a task to
complete its execution.

27. Callback - 
	pass a function as an argument to another function. The primary purpose
	of a callback is to execute code in response to an event.

1. Callback Hell: 
	nested callback is called callback hell

30. Callback serve a great purpose in asynchronous programming,

	There are 2 cases in which Callback is used,
	
	a. Mark completion of a long-running task.
	
	b. Execute a task after a long-running task.

30. async & await - 
	keywords introduced in ES8(ES2017), which are
	internally based on promises but makes the code more readable as 
	compared to promises.

31. When the keyword 'async' is prepended to a function, it can before 
	 safely assumed that a promise is returned from that function.


