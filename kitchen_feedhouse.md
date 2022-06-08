### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Feed the House

## Step 1
The house is hungry! And what better to feed it than apples, salmon, and mushroom stew! See if you could figure out how many of each ingredient the house requires. 

#### ~ tutorialhint 
Pay attention to how many zombie chefs go by with each ingredient. Use the ``||hoc22.feed house <ingredient>||`` blocks to feed the house the required amount.

```ghost
    hoc22.feedHouseApple()
    hoc22.feedHouseSalmon()
    hoc22.feedHouseMushroomStew()
    for (let index = 0; index < 4; index++) {    }

```
```template
    hoc22.feedHouseApple()
    hoc22.feedHouseApple()
    hoc22.feedHouseSalmon()
    hoc22.feedHouseSalmon()
    hoc22.feedHouseMushroomStew()
    hoc22.feedHouseMushroomStew()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.29
```