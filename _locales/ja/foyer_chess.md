### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# チェスの駒

## ステップ 1
キングとクイーンを解放したが、ドアはまだ開かない。駒が間違った位置にあるのだろう。2つの駒を正しい位置に移動させ、ここから脱出しましょう！

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
チェス盤は縦横で日付を表している。部屋の中を探してキングとクイーンがどの位置にあるべきか調べ、``||hoc22.キングを移動させる||``ブロックと``||hoc22.クイーンを移動させる||``ブロックを使い正しい位置に動かしてください。

```ghost
    hoc22.kingMove(Custom.ArrowUpOrange, 1)
    hoc22.queenMove(Custom.ArrowUpOrange, 1)

```
```template
    hoc22.kingMove(Custom.ArrowUpOrange, 3)
    hoc22.kingMove(Custom.ArrowLeftBlue, 1)
    hoc22.queenMove(Custom.ArrowRightYellow, 2)
    hoc22.queenMove(Custom.ArrowUpOrange,1)          
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```