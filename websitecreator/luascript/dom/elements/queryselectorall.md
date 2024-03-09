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

# querySelectorAll

The method **`querySelectorAll()`** returns all Elements within the element that matches the specified selector, or group of selectors. If no matches are found, `null` is returned.

Querys

<table><thead><tr><th>Symbol</th><th>Query</th><th data-hidden></th></tr></thead><tbody><tr><td>#</td><td>id</td><td></td></tr><tr><td>.</td><td>class</td><td></td></tr><tr><td>&#x3C;blank></td><td>tag</td><td></td></tr></tbody></table>

Example

```javascript
elem.querySelectorAll("#id") // Returns ALL element with the ID of id
```

```javascript
elem.querySelectorAll(".id") // Returns ALL element with the className of id
```

```javascript
elem.querySelectorAll("label") // Returns ALL element that are a LABEL
```
