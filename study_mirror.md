### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Wrong Reflection

## Step 1
Things in the mirror appear differently than in the room. Find all the differences and modify the room to make them match.

#### ~ tutorialhint 
Pay close attention to the lights and use the levers to match them up. Then move the cusor above the fireplace using ``||hoc22.cursor move <direction>||`` to select a position and ``||hoc22.place block||`` to place a block in that position.

```ghost
    hoc22.cursorMove(ColoredBlockDirection.Up)
    hoc22.placeBlock()
    for (let index = 0; index < 4; index++) {    }

```
```template
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Down)
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Left)
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Left)
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Left)
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Left)
    hoc22.placeBlock()
    hoc22.cursorMove(ColoredBlockDirection.Up)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.27
```