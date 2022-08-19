### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bridge Builder

## Step 1
Use your cursor to build a bridge that can help the crate minion reach the button! A path up will appear once the crate minion has pressed the button.

#### ~ tutorialhint 
Use the ``||hoc22.cursor move <direction>||`` block combined with ``||hoc22.place block||`` blocks to create a bridge to the button. The crate minion will walk to the button and press it once a bridge has been built for them.



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
        hoc22.placeBlock()
        hoc22.cursorMoveOrientationOneRight(1)   
    }
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```