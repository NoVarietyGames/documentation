# size

Use the **`size`** CSS property to define the size of the element. To change width and height use the respective properties,&#x20;

width | width-offset

height | height-offset

This Sizing uses ROBLOX's UDim2 size with only scale and offset

Use the size property to change both the scale and offset of both x and y

Example

```css
width: 1px; /* 1 returned */
/* changes scale */
width-offset: 50px; /* 50 returned */
/* changes offset */
height: 50%; /* 0.5 returned */
/* changes scale */
height-offset: 100% /* 1 returned */
/* changes offset */
size: 0.3px 50px 1% 25px;
/* changes both scale and offset */
```
