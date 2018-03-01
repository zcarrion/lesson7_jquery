## Project Name:  Recipe Display Application

### Course Title:
Web Application Development

### Assignment Date:  
02/28/2018

### Student Name:  
Zaida Carrion-Rodriguez

### Project Description:
In this assignments we will used jQuery to access elements in order to provide them with an event (action) when a user click the headers.  Some of the steps will be: creating the script.js file that will be included in the html document (index.html) as a script just previous to the ending tag of the body., as well as the jQuery library file, in order to link them.  To js files will be created in order to add Interactivity in different ways, to the h3 element some functions with events, will be created. Methods use will be next(), click(), fadeIn(), and animate(), and css manipulation to the hover() for the second version.

### View Project Online:
http://zcarrion.github.io/lesson7_jquery/

### Lessons Learned in the Assignment:
1. What is jQuery and the benefits: jQuery is a JavaScript library which is commonly use in order to facilitate the use of JavaScript by referencing the jQuery library.  By adding the jQuery library file to the documents and linking it to the html document.  The statements in jQuery starts with $ instead of “jQuery”.   The basic syntax is:  $(selector).action( )  . The $ defines the use of jQuery, the selector to access the element, and the action to perform the event.  In order to avoid the jQuery code to load before the document loading is good practice to user first:  $(document).ready(function){ Query Methods here});
2. Common events (methods).  jQuery events are actions of a web after a called event, for example, moving a mouser over an element and creating an action for it.  It has two steps:  first, assigned the event to the element (such as click), and then define what should happened in which a function must be passed to the event.  Click( ) is a common method that attach an event handler(click) to an element. Other common methods are:  dblclick() in which an action is performed after double-click an element; mouseenter() in which a function is executed after the mouse enters the HTML element; mouseleave(), in which a function is execute after the mouse leaves the element; hover() that takes 2 functions, since is a combination of mouseenter() and mouseleave(); text() that will return the text (or change it) within the selected element.    
3.jQuery traversing: which means to move through the DOM tree in order to find (or select) the HTML element based on their relation to other element.  Find() is one of the methods used to traverse the DOM by specifying the element and the parent of it: $(“parent”).find(“element”);.  Other methods such as:  first(), to find the first element and last() to find last element.  Method chaining is calling multiple methods to select an element. 

