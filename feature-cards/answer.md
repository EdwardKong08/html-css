Style feature cards with selectors: my answers

## 1. Which selector styles the full page or the page background?
Body 

## 2. Which selector styles the design that all cards use?
.material-card 

## 3. Which selector styles an element inside a section or a card?
.material-card p 

## 4. Which selector uses `>`?
.page-header p:last-child

## 5. Which selector changes the page on hover?
.resource-link:hover

## 6. Which selector changes the page on focus?
.resource-link:focus

## 7. Which two rules set the same property on one element, and which rule wins? Give the selectors, the property, the value that shows, and the reason.
Both .resource-link:hover and .resource-link:focus set the background-color to #------, so both show the same dark green because they have equal specificity.