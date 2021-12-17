# robosys_Kadai1
This is a repository for robosys Kadai1.

# 編集途中です

# License
GPL-2.0 License

# Author
Ryuichi Ueda

# Writer
Ryunosuke Sato  

（下記の参考ビデオの『ロボットシステム学第7回～第8回』をみながら、私が同じコードを記入しただけなので、コードの著作権は著者にあります。ただし、コード最上部3行のコメントアウトしている部分は、『ロボットシステム学第9回（ソフトウェアライセンスとクリエイティブ・コモンズ）』（49分15秒あたり）と『ロボットシステム学第3回（GitとGitHub）』（57分26秒あたり）を参考にして、私が著者のコードに追記したものです）

# Explanation
このリポジトリに掲載してあるデバイスドライバはLEDを点灯・消灯するものです。ディレクトリごと掲載しました。  
ラズベリーパイ4のGPIO25とGNDの間にLEDと抵抗を接続して使います。  
ローカルのリポジトリで、myledのディレクトリに入った後、以下の順にコマンドを入力してください。  

## 入力するコマンド
make  
sudo insmod myled.ko  
sudo chmod 666 /dev/myled0

その後、LEDを点灯させるためには  
echo 1 > /dev/myled0　と入力し、  
LEDを消灯させるためには  
echo 0 > /dev/myled0　と入力してください。

# Reference video (YouTube)
## 講義動画のためURLは掲載しない
Git, GitHubについて  
・ロボットシステム学第3回補足（GitHubへの鍵の登録）  
・ロボットシステム学第3回（GitとGitHub）

コードについて  
・ロボットシステム学第7回～第8回  
・ロボットシステム学第9回（ソフトウェアライセンスとクリエイティブ・コモンズ）

# Reference
GitHubの扱い方について  
・[ファイルの名前を変更する - GitHub Docs](https://docs.github.com/ja/repositories/working-with-files/managing-files/renaming-a-file)  
・[GitHub — READMEの作成方法と書き方【改行やリンク・画像の入れ方】| Howpon[ハウポン]](https://howpon.com/8334)  
・READMEをどのように書けば良いかの参考として、コードの著者のREADMEもいくつか拝見し、このREADMEを書きました。
