### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# スライドパズル

## ステップ 1
絵がめちゃくちゃになってしまったみたいだ！ブロックを押して絵を元に戻せるかやってみよう。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
``||hoc22.押す||``ブロックを使いピストンを動かし選んだ方向にブロックを移動させます。絵を元に戻すには最低3回動かす必要があります。

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
minecraft-hoc22=github:sae220/hoc22-ts
```