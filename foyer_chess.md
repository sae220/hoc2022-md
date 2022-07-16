### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# Chess Pieces

## Step 1
We've freed the king and queen! But the door still isn't opening. They must be in the wrong positions. Move them into the correct positions so you can finally escape this place!

#### ~ tutorialhint 
The chessboard represents a grid of dates. Search the room to figure out what dates the king and queen should be on and then use the ``||hoc22.move king <direction>||`` and ``||hoc22.move queen <direction>||`` blocks to move them into their correct positions.

```ghost
    hoc22.kingMove(ChessBlockDirection.Forward)
    hoc22.queenMove(ChessBlockDirection.Forward)
    for (let index = 0; index < 4; index++) {    }

```
```template
    for (let index = 0; index < 3; index++) {
            hoc22.kingMove(ChessBlockDirection.Forward)
        }
    hoc22.kingMove(ChessBlockDirection.Left)
    for (let index = 0; index < 2; index++) {
            hoc22.queenMove(ChessBlockDirection.Right)
        }  
    hoc22.queenMove(ChessBlockDirection.Forward)          
```

```package
minecraft-hoc22=github:ReWrite-Media/hoc22-ts#v0.2.64
```