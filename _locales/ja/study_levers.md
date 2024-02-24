### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# 色がついたレバー

## ステップ 1
ドアを開けるには、素早く正しい順番で4つすべてのレバーを引く必要がある。素早い騎士がレバーを引いてくれるようにしてください。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
``||hoc22.レバーを引く||``ブロックを使い素早い騎士を選ばれた色に移動しせレバーを引かせます。カーペットが何枚あるか確認してください。それが順番のヒントです。

```ghost
    hoc22.teleportLightBlueLever()
    hoc22.teleportMagentaLever()
    hoc22.teleportYellowLever()
    hoc22.teleportOrangeLever()
```
```template
    hoc22.teleportLightBlueLever()
    hoc22.teleportOrangeLever()
    hoc22.teleportYellowLever()
    hoc22.teleportMagentaLever()
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```