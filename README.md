# Course details
With over five billion global internet users in 2023, there is high demand to build web-based technologies, and it’s one of the most common platforms in software development. This course offers a project-based approach where beginners can get started with a hands-on approach to learning. Microsoft developer advocates Jasmine Greenaway and Nitya Narasimhan show you the tools of web development so you can start coding in HTML, CSS, and JavaScript. Plus, learn how artificial intelligence tools like Copilot and ChatGPT can assist in your web development.

[Course Link](https://www.linkedin.com/learning/html-css-and-javascript-building-the-web)

-------
## What I learned
----
1. [HTML Essential](#html)
2. [CSS Cascading Style Sheet](#css)

---
### HTML
HTML starts with 

``<html><html>``
You can add anything under this structure:
```html
<!DOCTYPE html>

<html>
  <head lang="en"> <!-- Header goes here -->
    <title>Welcome to the virtual terrarium</title> 
    <meta charset="utf-8" /> <!-- Author information goes here -->
    <meta name="viewport" content="width=device-width, initial-scale=1" /> <!-- Set the web view width-->
    <!-- import the webpage's stylesheet -->
	<link rel="stylesheet" href="" />
	<!-- import the webpage's JavaScript file -->
	<script src="" defer></script>
    <>
  </head>
  <body>
    <h1>My Terrarium</h1>
    <div> <!-- div acts as a container for all the content-->
    </div>
  </body>

</html>
```
### CSS
CSS is the style added to your HTML

``/* */`` Is used as comments in CSS

1.  Stylesheets & Setup
```css
<!-- import the webpage's stylesheet -->
<link rel="stylesheet" href="./style.css" />
```


2.  Cascading & Inheritance
``Cascading`` is like the flow of design decisions in your home. 
In this "cascade",the style set by you (the website developer) takes priority over the default style provided by the browser.
Styles you set "inline" in your HTML can override styles you set set externally in a stylesheet.
```css
/*Top Priority: Add an inline style in html*/
<h1 style="color: red">My Terrarium</h1>
/* Default style: adding this style to the css stylesheet */
h1 {
  color: blue;
}
```
``Inheritance``: is like inheriting design elements from your family.
<div style="border-left: 4px solid blue;
 background-color: #42a5f5; padding: 10px; font-color: black">
  <strong>Notes:</strong> Set the body's font to a given font, and check to see a nested element's font.
</div>

```css
body {
  font-family: helvetica, arial, sans-serif;
}
h1 {
  font-family: "Lobster", cursive;
}
```
3.  Selectors & Properties

``Selectors``: Selectors are like the tools you use to choose specific areas of your home for improvement. 
```css
/* Give a unique style to an id: right-container*/
#right-container {
	right: 0px;
}

/* Give a unique style to a class: container*/

.container {
	background-color: #dae6d8;
	width: 15%;
	top: 0px;
	position: absolute;
	height: 100%;
	padding: 10px;
}
```


``Properties``: Properties are like the specific instructions you give to your contractor for each design element in your home. For example, you may specify the color, size, or position of a piece of furniture. In CSS, properties define the specific visual characteristics of an element.
<div style="border-left: 4px solid blue;
 background-color: #42a5f5; padding: 10px; font-color: black">
  <strong>Notes:</strong> Here is a <a href="https://www.w3schools.com/cssref/index.php">css properties list.</a>  
</div>

```css
/*display*/
.container {
    display: flex;
}
/*position*/
.header {
    position: fixed;
    top: 0;
    width: 100%;
}
/*margin*/
.box {
    margin: 20px;
}
```

1.  Layouts & Positioning

``Layouts``: Layouts are like the floor plans for your home. They determine how different elements are arranged and organized within a space.

``Positioning``: Positioning is like arranging furniture in your home. You can position elements relative to their normal flow or to other elements. CSS provides different positioning options, such as absolute, relative, and fixed, to control the placement of elements on the page.
<div style="border-left: 4px solid blue;
 background-color: #42a5f5; padding: 10px; font-color: black">
  <strong>Notes:</strong> A great <a href="https://codepen.io/Rotarepmi/pen/rjpNZY">website to try position in css.</a>  
</div>

5.  Transitions & Animations

``Animations``: Animations are like adding dynamic elements to your home. Just like you might have a moving sculpture or a rotating ceiling fan, CSS animations bring elements to life by adding motion and visual effects.

``Transitions``: Transitions are like smoothly transitioning between different design states in your home. For example, when you open a door, it transitions from closed to open. In CSS, transitions allow you to smoothly change the appearance of an element over a specified duration.

