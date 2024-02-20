## dnd-js

Create drag and drop event in DOM.

## Usage

```html
<div id="target">
```

```js
const element = document.getElementById("target");
const enableGrab = true;

const dnd = new DnD(element, enableGrab);

// Set mousedown event
dnd.start = function(e) {
	// ...
};

// Set mousemove event
dnd.move = function(e) {
	// ...
};

// Set mouseup event
dnd.end = function(e) {
	// ...
};

// destroy DnD
dnd.destroy();
```