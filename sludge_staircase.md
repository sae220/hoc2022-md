### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Sludge Room - Staircase

## Step 1
Add some text describing the activity.

#### ~ tutorialhint 
Add some text explaining the answer in detail.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {}
```
```template
    for (let index = 0; index < 2; index++) {
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneRight(1)    
        }
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```