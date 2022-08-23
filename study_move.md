### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Agent Move

## Step 1
Move the clay ball to the green block. (Interact with the lightbulb for help)

#### ~ tutorialhint  
Use ``||hoc22.clay ball move <direction> by <number>||`` to move the clay ball onto the green block. Adjust the direction variable and how many blocks down it moves in order to reach the green block.

```ghost
    hoc22.clayBallMove(SixDirection.Up, 5)
```
```template
    hoc22.clayBallMove(UP, 3)
    hoc22.clayBallMove(RIGHT, 2)
    hoc22.clayBallMove(DOWN, 2)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```