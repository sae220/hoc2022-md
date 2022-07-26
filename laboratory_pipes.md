### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laboratory - Pipes

## Step 1
You'll need to add a specific amount of blocks to each of the hoppers. Maybe there is something in the room that can tell you how many?

#### ~ tutorialhint 
Count how many blocks are on the landing behind the puzzle and add that many blocks to the hoppers. Your default code should be the correct amount for the first 3 hoppers. 



```ghost
    hoc22.summonColoredBlockMagenta(1)
    hoc22.summonColoredBlockLightBlue(1)
    hoc22.summonColoredBlockYellow(1)
    hoc22.summonColoredBlockLime(1)
```
```template
    hoc22.summonColoredBlockYellow(2)
    hoc22.summonColoredBlockLightBlue(4) 
    hoc22.summonColoredBlockMagenta(3)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```