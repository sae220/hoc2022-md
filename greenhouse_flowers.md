### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Greenhouse - Flower Planting

## Step 1
Add some text describing the activity.

#### ~ tutorialhint 
Add some text explaining the answer in detail.



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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```