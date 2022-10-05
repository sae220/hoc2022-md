### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Feed the House

## Step 1
The house is hungry! And what better to feed it than apples, salmon, and mushroom stew! See if you could figure out how many of each ingredient the house requires. 

#### ~ tutorialhint 
Pay attention to how many Zombie Chefs go by with each ingredient. Use the ``||hoc22.feed house <ingredient>||`` blocks to feed the house the required amount.

```ghost
    hoc22.feedHouseApple(1)
    hoc22.feedHouseSalmon(1)
    hoc22.feedHouseMushroomStew(1)

```
```template
    hoc22.feedHouseApple(2)
    hoc22.feedHouseSalmon(1)
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.38
```