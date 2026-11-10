# Hjelpeliste

## HTML
```html
<h1></h1>
```
<h1>Heading 1</h1>
<br>

```html
<h2></h2>
```

<h2>Heading 2</h2>
<br>

```html
<h3></h3>
```

<h3>Heading 3</h3>
<br>

```html
<p>
```

<p>Paragraph</p>
<br>

```html
<a>
```

<a>Anchor</a> 
<p>works like a button that can sent you to links using <code>href=""</code></p>
<br>

```html
<button>
```

<button>Button</button>
<p>a button often paired with <code>onclick=""</code> in javascript</p>
<br>

```html
<div>
```

<div>Divider<div>
<p>used to devide section for <code>css</code> formating styles</p>

## CSS
css er en style sheet den lar deg endre utsene av tingene du hvelger

```css
:root {
  --main: #000000; /* "--" makes main a varible we give said varible the contetns of the hex code for black*/
}

h1 {
  color: var(--main); /*this will change all <h1> to the main color*/
}

body {
  background-color: #f46721; /*this will chnage the body of the html to orange*/
}
```
## JavaScript

```JavaScript
document. // is a selector for finding elements in the html file
getElementById('') // added behind document to select a id for exaple <h1 id="text">hei</h1>
.innerHTML = '' // used to change the html text shown
```

Variabler

```JavaScript
const name = '';
const name = 0;
// const is a consistant value of text or number

let name = '';
let name = 0;
// let is a flexible value of text or number

name += 1; // if the variable is a "let", and it is a number this will add one | += is add to value
name == 'value'; // doesn't need to be text but sets a value | == sets to value or number
name -= 1; // if the variable is a "let", and it is a number this will remove one | -= is remove to value
```

example

```html
...
<body>
<p id="e2">Hallo</p>
<button onclick="document.getElementById('e2').innerHTML = 'Hei';">
</body>
<!--This will change the "hallo" text to "Hei" when you press the button-->
```

## Linking the css and js files

```html
<head>
  <link rel="stylesheet" href="style.css">
  <script src="script.js"></script>
</head>
```
