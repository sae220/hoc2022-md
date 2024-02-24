### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# キャノン

## ステップ 1
それぞれのキャノンには対応するビームの色がある。時のオーブを囲むリングの色と同じ順番でキャノンを発射させてください。

今書かれているコードは壊れています。直してみてください。一度実行してみてどう動くのか確認し、その後正しく直して(デバッグして)ください。

#### ~ tutorialhint 
時のオーブの周りのリングの色をみてください。``||hoc22.キャノンを発射する||``ブロックを使い時のオーブの周りのリングの順番と合わせてください。一番外側のリングから始めてだんだん内側のリングに発射しましょう。

```ghost
    hoc22.magentaCannon()
    hoc22.lightBlueCannon()
    hoc22.limeCannon()
    hoc22.yellowCannon()
```
```template       
    hoc22.yellowCannon()
    hoc22.lightBlueCannon()
    hoc22.magentaCannon()
    hoc22.limeCannon()
    
```

```package
minecraft-hoc22=github:sae220/hoc22-ts
```