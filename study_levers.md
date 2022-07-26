### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Colored Levers

## Step 1
We'll need to flip all four levers in order to open the door, but we're not quick enough to do it manually. See if you could figure out the order they need to be flipped and a way to do it quickly.

#### ~ tutorialhint 
Something about those colored carpets seem weird. Use the ``||hoc22.teleport to <color> lever||`` blocks to quickly move yourself between levers.

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
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.77
```