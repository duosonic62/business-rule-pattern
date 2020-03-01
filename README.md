# 概要
DDDにおけるDomainをビジネスルールに焦点を当てた場合における、抽象データ型のパターンまとめ。

CCSRによる開発を想定。

# CCSR概要
RDRA2.0による要件定義<br>
　↑   ↓<br>
Kotlinによる仕様化<br>
　↑   ↓<br>
Kotlinによる実装

# パターン集

## パターン1
### ・バリエーション
このバリエーションを利用して、下記のパターンを表現する

## パターン2
### ・表形式A

| |メソッド名A|メソッド名B|
|---|---|---|
|enum値A|値1|値2|
|enum値B|値3|値4|

### ・表形式B 

| |enum値A|enum値B|
|---|---|---|
|enum値C|値1|値2|
|enum値D|値3|値4|

## パターン3
### ・状態モデルA

| |イベントA|イベントB|
|---|---|---|
|状態A|値1|値2|
|状態B|値3|値4|

### ・状態モデルB

| |イベントA|イベントB|
|---|---|---|
|状態A|値1|値2|
|状態B|値3|値4|

## パターン4
### ・計算

## パターン5
### ・集合
### ・列
### ・写像


