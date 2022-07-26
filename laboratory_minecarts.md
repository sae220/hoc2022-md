### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Laboratory - Minecraft Redirection

## Step 1
The mobs need to be sorted into the right spaces! Look at the mobs currently waiting to be sorted and make sure the code sorts them in the right order.

#### ~ tutorialhint 
The sorting tool with sort the mobs first from right to left. Count the mobs that are waiting from right to left and sort them correctly from top to bottom using the correct mob blocks.



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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.76
```