### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Minecart Redirection

## Step 1
The mobs need to be sorted into the right passageways! Look at the mobs currently waiting to be sorted and make sure the code sorts them in the right order.

#### ~ tutorialhint 
Use the ``||hoc22.sort||`` blocks to send the mobs to the correct passageways. They will be released from right to left, so make sure you order them correctly in your code.



```ghost
    hoc22.minecraftSortingZombie(1)
    hoc22.minecraftSortingSkeleton(1)
    hoc22.minecraftSortingCreeper(1)
```
```template
    hoc22.minecraftSortingSkeleton(1)
    hoc22.minecraftSortingZombie(1)
    hoc22.minecraftSortingSkeleton(1)
    hoc22.minecraftSortingCreeper(1)
    hoc22.minecraftSortingZombie(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```