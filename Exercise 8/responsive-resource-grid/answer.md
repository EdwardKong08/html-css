CSS Grid and media queries: my answers

## 1. Which element is the grid container on this page?
The .resource-grid section is the grid container because it holds all the resource cards.

## 2. Which elements are the grid items?
The five .resource-card articles are the grid items.

## 3. What does `1fr` mean in this grid?
1fr means one fraction of the available space in the grid.

## 4. Why does the highlighted card need a reset in the phone media query?
Because it spans two columns on the desktop. The reset makes it fit into one column on mobile.

## 5. Why must you test the same page at more than one width of the browser window?
To make sure the layout looks good and works properly on laptop, tablet and mobile screens.

## 6. Which change did you make? What changed in the browser, and which CSS property or media query caused it?
I changed the grid from three columns to two columns. The cards now appear in two columns. The grid-template-columns property caused this change. I also moved the highlighted card to the second card and changed the tablet breakpoint from 820px to 900px using the @media query.