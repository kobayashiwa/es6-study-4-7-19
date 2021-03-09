# es6-study-4-7-19
JavaScript 学習コース IV > クラスの基本 > メソッド（1）

## メソッドとは
メソッドとはそのインスタンスの「動作」のようなもの。
「名前」や「年齢」などの情報はプロパティで追加したのに対して、メソッドは「挨拶をする」「値を計算する」などの処理のまとまりを表す。

#### メソッドの定義
メソッドはクラスの中で定義する。
「メソッド名() { }」として、中括弧「{ }」の中にそのメソッドで行いたい処理を記述する。

#### メソッドの使い方
メソッドは、そのクラスから生成したインスタンスに対して呼び出す。
使い方は「インスタンス.メソッド名()」とすることでそのメソッドを呼び出し、処理を実行することができる。

## コーディングトレーニング
「鈴乃屋オリジナルコレクション 衣のいのち」のレイアウト構造をレスポンシブで写経する。

#### サイト構造
header > nav　【スクロールで出現】
main > section（first） > logo - section（about） - section（item #botankarakusa） - section（item #kamon） - section（item #namikasane） - section（item #kochoranbu） - section（others） - section（profile）
footer

#### ブレイクポイント
- desktop（1042px ↑）
- tablet（1040px ↓）
- smartDevice（767px ↓）

## チャレンジ
ヘッダーをsection（first）の高さ分、スクロールしたら出現するようにする
