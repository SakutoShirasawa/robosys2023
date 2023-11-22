# robosys2023  
このリポジトリは２０２３年にロボットシステム学で使用したものです。  
## ダウンロード方法
次のコマンドを実行する
```
git clone git@github.com:SakutoShirasawa/robosys2023.git
```
## plusコマンド  
![test](https://github.com/SakutoShirasawa/robosys2023/actions/workflows/test.yml/badge.svg)

標準入力から読み込んだ数値を足し合わせる。  
* 実行方法  
```
seq n | ./plus
```
nは任意の数値を入力  

もしくは  
```
seq n > nums
```
```
./plus < nums
```
## 必要なソフトウェア  
* python
  * テスト済み: 3.7～3.10

## テスト環境  
* Ubuntu22.04.2LTS
---
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* © 2023 SakutoShirasawa
