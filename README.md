# unix.2016
本リポジトリは「UNIX」の授業にて、補足情報等の共有に使用します

## 学習環境の設定

### VirtualBoxのインストール
1. システムのアップデート  
$ sudo apt update
1. システムのアップグレード  
$ sudo apt upgrade
1. VirtualBoxのインストール  
$ sudo apt install virtualbox

### Debian入手&インストール
1. <a href="https://www.debian.org/" target="_blank">ここから入手</a>
1. VirtualBoxに仮想環境を作成
1. 作成した仮想環境にDebianをインストール

### ネットワークの設定
#### ホスト側
1. [設定]-[ネットワーク]-[高度]-[ポートフォワーディング]  
以下の追加  
ホストポート 2222 ゲストポート 22  
ホストポート 8080 ゲストポート 80  
1. [設定]-[ネットワーク]  
「アダプター２」に「ホストオンリーアダプタ」を設定
#### ゲスト側
1. 「アダプタ－２」の設定を追加
	1. rootに移行する  
	$ su -
	1. 設定ファイルの編集  
	\# vi /etc/network/interfaces  
	::: ここから追加 :::  
	auto eth1  
	iface eth1 inet static  
	address 192.168.33.10  
	netmask 255.255.255.0  
	::: ここまで追加 :::
1. ネットワークの再起動  
\# service networking restart
#### 仮想環境(Debian)への接続方法
- $ ssh -p 2222 ユーザ名@localhost
- $ ssh ユーザ名@192.168.56.10

### システムの更新
1. $ su -
1. \# apt upgrade
1. \# apt update

### sudoコマンドを使えるようにする
1. sudoコマンドをインストール&設定  
\# apt install sudo  
\# vi /etc/group  
「sudo:」にログインユーザを追加
1. 一旦exitし、sshで接続し直す

### 公開鍵暗号方式でssh接続できるようにする
#### ホスト側
1. 公開鍵の鍵のペア（秘密鍵、公開鍵）を作成  
$ ssh-keygen
1. 公開鍵のパーミッションの変更  
$ chmod 600 .ssh/id_rsa.pub
1. 公開鍵をゲストの~/.ssh下にautorized_keysでコピー  
$ scp .ssh/id_rsa.pub ユーザ名@192.168.56.10:~/.ssh/authorized\_keys
1. 以下で接続してパスワードを聞かないで接続できればOK  
$ ssh ユーザ名@192.168.56.10