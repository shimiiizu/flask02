# XBRL WEB
様々なアプリケーションからなる
bootstrapを使って装飾する
まずは小さい形でも使える形にする。
拡張性はまだ、考慮しなくて良い
gitを使ってこまめに履歴を保存する


①経済指標表示
今のところ、cpiのみ表示している。
selectorで、経済指標を選べるようにする。
何故か分からないがインフレ率を選択した際にはうまく動作するものの、
その他の指標を指定した場合には動作しない。
原因は不明。

①株価表示
yahoo finance APIを使って株価を取得
plotly.jsを使って株価をグラフ化する。
フォームを使って株価コードを指定する

③理論株価計算
株式を永久債として計算。
利益をクーポンとして計算する。

④業績表示
業績と株価を比較する


⑤2軸プロット
PERとPBRを表示する。
どの企業がグループからはみ出しているのが分かる。