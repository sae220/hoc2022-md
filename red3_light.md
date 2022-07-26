### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Red3 - Light Power

## Step 1
Use the cursor to toggle all of the lights on. Once all the lights are on the door will open.

#### ~ tutorialhint 
Make sure you are toggling the light in every loop and moving the cusor by one each time. Some lights will already be on!



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
    hoc22.toggleLight()
    hoc22.cursorMoveOrientationOneRight(1)       
        }
     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```