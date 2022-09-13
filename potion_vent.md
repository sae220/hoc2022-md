### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Vent

## Step 1
Move the clay ball to the chest so it could open up the next section.

#### ~ tutorialhint 
Use the ``||hoc22.clay ball move <direction> by <number>||`` block to move the clay ball to the chest.



```ghost
    hoc22.clayBallMove(SixDirection.Up, 1)
```
```template
    hoc22.clayBallMove(SixDirection.Forward, 2)  
    hoc22.clayBallMove(SixDirection.Left, 3)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```