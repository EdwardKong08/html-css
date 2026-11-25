CSS selectors and which rule wins: my answers
1. When must you use a class selector, and not an element selector?

you must use a class selector when you want to style a specific group or element, instead of changing all elements with the same name.

2. What does the space mean in .material-shelf p?
The space in .material-shelf p means it selects all paragraph elements inside the .material-shelf element.

3. What does > mean in .quick-nav > a?
The > means it selects only direct child elements inside .quick-nav.

4. Why must a button link have a :hover style and a :focus style?
A button link needs :hover and :focus styles so users can see when they move their mouse over it or select it using a keyboard.

5. If a and .quick-nav > a both set color on a navigation link, which selector wins in the stylesheet of this lesson?
The .quick-nav > a selector wins because it is more specific than the general a selector, even if the a rule appears later in the CSS.