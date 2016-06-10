# unix.2016
本リポジトリは「UNIX」の授業にて、補足情報等の共有に使用します

## 評価方法

- 課題 58%
- 期末テスト 42%

## 関連リンク

- <a href="http://www.lpi.or.jp/" target="_blank">LPIC</a>
- <a href="http://www.backlog.jp/git-guide/" target="_blank">サルでもわかるGit入門</a>
- <a href="http://isoredirect.centos.org/centos/7/isos/x86_64/CentOS-7-x86_64-DVD-1511.iso" target="_blank">CentOSダウンロード</a>
- <a href="https://git-scm.com/book/en/v2" target="_blank">Pro Git</a>
- <a href="https://www.git-tower.com/blog/git-cheat-sheet/" target="_blank">GIT CHEAT SHEET</a>
- <a href="http://qiita.com/sutetotanuki/items/1700343852e863ba63a0" target="_blank">gitコマンドチートシート</a>

## manコマンドのマニュアルの日本語化

- sudo apt install manpages-ja

## vim

### vimの設定

1. vimのインストール

	- sudo apt install vim vim-runtime

1. 設定ファイルの編集(以下のリポジトリを参照)

	- https://github.com/KimiyukiYamauchi/vim_setting

### チュータの起動

- vimtutor
- LANG=c vimtutor


### リンク

- <a href="http://archiva.jp/web/tool/vim_basic.html" target="_blank">Vim 基本操作まとめ</a>

- <a href="http://www.labnol.org/internet/learning-vim-for-beginners/28820/" target="_blank">Learning Vim for Beginners</a>

## ネットワークの設定

### リンク

- <a href="http://linux-suomi.net/modules/sinyD0/index.php?id=23" target="_blank">インターフェースの設定</a>

- <a href="http://sicklylife.at-ninja.jp/memo/ubuntu1404/gufw.html" target="_blank">ファイアウォール</a>

## VirtualBoxのインストール

1. システムのアップデート  
$ sudo apt update
1. システムのアップグレード  
$ sudo apt upgrade
1. VirtualBoxのインストール  
$ sudo apt install virtualbox

## GNU Awkのインストール

- sudo apt install gawk

## GitHubに公開鍵暗号方式で認証を行う方法

- サーバ側
	- <a href="http://monsat.hatenablog.com/entry/generating-ssh-keys-for-github" target="_blank">SSHの公開鍵を作成しGithubに登録する手順</a>


- クライアント側

	- <a href="http://qiita.com/n_slender/items/30db800aad7eb193c07e" target="_blank">httpプロキシサーバがわかればGitHubは使える</a>
	- <a href="http://takuya-1st.hatenablog.jp/entry/20110813/1313223707" target="_blank">HTTPプロキシ経由でのSSH（その２） connect を使う</a>