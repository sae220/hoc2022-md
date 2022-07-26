### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Greenhouse - Flower Planting

## Step 1
Oh no! It looks like the water isn't getting to where we want it to go. Fill in all the holes so the water can flow correctly. Try modifying the default code before you create your own.

#### ~ tutorialhint 
Move the cusor using the ``||hoc22.cursor move <direction>||`` block and then use ``||hoc22.place block||`` to place a block in that position. Fill in all 6 holes that are above the black concrete to continue.



```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.flowerPlantingRedFlower()
    hoc22.flowerPlantingYellowFlower()
    hoc22.flowerPlantingBlueFlower()
    for (let index = 0; index < 2; index++) {    }
```
```template
    for (let index = 0; index < 5; index++) {
        hoc22.flowerPlantingBlueFlower() 
        hoc22.cursorMoveOrientationOneRight(1)    
        } 
    hoc22.cursorMoveOrientationOneDown(1) 
    for (let index = 0; index < 4; index++) {
        hoc22.flowerPlantingYellowFlower()  
        hoc22.cursorMoveOrientationOneLeft(1)  
        }         
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```