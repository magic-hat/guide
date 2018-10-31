---
title: Create a Complex JSX Element
---
## Create a Complex JSX Element

### Hint:
- It's important to remember that nested JSX must return one top level component. 
- The returned top level element may contain child elements.
- Make sure you've included an `h1`, a `p`, and an unordered list (`ul`) that contains three `li` items. These elements should all be children to a parent `div`.

### Example Solution:

```html
const JSX = <div>
  <h1>Heading.</h1>
  <p>Paragraph</p>
 <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
</div>;  
```
