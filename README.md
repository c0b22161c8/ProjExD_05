# こうかとんを撃ち落とせ
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
戦闘機を左右に動かし、こうかとんを撃ち落とすゲーム。スコアが一定以上になるとボスが出現する。

## ゲームの実装
###共通基本機能
* 背景画像の描画
### 担当追加機能
* ボスとその周りの小ボスの攻撃を変える。（渡辺）
* ボスの攻撃を無敵にする。（渡辺）
### ToDo
- [ ] 次回マージした際に必要な部分を書き足す

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
