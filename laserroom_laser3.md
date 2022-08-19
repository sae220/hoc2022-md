### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
Solid blocks stop the laser! Slide all 3 rows on the floor to make the laser pass-through the glass blocks and turn on the light at the other side. 

#### ~ tutorialhint 
Use the ``||hoc22.slide||`` blocks to select which row you and to move, and the direction it should move in.



```ghost
    hoc22.slideGreenRow()
    hoc22.slideYellowRow()
```
```template
    hoc22.slideGreenRow(TwoDirection.Left)
    hoc22.slideYellowRow(TwoDirection.Left)
    hoc22.slideRedRow(TwoDirection.Left)
    hoc22.slideRedRow(TwoDirection.Left)
    hoc22.slideRedRow(TwoDirection.Left)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```