### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Greenhouse - Cracked Wall

## Step 1
We need more water! It looks like I can use the cursor to break some of these damaged bricks to get more water.

#### ~ tutorialhint 
Move the cusor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.break block||`` to break a block in that position. Break all 4 blocks to get enough water to get to the next puzzle. 



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.breakBlock()
```
```template
    hoc22.cursorMoveOrientationOneDown(1) 
    hoc22.breakBlock()
    hoc22.cursorMoveOrientationOneRight(4) 
    hoc22.breakBlock() 
    hoc22.cursorMoveOrientationOneDown(2)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.breakBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.79
```