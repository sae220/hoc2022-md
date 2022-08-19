### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Open Doors

## Step 1
Each one of those holes represent a chamber door. Fill all four corners to open the chambers so we could get inside!

#### ~ tutorialhint 
Use the ``||hoc22.cursor move <direction>||`` block to move the cursor into position and then use ``||hoc22.place block||`` to fill the hole. Once all the holes are filled, the chamber doors should open.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(2)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```