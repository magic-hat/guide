---
title: Render HTML Elements to the DOM
---
# Render HTML Elements to the DOM

## Hints
To render an element to the DOM, we use the following syntax:
````javascript
ReactDOM.render(<item to be rendered>, <where to be rendered>);
````
To target a specific DOM node, use this document method with the target node specified:
````javascript
document.getElementByID(<target node>)
````
Use the Document method `getElementByID()` within the `render()` method to solve this challenge.

## Solution

Following the syntax, we would add this line of code to render the JSX element to the `div` with the id of challenge-node.
````javascript
ReactDOM.render(JSX,document.getElementById('challenge-node'));
````
