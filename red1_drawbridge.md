### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Drawbridge

## Step 1
The enderman butler needs help getting across the river. Teleport them across the river to the diamond block, then move them into position to pull the lever.

#### ~ tutorialhint 
Teleport the enderman to the diamond block by using the ``||hoc22.teleport enderman||`` block. Then use the ``||hoc22.move enderman||`` block to position them and ``||hoc22.pull lever down||`` to flip the lever.



```ghost
    hoc22.endermanButlerMoveForward(1)
    hoc22.superJump()
    hoc22.pullLeverDown()
```
```template
    hoc22.endermanButlerMoveForward(2)
    hoc22.superJump()
    hoc22.endermanButlerMoveForward(2)
    hoc22.pullLeverDown()  
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```