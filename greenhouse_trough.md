### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Greenhouse - Trough

## Step 1
It looks like there is some type of pattern I need to follow to plant these flowers. Maybe the planters to the left and right could show me how I'm suppose to be planting these.

#### ~ tutorialhint 
Move the cusor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place <flower>||`` to place the correct flower. Match the pattern on the left and right to complete the puzzle.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    for (let index = 0; index < 2; index++) {
        hoc22.cursorMoveOrientationOneUp(1) 
        hoc22.placeBlock()    
        }
    hoc22.cursorMoveOrientationOneRight(2)   
    for (let index = 0; index < 2; index++) {
        hoc22.cursorMoveOrientationOneUp(1) 
        hoc22.placeBlock()    
        }      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```