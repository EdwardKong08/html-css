Responsive portfolio grid: my answers

## 1. Which element became the grid container?
The .portfolio-grid section became the grid container because it holds all the resource cards.

## 2. Which elements became the grid items?
The five .resource-card articles became the grid items.

## 3. Which rule makes the columns for wide screens?
grid-template-columns: repeat(4, minmax(0, 1fr)); creates four equal columns.

## 4. Which rule changes the layout for a browser window of medium width?
The @media (max-width: 900px) rule changes the layout to two columns.

## 5. Which rule stops the featured card from making the phone layout too wide?
grid-column: auto; resets the featured card so it fits into one column on small screens.