# othello
KDEのB3，Kチームのオセロプログラム
## game.py
ユーザとボードを使ったゲームの流れが書かれている．
ユーザに入力させたりボードに石置いたり．
## board.py
石を置くボードを表すクラス．石置いたりひっくり返したり
する．
## user.py
ユーザを表すクラス．石置く場所を決めたりなど．
## othello.py
board.BoardをGUIで利用できるようにするクラス．
## 未実装部分
*Undo処理．ボードや入力座標の履歴が残っているのでそれを用いて実装する予定．
GUI部分．Tkinterを用いています．
AIの実装．Userクラスのcpu__inputに書く予定
