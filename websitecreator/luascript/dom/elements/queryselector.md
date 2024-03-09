---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# querySelector

The method **`querySelector()`** returns the first Element within the element that matches the specified selector, or group of selectors. If no matches are found, `null` is returned.

Querys

<table><thead><tr><th>Symbol</th><th>Query</th><th data-hidden></th></tr></thead><tbody><tr><td>#</td><td>id</td><td></td></tr><tr><td>.</td><td>class</td><td></td></tr><tr><td>&#x3C;blank></td><td>tag</td><td></td></tr></tbody></table>

Example

```javascript
elem.querySelector("#id") // Returns the FIRST element with the ID of id
```

```javascript
elem.querySelector(".id") // Returns the FIRST element with the className of id
```

```javascript
elem.querySelector("label") // Returns the FIRST element that is a LABEL
```
