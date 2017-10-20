# Functional Ruby

---

## なにやるの
Rubyに関数型の知見を導入

Arrayを使ったときに

- メンテナンスしやすい
- 短かくてシンプル

なコードにする

---

## 関数型の知見
### 副作用を持たない
副作用

- 値を書き換える
- 状態を持つ
- 入出力をする

### メリット
- 同じ引数なら同じ結果が返る
- テストしやすい

---

## 関数型の知見2
### 強力な集合操作
map, reduce, select などのシンプルかつ強力な関数

RubyのArrayのメソッドでもできる

---

## RubyのArray基本ルール
### 副作用メソッド禁止(特に!)

### メソッドチェインは程々に
時々束縛することを考える

### reduceは最後の手段
reduceは強力過ぎて読みづらくなりがち

---

## 便利なやつ一覧
- map
- reduce
- combination
- compact
- find, find_index
- flatten(n)
- include?
- permutation
- product
