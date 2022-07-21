### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Sludge Room - Windy Bridge

## Step 1
Use your cursor to block the wind so you can walk across the bridge.

#### ~ tutorialhint 
Use the symbols and colors on the arrows of the cursor to place a block below the stair blocks where the wind is coming out.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.cursorMoveOrientationOneUp(1)   
    hoc22.placeBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```