# robosys_Kadai1
This is a repository for robosys Kadai1.　ロボットシステム学　課題1のリポジトリです。


# このリポジトリにはREADMEがmasterブランチにもありますが、このmainブランチのものを参照してください

# このリポジトリは古いものです。最新のリポジトリは[こちら](https://github.com/ryunosukesato/robosys_Kadai1_2)
お詫びの内容を全て訂正し、改良を加え、提出し終えたリポジトリが上記URLのリポジトリです。必ず、最新のリポジトリを参照してください。

# お詫び
このリポジトリには誤りがあります。以下に明記します。

## READMEについて
このリポジトリ内には、AuthorとWritten byがありますが、著者はRyuichi Uedaです。

## myled.cに関して
mainブランチのものは誤りがあります。masterブランチのものが正しいものです。

# 以下は誤りがあったを含むすべてをそのまま残しています。必ず上記で示した最新のリポジトリを参照してください。

# License（ライセンス）
GPL-2.0 License

# Author（著者）
Ryuichi Ueda

# Written by（このリポジトリとコードを書いた人）
Ryunosuke Sato  

## 著者の責任とならないように、補足するために、Written by として私の名前も記載します

（下記の参考ビデオの『ロボットシステム学第7回～第8回』をみながら、著者が作成したコードと同じコードを私が記入しただけなので、コードの著作権は著者にあります。ただし、コード最上部3行のコメントアウトしている部分は、『ロボットシステム学第9回（ソフトウェアライセンスとクリエイティブ・コモンズ）』（49分15秒あたり）と『ロボットシステム学第3回（GitとGitHub）』（57分26秒あたり）を参考にして、私が著者のコードに追記したものです）

# Explanation
このリポジトリに掲載してあるデバイスドライバはLEDを点灯・消灯するものです。GitHubに動作確認を終えたmyledのディレクトリごと掲載したものから、makeで作成されるものを削除して、このリポジトリを作成しました。  

## 使用する（した）機器
・ラズベリーパイ4 (Ubuntu 20.04.3 LTS)  
・ブレッドボード  
・ジャンパケーブル（オス-メス） 2個  
・LED  
・抵抗（???Ω）  

## 回路図
・ラズパイ4のGPIO25（22番ピン）とGND（39番ピン）の間にLEDと抵抗を接続  
※LEDのアノード（足の長い方）をGPIO25に接続すること  
後ほど写真を記載します。

# Reference
## 参考ビデオ(YouTube)
講義動画のためURLは掲載しない

Git, GitHubについて  
・ロボットシステム学第3回補足（GitHubへの鍵の登録）  
・ロボットシステム学第3回（GitとGitHub）

コードについて  
・ロボットシステム学第7回～第8回  
・ロボットシステム学第9回（ソフトウェアライセンスとクリエイティブ・コモンズ）

## GitHubの扱い方について  
・[ファイルの名前を変更する - GitHub Docs](https://docs.github.com/ja/repositories/working-with-files/managing-files/renaming-a-file)  
・[GitHub — READMEの作成方法と書き方【改行やリンク・画像の入れ方】| Howpon[ハウポン]](https://howpon.com/8334)  

### READMEについて
・READMEをどのように書けば良いかの参考として、コードの著者[Ryuichi Ueda](https://github.com/ryuichiueda)のREADMEをいくつか拝見し、このREADMEを書きました  
・READMEに何を書いたのかを話した友人のリポジトリは こちら（←後ほどURLを貼ります）になります

## 必要となる道具とその扱い方について
・[【ラズパイ電子工作】LEDを点灯させる方法(GPIO使用)| 電気設計人.com](https://denkisekkeijin.com/raspberrypi/pi-led/)  
・[Raspberry PiでLEDの点灯 - Quita](https://qiita.com/aryoa/items/3f6d82b8c63761cef087)  
・[ブレッドボードの使い方 | Spiceman](https://spiceman.jp/bread-board/)  
