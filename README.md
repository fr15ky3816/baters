# アグリバーター（仮）
  余剰・廃棄野菜を生産者、レストランさん間で取引するための<br>物々交換プラットフォーム

## ターゲットユーザ
  * 市場に流通させることができないような余剰廃棄野菜に悩む農家、生産者
  * 生産者とのつながりや廃棄ロス問題に共感する飲食店、消費者

## サイト概要
 農家さんが生産する野菜が流通されることなく、大量に廃棄されている問題を解決する手段として作成いたしました。
  *  メルカリ（　https://www.mercari.com/jp　）のようなユーザー間で自由に取引できるプラットフォーム
  * 金銭のやり取りは行わず、物々交換（レストラン側はフードチケット等）での取引
  * SDGsや食品廃棄の問題、飲食と生産者双方のメリットになる取り組み

## サイト利用の流れ
  レストラン側
  1. 出品したい商品（交換したい商品）を登録
  2. 購入したい商品に交換商品を提示してオファーを申請
  3. オファーが受諾されると購入成立
  4. 利用者間で受け渡しを行う
  <br>
  生産者側
  1. 出品したい商品を登録
  2. 商品にオファーがきて、交換商品、出品商品が確認できたら受諾
  3. 購入成立フェーズに移行し、利用者間で受け渡しを行う
  <br>
  サイト機能要約
  *  ECサイト（メルカリ）のような形式で、取引の間にオファーフェーズ（購入者が商品を交換商品を提示）を挟む。
  *  レストラン側がオファー申請をし、生産者側がオファー承諾することで注文が完了。
  *  配送に関しては、商品サイズが大きかったり、重量があるものが多いので、利用者同士でコメント内で取り決めるものとする

## 実装機能 
  * いいね機能、コメント機能、オファー機能、検索機能
  * 要検討（ジャンルの階層構造gem ‘ancestry’、タグ機能）

## サイト設計図
  * ER図（https://drive.google.com/file/d/1rzE7Faidf-b73q5Ahk5mEV5Wv9OFfxNy/view?usp=sharing）
  　![田中翔太ポートフォリオ](https://user-images.githubusercontent.com/78789105/121110596-8042e400-c848-11eb-8492-eac5f5cc2e56.jpg)
  * 画面遷移図（https://drive.google.com/file/d/1wv4DAQ76Cr2aX-Tcdc29lmVFhPlGsiiO/view?usp=sharing）
  * アプリケーション定義書（https://drive.google.com/file/d/13ReQCO37fyGJI2jBT8msQd-JYDFHPOAo/view?usp=sharing）
  * チャレンジ要素一覧（https://docs.google.com/spreadsheets/d/1Uqk7aJu_OgppnLsnrAEJe2xI1BnNlB_9QUgpyxwT21U/edit?usp=sharing）
  * テーブル定義書（https://drive.google.com/file/d/1Imqj7BhY1gPq38XG_BVY8aSZNuHeF73p/view?usp=sharing）

##  開発環境
 * 言語：HTML,CSS,JavaScript,Ruby,MySQL
 * JSライブラリ：jQuery
 * フレームワーク：Ruby on Rails
 * IDE：Cloud9
