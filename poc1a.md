### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Color Dropper

## Step 1
Drop the right amount of colored blocks

Use ``||hoc22.summonColoredBlock <color>||``

```ghost
    hoc22.summonColoredBlock(YELLOW_CONCRETE)
    for (let index = 0; index < 4; index++) {
    	
    }    
```
```template
    for (let index = 0; index < 1; index++) {
    	hoc22.summonColoredBlock(YELLOW_CONCRETE)
    }
    for (let index = 0; index < 5; index++) {
    	hoc22.summonColoredBlock(LIGHT_BLUE_CONCRETE)
    }
    for (let index = 0; index < 3; index++) {
    	hoc22.summonColoredBlock(MAGENTA_CONCRETE)
    }
    for (let index = 0; index < 1; index++) {
    	hoc22.summonColoredBlock(LIME_CONCRETE)
    }            
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts
```