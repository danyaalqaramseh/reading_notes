# In this reading note we'll covor some importent things - pay attention 

# Introduction to HTML 

## First , lets talk about how people accsess the website :

1. **Browsers**
_People access websites using software called a web browser. Popular examples include : Firefox, Internet Explorer, Safari, Chrome, and Opera. In order to view a web page, users might type a web address into their browser, follow alink from another site, or use a bookmark._

2. **Web Servers**
_When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website. Web servers are special computers that are constantly connected to the Internet, and are optimized to send web pages out to people who request them_

3. **Screen readers**
_Screen readers are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.In the same way that many countries have legislations that require public buildings to be accessible to those with disabilities, many laws have also been passed that require websites be accessible to those with disabilities._

4. **Devices**
_People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones. It is important to remember that various devices have different screen sizes and some have faster connections to the web than others_


###### How the Web Works :

_When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server_


## Structure of the website : 

**HTML Uses Elements to Describe the Structure of Pages**

 **The Photo below show us the basic structure**

 ![Basic HTML Structure](https://www.google.com/url?sa=i&url=http%3A%2F%2Fwww.scriptingmaster.com%2Fhtml%2Fbasic-structure-HTML-document.asp&psig=AOvVaw0sTaCA-wep6lE4XYTDQwk3&ust=1612715625375000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCIDa6oLY1e4CFQAAAAAdAAAAABAI)

 _Which there is an open-close tag you can put the content between them and the attributes inside the open tag which also  provide additional information about the contents of an element , look at the pooto below :_

 ![attribute](http://web.simmons.edu/~grovesd/comm244/notes/week2/html-attributes.jpg)

 
 **The recap is:**
+ HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
+ Tags are often referred to as elements.
+ Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
+ Opening tags can carry attributes, which tell us more
about the content of that element.
+ Attributes require a name and a value.
+ To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go. 

# Lets talk about some Extra Markup 

###### DOCTYPES tell browsers which version of HTML you are using.
Since the web was first created, there have been several different versions of HTML. Each new version was designed to be an improvement 
on the last (with new elements and attributes added and older code removed).

Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of  HTML .

**Versions of HTML From 1997 to 2000**

 + HTML 4
 + XHTML 1.0
 + HTML5

 _for more info_ [click here](https://www.educba.com/versions-of-html/)

 ###### You can add comments to your code between the <!-- and --> markers.

 It is a good idea to add comments to your code because, no matter how familiar you are with the page at the time of writing it, when you come back to it later (or if someone else needs to look at the code), comments will make it much easier to understand.

Although comments are not visible to users in the main browser window, they can be viewed by anyone who looks at the source code behind the page.

###### The id and class attributes allow you to identify particular elements. 
- __*id attribute*__ :  id attribute is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character). It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).

The id attribute is known as a global attribute because it can be used on any element.

- __*class attribute*__ : Every HTML element can also carry a class attribute. Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page. **For example** you might have some paragraphs of text that contain information that is more important than others and want to distinguish these elements, or you might want to differentiate between links that point to other pages on your own site and links that point to external sites. 


###### The <div> and <span> elements allow you to group block-level and inline elements together.
Some elements will always appear to start on a new line in the browser window. These are known as block level elements.
Examples of block elements are <h1>, <p>, <ul>, and <li>. **div element** allows tou to group that 


Also some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements . Examples of inline elements are <a>, <b>, <em>, and <img>. **Span element** used to group its together .


###### <iframes> cut windows into your web pages through which other pages can be displayed.
There are a few attributes that you will need to know to use it:

- src
The src attribute specifies the URL of the page to show in the frame.
- height 
The height attribute specifies the height of the iframe in pixels.
- width
The width attribute specifies the width of the iframe in pixels
###### The <meta> tag allows you to supply all kinds of information about your web page.

###### Escape characters are used to include special characters in your pages such as <, >, and © 

![escape char](https://www.google.com/url?sa=i&url=https%3A%2F%2Fsuccess.appen.com%2Fhc%2Fen-us%2Farticles%2F201855899-Guide-to-Using-HTML-Tags-Characters-in-Labels&psig=AOvVaw1U8IaaVTZqCA9ddUK1YMmz&ust=1612721442970000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCOjnmtrt1e4CFQAAAAAdAAAAABAI)


# HTML layout 

- The new HTML5 elements indicate the purpose of different parts of a web page and help to describeits structure.

- The new elements provide clearer code (compared with using multiple <div> elements).
- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
- To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.




# To PROCESS & Design your webpage , you must focus on : 

1. _It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return._

2. _Site maps allow you to plan the structure of a site._

3. _Wireframes allow you to organize the information that will need to go on each page_


4. _Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them._

5. _You can differentiate between pieces of information using size, color, and style._

6. _You can use grouping and similarity to help simplify the information you present._




# Intro to JavaScript :

## JavaScript make the web page more interactive by :

1. **ACCESS CONTENT**
You can use JavaScript to select any element, attribute, or text from an
HTML page. For example:

+ Select the text inside all of the <hl> elements on a page
+ Select any elements that have a class attribute with a value of note
+ Find out what was entered into a text input whose id attribute has a value of email 

2. **MODIFY CONTENT**
You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example:
+ Add a paragraph of text after the first <hl> element
+ Change the value of class attributes to trigger new CSS rules for those elements
+ Change the size or position of an < img> element

3. **PROGRAM RULES**
You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example:
+ A gallery script could check which image a user clicked on and display a larger version of that image.
+ A mortgage calculator could collect values from a form, perform a ca lculation, and display repayments.
+ An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport).

4. **REACT TO EVENTS**
You can specify that a script should run when a specific event has occurred. For example, it could be run when:
- A button is pressed
- A link is clicked (or tapped) on
- A cursor hovers over an element
- Information is added to a form
- An interval of time has passed
- A web page has finished loading

## What is a Script and how can i creat one ?

+ A script is a series of instructions that the computer can follow in order to achieve a goal.
+ Each time the script runs, it might only use a subset of all the instructions.
+ Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.
+ To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task .

## How do i write a Script ?

+ It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension.

+ The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file).

+ If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created. 





















