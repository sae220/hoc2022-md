### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Lazer Room - Lazer Puzzle

## Step 1
Solid blocks stop the lazer! Slide the rows on the floor to make the lazer go through the glass blocks instead. 

#### ~ tutorialhint 
The lazer needs to reach the lights at the end. You will need to slide the red row more than once, so add multiple blocks!



```ghost
    hoc22.slideGreenRow()
    hoc22.slideYellowRow()
    hoc22.slideRedRow()
```
```template
    hoc22.slideGreenRow(TwoDirection.Left)
    hoc22.slideYellowRow(TwoDirection.Left)
    hoc22.slideRedRow(TwoDirection.Right)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```