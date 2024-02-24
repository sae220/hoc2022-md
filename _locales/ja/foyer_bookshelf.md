### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# 本棚前の階段

## ステップ 1
本棚の上に何かあるようだ。上に行く道を作ってみよう。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
``||hoc22.カーソルを移動させる||``ブロックを使い本棚に沿ってカーソルを移動させ、その後``||hoc22.ブロックを置く||``ブロックを使いその位置にブロックを置いてください。上に行くための階段を作ってください。

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 4; index++) {    }

```
```template
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
    hoc22.cursorMoveOrientationOneRight(3)
    hoc22.placeBlock()
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```