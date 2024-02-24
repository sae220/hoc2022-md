### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# 間違った鏡

## ステップ 1
暖炉の上のカボチャがこの部屋と鏡の中とでどこか違う。同じにしてみてください。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
``||hoc22.カーソルを移動させる||``ブロックを使い暖炉の上のカーソルの位置を決め、``||hoc22.カボチャを置く||``ブロックを使いその位置にカボチャを置いてください。

```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placePumpkin()
    for (let index = 0; index < 2; index++) {}

```
```template
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.placePumpkin()
    hoc22.cursorMoveOrientationOneLeft(1)
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```