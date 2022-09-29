### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Cannons

## Step 1
Each time Agent has their own color, and there's matching colored rings around the Time Orb. Activate the cannons in the same order as the colored rings surrounding the Time Orb.

#### ~ tutorialhint 
Pay close attention to the colored rings around the Time Orb. Use the ``||hoc22.activate <color> cannon||`` blocks to match the order of rings around the Time Orb. Start from the outer most ring and work your way in.

```ghost
    hoc22.magentaCannon()
    hoc22.lightBlueCannon()
    hoc22.limeCannon()
    hoc22.yellowCannon()
```
```template       
    hoc22.lightBlueCannon()
    hoc22.limeCannon()
    hoc22.yellowCannon()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```