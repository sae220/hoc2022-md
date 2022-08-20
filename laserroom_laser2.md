### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
Solid blocks stop the laser! Slide the green and yellow rows on the floor to make the laser pass-through the glass blocks and turn on the light at the other side. 

#### ~ tutorialhint 
Use the ``||hoc22.slide||`` blocks to select which row you and to move, and the direction it should move in.



```ghost
    hoc22.slideGreenRow(TwoDirection.Left,1)
    hoc22.slideYellowRow(TwoDirection.Left,1)
```
```template
    hoc22.slideGreenRow(TwoDirection.Left,1)
    hoc22.slideYellowRow(TwoDirection.Left,1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.11
```