### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Sludge Room - Bridge Builder

## Step 1
Use your cursor to build a bridge that can help the zombie chef reach the button! A path up will appear once the zombie chef has pressed the button.

#### ~ tutorialhint 
Move the cursor one block at a time and place a block each time to the button. The zombie chef will walk to the button once a bridge has been built for them.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.cursorMoveOrientationOneUp(2)   
    hoc22.placeBlock()
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```