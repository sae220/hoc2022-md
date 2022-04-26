### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Mob Weight

## Step 1
Make the scale add up to 10 lbs

Use ``||hoc22.summonWeight <mob>||``

```ghost
    hoc22.summonWeight(Weight.CHICKEN)
    for (let index = 0; index < 4; index++) {
    	
    }    
```
```template
    for (let index = 0; index < 4; index++) {
    	hoc22.summonWeight(Weight.CHICKEN)
    }
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.16
```