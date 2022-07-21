### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Red 1 - Drawbridge

## Step 1
The zombie chef needs help getting across the river. See if you can help them by counting how many blocks they need to move forward before jumping.

#### ~ tutorialhint 
Count how many blocks the zombie chef needs to move forward and use the ``||hoc.move <number>||`` to move the zombie forward. Then have the zombie super jump across the river. Remember you can use multiple ``||hoc.move <number>||`` blocks. Make sure the zombie pulls the lever as well!



```ghost
    hoc22.zombieMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()
```
```template
    hoc22.zombieMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()  
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.75
```