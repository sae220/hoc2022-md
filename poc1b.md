### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Mob Weight

## Step 1
Make the scale add up to 10 lbs

Use ``||hoc22.summonWeight <mob>||``

```ghost
    hoc22.summonWeightChicken()
    hoc22.summonWeightCow()
    hoc22.summonWeightSheep()
    for (let index = 0; index < 4; index++) {
    	
    }    
```
```template
    for (let index = 0; index < 4; index++) {
    	hoc22.summonWeightChicken()
    }
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.64
```