# hayabusa-bon

## はじめに
隼本のstan部分のpystanによる実装

- ローカルレベルモデルの推定
- 応用:複雑な観察方程式を持つモデル

の2つの章のRとstan部分をpythonで実装しました。

google colabを用いて実装しています。
google colabではimport pystanとするだけでstanが使用できるため非常に簡単です。


## 使用時の注意
データを入れたフォルダに従って下記のフォルダを変更してください。
下記の場合はmy driveの下にdataフォルダをつくりそこにデータを入れた場合です。

TEMPLATE_DIR = "/content/drive/My Drive/"
DATA_DIR = TEMPLATE_DIR + "data/" #dataを入れたフォルダを記載

## 参考サイト
- 隼本サポートページ:https://logics-of-blue.com/tsa-ssm-book-support/
- Rとstanのコードとデータ:https://github.com/logics-of-blue/book-tsa-ssm-foundation
