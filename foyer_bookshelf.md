### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bookcase Staircase

## Step 1
There seems to be something at the top of the bookcase. See if you could create a way to get up there.

#### ~ tutorialhint 
Move the cursor along the bookcase to select a position using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place block||`` to place a block in that position. Create a staircase to get to the top.

```ghost
    hoc22.cursorMoveOrientationOneUp()
    hoc22.cursorMoveOrientationOneDown()
    hoc22.cursorMoveOrientationOneLeft()
    hoc22.cursorMoveOrientationOneRight()
    hoc22.placeBlock()
    for (let index = 0; index < 4; index++) {    }

```
```template
    for (let index = 0; index < 6; index++) {
            hoc22.placeBlock()
            hoc22.cursorMoveOrientationOneRight()
        }
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneUp()
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp()
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.64
```