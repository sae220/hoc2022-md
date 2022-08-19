### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Light Power

## Step 1
Use the cursor to turn on all of the lights. Once all the lights are on the door will open.

#### ~ tutorialhint 
Use the ``||hoc22.cursor move <direction>||`` block to select a light and then ``||hoc22.turn on||`` to turn it on. Using a loop will make the code a lot simplier, but isn't required.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.toggleLight()
    for (let index = 0; index < 2; index++) {    }
```
```template  
    for (let index = 0; index < 3; index++) {
        hoc22.cursorMoveOrientationOneRight(1)   
        hoc22.toggleLight()    
    }
     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```