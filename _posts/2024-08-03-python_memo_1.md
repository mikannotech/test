---
title: "Python 備忘録 変数"
categories:
  - プログラミング
tags:
  - Python
---

**変数とは**

- 変数は値に名前を付ける仕組み。
- 例：`a = 100` で `100` に `a` という名前がつく（変数定義）。

**代入文**

- `=` を使った構文のこと。
- 右辺の値が左辺の変数に割り当てられる。
- 例：`a = a - 10` は `a` の値を 10 減らす。

**関数の定義**

- 関数を使うと、繰り返しの計算が楽になる。
- 定義方法：

    ```python
    def 関数名(引数, ...):
        return 式
    ```

- 例：`def bmi(height, weight): return weight / (height/100.0) ** 2`

**ローカル変数**

- 関数内で定義された変数はローカル変数。
- 関数外では同じ名前でも別の変数として扱われる。

**`print` と `return` の違い**

- `print` は関数の実行中に値を表示するためのもの。
- `return` は関数の結果を返すためのもの。

**コメントと空行**

- コメントは `#` を使って追加し、コードの理解を助ける。
- 空行はコードを見やすく整理するために使う。