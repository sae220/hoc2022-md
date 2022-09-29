### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Agent Move

## Step 1
Move the clay ball to the gold block. (Interact with the lightbulb for help)

#### ~ tutorialhint  
Use ``||hoc22.clay ball move <direction> by <number>||`` to move the clay ball onto the gold block. Adjust the direction variable and how many blocks down it moves in order to reach the gold block.

```ghost
    hoc22.clayBallMove(SixDirection.Up, 5)
```
```template
    hoc22.clayBallMove(UP, 3)
    hoc22.clayBallMove(LEFT, 2)
    hoc22.clayBallMove(DOWN, 3)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```