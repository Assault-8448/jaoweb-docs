---
title: Forgeの導入解説【2021年版】
description: 様々なModの前提Modとなっている「Forge」の導入方法を解説します。
category: modification
image: https://storage.jaoafa.com/f54f2539629b70b8f3d78cc694236081.png
author: EKipa
createdAt: 2021-1-1
updatedAt: 2021-1-3
---

この記事では、様々なModの前提Modとなる「**Forge**」の導入方法などを解説します。

## 目次

<!--contents-->

## 解説環境

以下の環境で解説します。他の環境・バージョンの場合は違う点もあるかもしれませんので、適量読み替えてください。

- Windows 10
- Minecraft Version 1.12.2
- Minecraft Forge 1.12.2 14.23.3.2655
- Java 1.8.0_171

## 導入方法

### 1. Forgeをダウンロードしましょう

![Forgeの公式サイト](https://storage.jaoafa.com/e9be87582a12b68052fcaf59fa880076.png)

[Forgeの公式サイト](http://files.minecraftforge.net)にアクセスしましょう。  
左側の「**Minecraft Version**」リストから自分がダウンロードしたいバージョンを選び(ここでは1.12.2)クリックしましょう。(①)  
その後、ページが変わったら「**Download Recommended**」内(②)の「**Windows Installer**」をクリックしましょう。(③)

adfoc.usの広告が表示されますが、広告をクリックせず、5秒程度待ち右上に「**SKIP**」とボタンが出てきたらそれをクリックし、ダウンロードしましょう。  
これでForgeのインストーラのダウンロードが完了しました。

### 2. Forgeのインストール

![Forgeのインストーラ](https://storage.jaoafa.com/241a9ce6071568e1d9fb6ee1f6694c27.png)

ダウンロードしてきたForgeのインストーラを、**ダブルクリックして直接実行**しましょう。
うまく開いたら、「**Install client**」を選択していることを確認し「**OK**」をクリックしましょう。

「**Successfully installed client profile forge for version forge...**」と出たら完了です。  
エラー等が発生した場合はそのエラーをよく読み、調べたりして解決してみてください。

### 3. プロファイルの変更

![プロファイルの変更](https://storage.jaoafa.com/c923ffc39256a47662c0bc9d6cd7db02.PNG)

ランチャーを開き、「**起動構成**」をクリック(①)、新規に作成された「**Forge**」というプロファイルをクリックしてください。(②)

プロファイルを開くと、設定画面が出てくるので以下のように変更しましょう。(あくまで**例です**。必要に応じて解像度の設定、Javaのパス指定、JVMの引数設定等を行ってください。)

![起動構成の編集](https://storage.jaoafa.com/43fa5faefd8d880d1c7fa70386c4723d.PNG)

- <span style="color: red;">**アイコン**</span>(①)
 名前、バージョンの隣にあるアイコンを変更します。既に準備されている76種類のMinecraftのブロックアイコンの他に、自分でアイコンをアップロードすることもできます。(128x128ピクセルのPNGファイルのみ)

- <span style="color: blue;">**名前**</span>(②)  
  起動するプロファイルを見分けるために**一番重要**になる「名前」です。必ず変更することをお勧めします。

  自分が分かればなんでも構いませんが、私は「[TYPE] [VERSION]」の形式で入力するようにしています。例として画像の場合だと、1.12.2のバージョンでForgeというものなので「Forge 1.12.2」などとしています。

- <span style="color: orange;">**ゲームディレクトリ**</span>(③)  
  人によってはゲームディレクトリをバージョンによって分割しない方もいるようですが、Modなどを導入する場合は必ずゲームディレクトリをプロファイルによって変更した方が良いと思います。

  私の場合は既定で作成される「.minecraft」に「GameDirectory」というフォルダを作成し、その中に「VERSION_TYPE」の形式でフォルダを作成しています。不具合の原因となるので、ファイル名に日本語を使うのは推奨しません。例として画像の場合だと、1.12.2のバージョンでForgeというものなので「1.12.2_forge」などとしています。(**ここでなければならない、という規定はありません。**あなたの置きたいところにファイルを作成しましょう。)

一通り設定をしたら、「**保存**」を押してプロファイルを保存しましょう。

### 4. 実際に起動をしてみましょう

![Forgeを選択してMinecraftを起動](https://storage.jaoafa.com/687817ad7c5e989cd1177daef431373f.PNG)

プレイボタンの左側の**v**をクリックし、先ほど作成したプロファイルを選択しましょう。
選択したら、「**プレイ**」を押しゲームを起動します。

正常に起動すれば導入は完了です。

## 免責等

- ブログ記事作成者及び当サービス「jao Minecraft Server」では、この記事に記載された内容を行ったことによる問題への**一切の責任を負いません。** 何かを試したり、やってみたりするときには必ず「**自己責任**」を念頭に。
- また、多くの記事は時間を追うことに情報が古くなります。仕様が変わっていたり、そもそも無くなっている可能性もありえるということを覚えておいてほしいです。
- 「どうしたらいいのだろう？」などと疑問が発生した場合は[Discord](community/discord)の`#question`チャンネルにて質問してみましょう。