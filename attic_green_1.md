### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Attic Tutorial

## Step 1
The box with the orange arrow on the floor is your cursor. You'll use it throughout the house to minipulate blocks. In this activity we'll use it to open the trapdoor and release the Agent. (Interact with the lightbulb for more help)

#### ~ tutorialhint 
Move the cursor three blocks forward using the ``||hoc22.cursor move||`` block and then use the ``||hoc22.open trapdoor||`` block to release the Agent.



```ghost
    hoc22.cursorMoveOrientationOneUp(3)
    hoc22.openTrapdoor()
```
```template
    hoc22.cursorMoveOrientationOneUp(2)     
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```