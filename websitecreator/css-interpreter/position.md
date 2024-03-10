# position

The `position` CSS property sets how an element is positioned in a document. You can use the properties x, x-offset, y, y-offset or position to determine the final location of positioned elements

This positioning uses ROBLOX's UDim2 positioning with only scale and offset

Use the position property to change both the scale and offset of both x and y

Example

```css
x: 1; /* evaulates as 1px so returns 1 */
/* changes scale */
x-offset: 50%; /* evaulates as 0.5% so returns 0.5 */
/* changes offset */
y: 100%; /* evaulates as 100% so returns 1 */
/* changes scale */
y-offset: 50; /* evaulates as 50px so returns 50 */
/* changes offset */
position: 0.3 50 0.2 25; /* returns 0.3px 50px 0.2px 25px */
/* changes both scale and offset */
```
