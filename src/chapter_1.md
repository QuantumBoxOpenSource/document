# 第1章

## 第1章の目標（学びたいこと）
- Next.js (React)
- Git
- GitHub

## Overview
いわゆるポートフォリオサイト、ブログと言われるような自分の今後の制作物を紹介したり、記事を投稿できるようなWebサイト。
つまりCMS(Contents Management System)を作ることが目標。

### 使用するツール紹介
#### Next.js
[公式サイト](https://nextjs.org/)
ReactをよりWebサイト用に特化させたフレームワーク

#### Git
ソフトウェアのバージョン管理ツール  
個人で開発するときには進捗をこまめに保存できるツールという理解で問題なし。  
複数人で開発するときに真価を発揮する。  
この章では使用する機能を絞ってgitに慣れるところから始めるが、章を重ねるごとにより多くの機能に触れていき、最終的には実際に業務で開発しているような状況に近づける。  

#### GitHub
ソフトウェア開発のプラットフォーム  
開発しているソフトウェアのソースコードを管理しやすくしてくれる。  
複数人で開発しているときにはGitを使用して進めた進捗をアップロードして共有ができる。  
実際この章で必要なツールではないが、Gitとの組み合わせで徐々に慣れるために少しずつ使用していく。  

## Process
### Next.jsを始める
[Nextjsのチュートリアル](https://nextjs.org/learn/basics/create-nextjs-app)に従ってNextjsの仕組みや扱い方を学ぶ。  

Node.jsがバージョン10.13以降のものがインストールされていればそれ以外に必要なものはありません。  
実際に叩くコマンドは`npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/learn-starter"`です。  
このコマンドを打つとサンプルとして用意されているnextjsのプロジェクトを簡単に立ち上げることが可能です。  

これを分解して解説します。  
まずは`npx create-next-app`
npxは引数として与えられたコマンドを以下の順番で探して実行します  
1. ローカルパッケージ（node_modules/.bin）
2. 環境変数PATH
3. npmレジストリ
つまり今回は引数として与えられた`create-next-app`を探して実行するわけなので、create-next-appがあなたのパソコンにインストールされていなくても[npmのレジストリ](https://www.npmjs.com/package/create-next-app)にあるので実行してくれます。  

つまり実質的に実行されるコマンドは`create-next-app`ということになります。
[create-next-appの詳しい説明](https://nextjs.org/docs/api-reference/create-next-app)を読むと、先程実行したコマンドではいくつかのオプションを与えていることがわかります。


## 第1章のまとめ

## 参考リンク
