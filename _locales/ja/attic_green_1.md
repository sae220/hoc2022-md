### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# 屋根裏のチュートリアル

## ステップ 1
床にあるオレンジの矢印の箱がカーソルです。カーソルは、家のあちこちでブロックを変えるのに使います。このアクティビティでは、カーソルを使ってトラップドアを開け、エージェントを解放します。(ヒントが欲しい場合は、電球ボタンを押してください)。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
``||hoc22.カーソルを動かす||``ブロックを使いカーソルを前に3ブロック動かし、 その後``||hoc22.open trapdoor||``ブロックを使いエージェントを解放してください。


```ghost
    hoc22.cursorMoveOrientationOneUp(3)
    hoc22.openTrapdoor()
```
```template
    hoc22.cursorMoveOrientationOneUp(2)     
```
```package
minecraft-hoc22=github:sae220/hoc22-ts
```