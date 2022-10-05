### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Plate Swap

## Step 1
It seems the Zombie Chef gave everyone the wrong meal! Search the kitchen for the menu and make sure everyone ends up with the correct meal.

#### ~ tutorialhint 
Use the ``||hoc22.swap <color> side||`` blocks to swap the dishes until everyone has their correct meals. The minimum amount of swaps required is three.

```ghost
    hoc22.dinnerTableSwapGreen()
    hoc22.dinnerTableSwapBlue()
    hoc22.dinnerTableSwapYellow()
    hoc22.dinnerTableSwapRed()
```
```template
    hoc22.dinnerTableSwapGreen()
    hoc22.dinnerTableSwapBlue()
    hoc22.dinnerTableSwapYellow()
    hoc22.dinnerTableSwapRed()

```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.38
```