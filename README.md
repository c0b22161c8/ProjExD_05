# こうかとんを撃ち落とせ！
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
戦闘機を左右に動かし、こうかとんを撃ち落とすゲーム。スコアが一定以上になるとボスが出現する。

## ゲームの実装
###共通基本機能
* 背景画像の描画
* 戦闘機の描画
### 担当追加機能
* ボスの作成(担当：吉元)：ボスに関するクラス
* サブボスの作成(担当：吉元)：ボスの回りを飛ぶサブボスに関するクラス
* ボスのHPの作成(担当：吉元)：ボスのHPに関するクラス
* 画像の変更、反転（担当：篠原）：UFOの画像をこうかとんに変更し反転させる。
* やられた際の表示：敵にやられたときにスコアを大きく表示できるようにした。
* チャージビーム(黄川田): ESCAPEを押すとチャージされる。10回以上だとchargeビーム20回以上だとsuperビームになる。大きさも変えていて、貫通するようになっている。チャージビームの状態がわからないため表示させる機能も追加.
### ToDo
* ゲームオーバーの表示
* チャージビーム
* ボスとその周りの小ボスの攻撃を変える。（渡辺）
* ボスの攻撃を無敵にする。（渡辺）
### メモ
* 戦闘機の移動は矢印キー
* ビームを撃つのはスペースキー
* 攻撃は無敵のやつと小さくて速いやつを実装する
* 攻撃は実際のボスがいないと実装できないため、実際にマージして細かいところを修正する。
* (黄川田)ボス戦のビームの攻撃力を付ける. ビームの状態によっても攻撃力が違うようにする.
