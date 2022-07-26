### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Red 1 - Maze

## Step 1
The zombie chef needs you help getting through the maze to the emeralds on the other side. The lights on the wall seem to be associated with the doors in some way, but they only open when the other is closed. 

#### ~ tutorialhint 
Use the levers on the wall to make sure the zombie chef has a path to get through. Make sure you have a path open before you use the code to move! Once you have a path set, use the ``||hoc22.move NPC <number>||`` block to get them to the emerald blocks. 



```ghost
    hoc22.npcMoveForward(1)
    hoc22.npcMoveBack(1)
    hoc22.npcMoveLeft(1)
    hoc22.npcMoveRight(1)
```
```template
    hoc22.npcMoveForward(2)
    hoc22.npcMoveRight(3) 
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```