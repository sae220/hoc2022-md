### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Weights

## Step 1
You need the scale to reach a weight of exactly 23lbs. Maybe there is a sign around here to tell me how much each mob weighs? 

#### ~ tutorialhint 
Use the `||hoc22.summon <mob>||` blocks to spawn in mobs to get a total weight of 23. A chicken is 1, a sheep is 3, and a cow is 5.



```ghost
    hoc22.summonWeightChicken(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightSheep(1)
```
```template
    hoc22.summonWeightSheep(1)
    hoc22.summonWeightCow(1)
    hoc22.summonWeightChicken(1)
      
```
```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```