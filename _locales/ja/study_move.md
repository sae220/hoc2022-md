### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# 移動させる

## ステップ 1
粘土玉を金ブロックに移動させてください。ヒントが欲しい場合は、電球ボタンを押してください。まずデフォルトのコードを実行し、何が起こるかを確認し、その後、問題を解くために正しく直してください。これをデバッグと呼びます。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint  
``||hoc22.粘土玉を移動させる||``ブロックを使い粘土玉を金ブロックの上まで移動させてください。金ブロックに着くためにどの方向に何ブロック移動すればいいかを直してください。

```ghost
    hoc22.clayBallMove(FourDirectionUpDown.Up, 5)
```
```template
    hoc22.clayBallMove(FourDirectionUpDown.Up, 3)
    hoc22.clayBallMove(FourDirectionUpDown.Left, 2)
    hoc22.clayBallMove(FourDirectionUpDown.Down 3)
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```