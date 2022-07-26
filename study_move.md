### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Agent Move

## Step 1
Use ``||hoc22.agent move <direction> by <number>||`` to move the Agent onto the green block. (Interact with the lightbulb for help)

#### ~ tutorialhint 
Adjust the direction variable and how many blocks down it moves in order to reach the green block. 

```ghost
    hoc22.agentMove(SixDirection.Up, 5)
```
```template
    hoc22.agentMove(UP, 3)
    hoc22.agentMove(RIGHT, 2)
    hoc22.agentMove(DOWN, 2)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```