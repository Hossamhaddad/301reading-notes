# CSS Grid
## CSS Grid Layout is the most powerful layout system available in CSS , it can handle both columns and rows .

##  You work with Grid Layout by applying CSS rules both to a parent element which becomes the Grid Container and to that element’s children .

### Some Properties for the Grid Container:
1. #### display
2. #### grid-template-rows
3. #### grid-template-columns
4. #### grid-gap
5. ####  place-items
6. #### grid-auto-flow

### Some Properties for the Grid Items:
1. #### grid-column-start
2. #### grid-row-start
3. #### grid-row
4. #### grid-area
5. #### align-self
6. #### grid-column-end

## When sizing rows and columns, you can use all the lengths you are used to, like px, rem, %, etc, but you also have keywords like min-content, max-content.


## There is repeat() function, which saves some typing, like making 10 columns: grid-template-columns: repeat(10, 1fr); .

## The ‘Holy Grail’ layout describes a page with a header and footer that stick at the top and bottom of the window respectively, and a content section that is split into two sidebars and the main content sits between them.


## CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns. Finally two dimensional layouts are becoming simpler!