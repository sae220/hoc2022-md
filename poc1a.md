### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Color Dropper

## Step 1
Drop the right amount of colored blocks

Use ``||hoc22.summonColoredBlock <color>||``

```ghost
    hoc22.summonColoredBlockMagenta()
    hoc22.summonColoredBlockLightBlue()
    hoc22.summonColoredBlockYellow()
    hoc22.summonColoredBlockLime()
    for (let index = 0; index < 4; index++) {
    	
    }    
```
```template
    for (let index = 0; index < 1; index++) {
    	hoc22.summonColoredBlockYellow()
    }
    for (let index = 0; index < 5; index++) {
    	hoc22.summonColoredBlockLightBlue()
    }
    for (let index = 0; index < 3; index++) {
    	hoc22.summonColoredBlockMagenta()
    }
    for (let index = 0; index < 1; index++) {
    	hoc22.summonColoredBlockLime()
    }            
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.64
```