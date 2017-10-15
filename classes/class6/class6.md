# Class 6

# Designing On A Grid with CSS

[What is a grid?](https://gridbyexample.com/what/)  
	
We create a grid container by declaring ```display: grid``` or ```display: inline-grid``` on an element. As soon as we do this all direct *children* of that element will become grid items.

```
<div class="wrapper">
  <div>One</div>
  <div>Two</div>
  <div>Three</div>
  <div>Four</div>
  <div>Five</div>
</div>
```

I make the ```.wrapper``` a grid container.

```
.wrapper {
  display: grid;
}
```

* [Example](https://gridbyexample.com/examples/example1/) with code

### Resources

* [One Grid: Multiple Ways](https://css-tricks.com/css-grid-one-layout-multiple-ways/)

# Introduction to interaction with Javascript

## Javascript 101

### What's it for?

* Dynamic change
* Interaction!

### What does it do?
* Add new HTML to the page, change the existing content, modify styles
* React to user actions, run on mouse clicks, drags or key presses
* Send requests for data to a server
* Ask the visitor questions and show messages
* Store information locally on user's computer

##### Javascript can change HTML Attributes

```
<button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

```

##### Javascript can change CSS styles

```
document.getElementById("demo").style.fontSize = "25px";
```

##### Javascript can hide HTML elements

```
document.getElementById("demo").style.display = "none";
```

##### or show them

```
document.getElementById("demo").style.display = "block";
```
### It goes between ```<script>``` tags
* In HEAD or BODY

### Calling external scripts

```
<!DOCTYPE html>
<html>
<body>

<script src="myScript.js"></script>

</body>
</html>
```

#### Advantages of External scripts
* It separates HTML and code
* It makes HTML and JavaScript easier to read and maintain
* Cached JavaScript files can speed up page loads
* you can load several

```
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>
```

### Syntax
* Refers to the proper way to write Javascript code
* Javascript is a language with lines of instruction separate by semicolons ```;```

### Output

* Writing into an HTML element, using innerHTML.
* Writing into the HTML output using document.write().
* Writing into an alert box, using window.alert().
* Writing into the browser console, using console.log().


### Statements

* In HTML, JavaScript statements are "instructions" to be "executed" by the web browser.

```
document.getElementById("demo").innerHTML = "Hello Dolly.";
```
### Variables
* A variable holds data
* Declare a variable with ```var``` and assign a value with ```=```

```
var x;

x = 10;
```

* There are numbers, strings and booleans - which we will come back to
* Javascript is CaSe SeNsItIvE
* underscore is okay but hyphens are not!
* you can think of variables holding *numbers* and *strings* aka text

### Syntax
* lines end with a ;
* Flow order (top to bottom)
* comments start with //
* increment with ```++``` and decrement with ```--```
* add strings together with ```txt = string1 + " " + string2;```

### Functions are code blocks
* they break your code into manageable chunks
* name them. Put them in brackets

```
function myFunction() {
    document.getElementById("demo1").innerHTML = "Hello Dolly!";
    document.getElementById("demo2").innerHTML = "How are you?";
}
```

### Operators

* ```==``` equal to
* ```!=```	not equal
* ```>```	greater than
* ```<```	less than
* ```>=```	greater than or equal to
* ```<=``` less than or equal to

### Logic

* AND ```&&```
* OR ```||```
* NOT ```!```

## Homework

* [Intro to Javascript tutorial](https://www.w3schools.com/js/js_intro.asp)
	* from Introduction to Events
* Read [Facebook Faces A New World as Officials Rein in a Wild Web](https://www.nytimes.com/2017/09/17/technology/facebook-government-regulations.html?_r=1) and watch the 10 minute documentary
* Code a draft version of your project. Start by creating your landing page and its HTML content and CSS style. Organize your other pages and assets into folders. Get your links working. We will do a check-in and partner review of landing pages and content next class.
