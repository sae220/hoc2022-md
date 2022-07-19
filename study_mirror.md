### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Wrong Reflection

## Step 1
Things in the mirror appear differently than in the room. Find all the differences and modify the room to make them match.

#### ~ tutorialhint 
Move the cusor above the fireplace using ``||hoc22.cursor move <direction>||`` to select a position and ``||hoc22.place block||`` to place a block in that position.

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()

```
```template
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```