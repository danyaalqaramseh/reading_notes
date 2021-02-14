
# In JavaScript :

functions are objects. You can work with functions as if they were objects. For example, you can assign functions to variables, to array elements, and to other objects. They can also be passed around as arguments to other functions or be returned from those functions.

function message() {
alert("Greetings Linda!");
}
alert(typeof message);      // => function
alert(message instanceof Object);   // => true
 

We see that a function is indeed an object. JavaScript functions are a special type of objects, called function objects. A function object includes a string which holds the actual code -- the function body -- of the function. The code is literally just a string. Although not recommended, you can create a new function object by passing the built-in Function constructor a string of code, like so:

var body = "return Math.PI * radius * radius";
var circle = new Function("radius", body);
alert(circle(5)); // => 78.5398..
You can also create a new function with a custom constructor function (remember that by convention a constructor function always starts with an upper-case letter). In the code below we have a Book constructor function that is used to create book instances. In the constructor function we are assigning a function object to the getDetails property.

 

# JavaScript - Document Object Model or DOM
Every web page resides inside a browser window which can be considered as an object.

A Document object represents the HTML document that is displayed in that window. The Document object has various properties that refer to other objects which allow access to and modification of document content.

The way a document content is accessed and modified is called the Document Object Model, or DOM. The Objects are organized in a hierarchy. This hierarchical structure applies to the organization of objects in a Web document.

Window object − Top of the hierarchy. It is the outmost element of the object hierarchy.

Document object − Each HTML document that gets loaded into a window becomes a document object. The document contains the contents of the page.

Form object − Everything enclosed in the <form>...</form> tags sets the form object.

Form control elements − The form object contains all the elements defined for that object such as text fields, buttons, radio buttons, and checkboxes.

 

There are several DOMs in existence. The following sections explain each of these DOMs in detail and describe how you can use them to access and modify document content.

The Legacy DOM (Links to an external site.) − This is the model which was introduced in early versions of JavaScript language. It is well supported by all browsers, but allows access only to certain key portions of documents, such as forms, form elements, and images.

The W3C DOM (Links to an external site.) − This document object model allows access and modification of all document content and is standardized by the World Wide Web Consortium (W3C). This model is supported by almost all the modern browsers.

The IE4 DOM (Links to an external site.) − This document object model was introduced in Version 4 of Microsoft's Internet Explorer browser. IE 5 and later versions include support for most basic W3C DOM features