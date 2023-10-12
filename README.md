CONQUERING RESPONSIVE LAYOUTS 
## DAY 9- FLEXBOX CHALLENGE

In these i learned a lot about how `display:flex;` will automatically create `flex-container` as the parent and `flex-item` as the child. 

flex-container usually have ## flex-direction:row; by default.
flex-items by default will want to become column inside of their flex container. [the direct children are becoming the column]

I also learned that there are two ways we can create spacing between column
1. GAP: by setting gap (em or px) it create a space between each one of the flex-item and does not affect the outside space.

2. [.col+.col{margin-left:;}] this is called COMBINATOR. This is selecting the adjacent siblings. If a .col has an adjacent sibling of .col, it going to select it(i.e it is only lookingif something come before it).

i also got to understand that [justify-content:space-between;] is about spacing out and justifying space in between things. 