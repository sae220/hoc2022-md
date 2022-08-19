### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Unlock the Trap

## Step 1
Now we have the chance to capture them! We need to align the 3 sections to open it!

#### ~ tutorialhint 
Rotate each section using the ``||hoc22.rotate <section> <direction> by <number>||`` blocks. Line up the colored paths between all 3 sections. Once that's done, we should be able to finally put a stop to those Time Agents!

```ghost
    hoc22.outerRingClockwise(1)
    hoc22.outerRingCounterclockwise(1)
    hoc22.middleRingClockwise(1)
    hoc22.middleRingCounterclockwise(1)
```
```template       
    hoc22.outerRingClockwise(1)
    hoc22.middleRingCounterclockwise(3)

```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.0
```