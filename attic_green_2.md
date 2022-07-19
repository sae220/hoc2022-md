### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
Now that the trapdoor is open, move the Agent up two blocks to set it free.

#### ~ tutorialhint 
Move the Agent up two blocks using the ``||hoc22.agent move <direction> by <number>||`` block.



```ghost
    hoc22.agentMove(SixDirection.Up, 2)
```
```template
    hoc22.agentMove(SixDirection.Up, 1)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```