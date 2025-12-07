# Tool Learning Log

## Tool: **QJuery**

## Project: **Preventing ElderLy Scam**

---

### 10/5/25:
* The purpose of jQuery is to make it much easier to use JavaScript on your website.
<p>The jQuery library contains the following features:</p>

* HTML/DOM manipulation
* CSS manipulation
* HTML event methods
* Effects and animations
* AJAX
* Utilities
<p>Tip:In addition, jQuery has plugins for almost any task out there.</p>

<h4>jQuery Syntax:</h4>
<p>The jQuery syntax is tailor-made for selecting HTML elements and performing some action on the element(s).Examples:</p>

* `$(this).hide() - hides the current element.`

* `$("p").hide() - hides all paragraph elements.`

* `$(".test").hide() - hides all elements with class="test".`

* `$("#test").hide() - hides the element with id="test".`
### 10/27:
*During this day i was basically just looking around all the possible of J-query.
<p> jQuery has the ability of java script like function</p>

* `heading.style.color = "blue";` changes the heading color to blue when clicked

* `<button id="myButton">Click on me!</button>` this creates a button that has the phrase click on me

*  `heading.textContent = "Click on me again!";` changes the phrase into click on me again

<p> this makes it which when you first click on the button you start with click on me but when you click again it says click on me again but its blue </p>

<p>I am just testing what J query has to offer but now i would follow every lesson rather than randomly tinker.</p>
<h3>11/10:</h3>

<h4>jQuery Selector:</h4>

* jQuery selectors allow you to select and manipulate HTML element(s).

* jQuery selectors are used to "find" (or select) HTML elements based on their name, id, classes, types, attributes, values of attributes and much more. It's based on the existing CSS Selectors, and in addition, it has some own custom selectors

* The jQuery element selector selects elements based on the element name.

<p>here are some codes and the function:</p>

* `$("*")Selects all elements`

* `$(this)Selects the current HTML element`

* `$("p.intro")Selects all <p> elements with class="intro"`

* `$("p:first")Selects the first <p> element`

* `$("ul li:first")Selects the first <li> element of the first <ul>`

* `$("ul li:first-child")	Selects the first <li> element of every </ul>`

* `$("[href]")Selects all elements with an href attribute`

* `$("a[target='_blank']")Selects all <a> elements with a target attribute value equal to "_blank"`

* `$("a[target!='_blank']")Selects all <a> elements with a target attribute value NOT equal to "_blank"`

* `$(":button")selects all <button> elements and <input> elements of type="button"`

* `$("tr:even")Selects all even <tr> elements`

* `$("tr:odd")Selects all odd <tr> elements`

### 11/17:
<h4>Jquery Events:</h4>

* All the different visitors' actions that a web page can respond to are called events.

* An event represents the precise moment when something happens.

<h4>Here are the codes and properties</h4>

* click()

   * The `click()` method attaches an event handler function to an HTML element.

   * The function is executed when the user clicks on the HTML element.

   * The following example says: When a click event fires on a `<p> element; hide the current <p>` element:
* dblclick()

   * The `dblclick()` method attaches an event handler function to an HTML element.
 
   * The function is executed when the user double-clicks on the HTML element

* mouseenter()

  * The `mouseenter()` method attaches an event handler function to an HTML element.
 
  * The function is executed when the mouse pointer enters the HTML element.
 
* mouseleave()

  * The `mouseleave()` method attaches an event handler function to an HTML element.

  * The function is executed when the mouse pointer leaves the HTML element.

* mousedown()

  * The `mousedown()` method attaches an event handler function to an HTML element.

  * The function is executed, when the left, middle or right mouse button is pressed down, while the mouse is over the HTML element
 
* mouseup()

  * The `mouseup()` method attaches an event handler function to an HTML element.

  * The function is executed, when the left, middle or right mouse button is released, while the mouse is over the HTML element
 
* hover()

  * The `hover()` method takes two functions and is a combination of the mouseenter() and mouseleave() methods.

  * The first function is executed when the mouse enters the HTML element, and the second function is executed when the mouse leaves the HTML element
 
* focus()

  * The `focus()` method attaches an event handler function to an HTML form field.

  * The function is executed when the form field gets focus:
 
* blur()

  * The `blur()` method attaches an event handler function to an HTML form field.

  * The function is executed when the form field loses focus:
 
* on()

  * The `on()` method attaches one or more event handlers for the selected elements.

  * Attach a click event to a <p> element
 
  <p>I learned that An event represents the precise moment when something happens allowing moving a mouse over an element, selecting a radio button, and clicking on an element </p>
