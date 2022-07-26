### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
The Agent had just enough power to open the Green door. If you can figure out how to let more light in from above it, that will charge the Agent up even more.

#### ~ tutorialhint 
Look above the Agent and use the cursor to open the four trapdoors and let more light in. Use the colored arrows to help you choose which direction the cursor should move.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.openTrapdoor()
```
```template
    hoc22.openTrapdoor()
    hoc22.cursorMoveOrientationOneRight(2)
    hoc22.openTrapdoor()
    hoc22.cursorMoveOrientationOneUp(2)
    hoc22.openTrapdoor()
    hoc22.cursorMoveOrientationOneLeft(2)    
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```