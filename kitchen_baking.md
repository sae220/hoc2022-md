### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Bake Bread

## Step 1
The zombie chef needs help making bread. Use the included blocks to create a recipe the zombie chef can follow.

#### ~ tutorialhint 
Think about the order of operations it takes to make bread. You'd first ``||hoc22.harvest wheat||``, but then what? There are exactly four steps.

```ghost
    hoc22.bakingBreadWheat()
    hoc22.bakingBreadGrain()
    hoc22.bakingBreadDough()
    hoc22.bakingBreadBread()
```
```template
    hoc22.bakingBreadWheat()
    hoc22.bakingBreadDough()
    hoc22.bakingBreadBread()
    hoc22.bakingBreadGrain()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.29
```