### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Colored Levers

## Step 1
We'll need to flip all four levers in order to open the door, but we're not quick enough to do it manually. See if you could figure out the order they need to be flipped and program the Suite of Armor to do it for you.

#### ~ tutorialhint 
Use the ``||hoc22.flip <color> lever||`` blocks to move the Suit of Armor to the selected color and flip the lever. Pay close attention to how many pieces of carpet there are. That will give you a clue on the order.

```ghost
    hoc22.teleportLightBlueLever()
    hoc22.teleportMagentaLever()
    hoc22.teleportYellowLever()
    hoc22.teleportOrangeLever()
```
```template
    hoc22.teleportLightBlueLever()
    hoc22.teleportOrangeLever()
    hoc22.teleportYellowLever()
    hoc22.teleportMagentaLever()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```