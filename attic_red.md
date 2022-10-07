### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
To open the Red door, the Agent will need some help. Move the Agent onto the Gold blocks in front of the Red door and then flip the lever down.

#### ~ tutorialhint 
Move the Agent forward 14 blocks using the ``||hoc22.agent move <direction> by <number>||`` block and then flip the lever down.



```ghost
    hoc22.agentMove(SixDirection.Up, 1)
```
```template
    hoc22.agentMove(SixDirection.Forward, 10)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.41
```