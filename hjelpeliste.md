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

<p>Paragraf</p>
<br>

```html
<a>
```

<a>Anchor</a> 
<p>works like a button that can sent you to links using <code>href=""</code></p>
<br>

```html
<butotn>
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

## JavaScript

```JavaScript
document. // is a selector for finding elements in the html file
getElementById('') // added begind document to select a id for exaple <h1 id="text">hei</h1>
.innerHTML = '' // used to change the html text shown
```

Variabler

```JavaScript
const name = '';
const name = 0;
// const is a consistan value of text or number

let name = '';
let name = 0;
// let is a flexible value of text or number

name += 1; // if name's let is a number this will add one | += is add to value
name == 'value'; // dosent need to be text but sets a value | == sets to value or number
name -= 1; // if name's let is a number this will remove one | -= is remove to value
```

example

```html
...
<body>
<p id="e2">Hallo</p>
<button onclick="document.getElementById('e2').innerHTML = 'Hei';">
</body>
<!--This whill change the "hallo" text to "Hei" when you press the button-->
```
