### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Potion Room - Vent

## Step 1
Move the Agent to the chest so it could open up the next section.

#### ~ tutorialhint 
Use the ``||hoc22.agent move <direction> by <number>||`` block to move the Agent to the chest.



```ghost
    hoc22.agentMove(SixDirection.Up, 1)
```
```template
    hoc22.agentMove(SixDirection.Forward, 4)  
    hoc22.agentMove(SixDirection.Left, 3)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```