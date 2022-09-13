### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Picture Slide

## Step 1
It seems like the picture got scrambled! Let's see if we could push the blocks around to put the picture back in order.

#### ~ tutorialhint 
Use the ``||hoc22.push <color> <direction>||`` blocks to trigger the pistons in order to move the blocks in the selected direction. It takes a minimum of three moves to put the picture back in order.

```ghost
    hoc22.mosaicPushUp()
    hoc22.mosaicPushDown()
    hoc22.mosaicPushLeft()
    hoc22.mosaicPushRight()
```
```template
    hoc22.mosaicPushLeft()
    hoc22.mosaicPushRight()
    hoc22.mosaicPushDown()
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.3.12
```