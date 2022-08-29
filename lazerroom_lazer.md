### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laser Puzzle

## Step 1
Solid blocks stop the laser! Slide the green row on the floor to make the laser pass-through the glass blocks and turn on the light at the other side. 

#### ~ tutorialhint 
Use the ``||hoc22.slide||`` blocks to select which row you want to move, and the direction it should move in. The block that slides into the hole will exit on the other side.



```ghost
    hoc22.slideGreenRow(TwoDirection.Left,1)

```
```template
    hoc22.slideGreenRow(TwoDirection.Left,1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.11
```