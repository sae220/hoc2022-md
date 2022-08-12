### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Red 1 - Drawbridge

## Step 1
The enderman butler needs help getting across the river. See if you can help them by counting how many blocks they need to move forward before jumping.

#### ~ tutorialhint 
Count how many blocks the enderman butler needs to move forward and use the ``||hoc.move enderman butler||`` to move the enderman forward. Then have the enderman super jump across the river. Remember you can use multiple ``||hoc.move enderman butler||`` blocks. Make sure the enderman pulls the lever as well!



```ghost
    hoc22.endermanButlerMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()
```
```template
    hoc22.endermanButlerMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()  
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.79
```