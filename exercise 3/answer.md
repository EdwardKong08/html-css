 CSS selectors and which rule wins: my answers
  1. When must you use a class selector, and not an element selector?
  You use a class selector when you want to style specific elements rather than all elements of the same type.

2. What does the space mean in `.material-shelf p`?
The space means a descendant selector, targeting all <p> elements inside an element with the class .material-shelf

3. What does `>` mean in `.quick-nav > a`?
The > means a direct child selector, targeting only <a> elements that are direct children of .quick-nav.

 4. Why must a button link have a `:hover` style and a `:focus` style?
 A :hover style shows visual feedback when the mouse is over the button, while a :focus style helps keyboard users see which button is selected.

 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
.quick-nav > a wins because it is more specific than the a element selector.
