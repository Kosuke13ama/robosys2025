# robosys2025

[![test](https://github.com/Kosuke13ama/robosys2025/actions/workflows/test.yml/badge.svg)](https://github.com/Kosuke13ama/robosys2025/actions/workflows/test.yml)

## プログラムについて
標準入力から読み込んだ文章（文字列）に含まれるアラビア数字を、日本語の漢数字に変換して出力するプログラムである。

## クローン方法

このリポジトリを下記のようにクローンしてください。

```
$ git clone https://github.com/Kosuke13ama/robosys2025.git
```

## 使い方
このプログラムは実行権限を与えて使用します。

```
$ chmod +x kanji
```

**実行方法の例**<br>
* 単純な数値を変換する場合<br>

```
$ echo 12345 | ./kanji 一万二千三百四十五
```

* 文章の中の数値を変換する場合<br>

```
$ echo "今年は2025年です" | ./kanji 今年は二千二十五年です
```

## 必要なソフトウェア

- Python
  - テスト済みバージョン：3.7~3.10

## テスト環境

- Ubuntu 20.04 LTS / 22.04 LTS

## ライセンス

* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* © 2025 Kosuke13ama
