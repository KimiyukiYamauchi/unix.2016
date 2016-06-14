## 演習

### 06/14

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160614
1. 各自のGitHubに以下のリポジトリを作成
	- exe160614
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. デフォルトゲートウェイへの接続確認の結果をgw-testファイルに保存
	1. 自PCのIPアドレスをmy_pc_addrファイルに保存
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする


### 06/09

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160609
1. 各自のGitHubに以下のリポジトリを作成
	- exe160609
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. 以下の手順でスクリプト(backup_docs.sh)を作成する
		1. backup_docs.shファイルを作成
		1. エディタで開いて、以下の処理を記述
			1. 各自のドキュメトディレクトリ以下(/home/xxx/Documents)をgzip圧縮&書庫化し、  
			backup_docs.shを実行する際に指定したファイルに保存  
			(例)$ ./backup_docs.sh test => test.tar.gz
			1. ファイル名が指定されていない場合は日付よりファイル名を作成  
			(例)$ ./backup_docs.sh => 160609.tar.gz(2016年6月9日の場合)
			1. 上記ファイルをbackupディレクトリに移動
		1. backup_docs.shが正常に動作することを確認
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする


### 06/08

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160608
1. 各自のGitHubに以下のリポジトリを作成
	- exe160608
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. 以下の手順でスクリプト(backup_docs.sh)を作成する
		1. backup_docs.shファイルを作成
		1. エディタで開いて、以下の処理を記述
			1. 各自のドキュメトディレクトリ以下(/home/xxx/Documents)をgzip圧縮&書庫化し、  
			backup_docs.shを実行する際に指定したファイルに保存  
			$ ./backup_docs.sh (ファイル名)
			1. 上記ファイルをbackupディレクトリに移動
		1. backup_docs.shが正常に動作することを確認
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする


### 06/07

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160607
1. 各自のGitHubに以下のリポジトリを作成
	- exe160607
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. 以下の手順でスクリプト(backup_docs.sh)を作成する
		1. backup_docs.shファイルを作成
		1. エディタで開いて、以下の処理を記述
			1. 各自のドキュメトディレクトリ以下(/home/xxx/Documents)をgzip圧縮&書庫化し、  
			160607-docs.tar.gzファイルに保存
			1. 160607-docs.tar.gzファイルをbackupディレクトリに移動
		1. backup_docs.shが正常に動作することを確認
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする


### 06/02

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160602
1. 各自のGitHubに以下のリポジトリを作成
	- exe160602
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. 昨日作成した「test」ユーザを削除(ホームディレクトリも削除)
	1. /homeディレクトリ下の一覧表示をhome_listファイルに保存する
	1. file1ファイルを作成
	1. file1の所有ユーザ、所有グループを変更
		1. 所有ユーザ -> penguin
		1. 所有グループ -> penguin
	1. file1のアクセス権を以下に変更
		1. 所有ユーザー -> 読み込み/書き込み可
		1. 所有グループ -> 読み込みのみ可
		1. その他 -> 読み込み/書き込みいずれも不可
	1. file1の詳細表示をfile1_listファイルに保存

1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする


### 06/01

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160601
1. 各自のGitHubに以下のリポジトリを作成
	- exe160601
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. 以下の条件でユーザを作成
		1. ユーザ名 -> test
		1. ホームディレクトリ -> 作成する
		1. シェル -> /bin/bash
	1. /etc/passwdを検索し、上記で作成したユーザ情報を  
	user_infoファイルに保存する
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする

### 05/31

1. 前回のリポジトリのvim_command.mdをエディタで開き、説明が間違っている  
ものや未記入の部分を記述
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする

### 05/26

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160526
1. 各自のGitHubに以下のリポジトリを作成
	- exe160526
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. vim_command.mdをエディタで開き、「h」と同様に他のコマンドの説明  
を追加する
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushする

### 05/25

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160525
1. 各自のGitHubに以下のリポジトリを作成
	- exe160525
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. score_motoファイルの重複データを排除して、scoreファイルに保存する
	1. scoreのトップ5をtop_fiveファイルに保存する
	1. scoreのワースト5をworst_fiveファイルに保存する
	1. scoreの半角スペース区切りを,(カンマ)区切りに変更したものを  
	score.csvファイルに保存する
	1. scoreとscore.csvを比較し、結果をsabunファイルに保存する
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushプッシュする


### 05/24

1. 以下のリポジトリをcloneする
	- https://github.com/KimiyukiYamauchi/exe160524
1. 各自のGitHubに以下のリポジトリを作成
	- exe160524
1. ローカルリポジトリに上記で作成したリモートリポジトリを追加(add)
1. 以下の操作を行う
	1. /etcディレクトリ以下の拡張子がconfのファイルの一覧をアルファベット順  
	でファイル名etc_conf_listに保存する
	1. リポジトリ内のtouch_dirsディレクトリにfile1〜file20のファイル名で  
	ファイルを作成する
	1. 上記で作成したファイルのファイル名に拡張子.txtを付加する  
	ヒント:renameコマンドを使用すると一括でファイル名を変更できます
	1. dmesgコマンドの出力の先頭１０行をdmesg_headファイルに保存する
	1. dmesgコマンドの出力の末尾１０行をdmesg_tailファイルに保存する
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushプッシュする

### 05/19

1. 以下のリポジトリをクローンする
	- https://github.com/KimiyukiYamauchi/exe160519
1. 各自のGitHubに以下のリポジトリを作成
	- exe160519
1. クローンしたリポジトリに上記で作成したリモートリポジトリを追加
1. クローンしたディレクトリに移動
1. 以下のファイル、ディレクトリ操作を行う
	1. etcディレクトリ下のファイル名の２文字目がsで、拡張子がconf  
	であるファイルをリポジトリ内のsecond_s_confディレクトリ下にコピー
	1. リポジトリ内のfiles1ディレクトリ下のfile1〜file9のファイル名を  
	それぞれfile01〜file09に変更する
	1. files1ディレクトリを同じディレクトリ階層にfiles_tディレクトリ  
	として、コピーする
	1. files2ディレクトリ下のファイルをfiles_tディレクトリ下にコピーする
	1. files_tディレクトリのディレクトリ名をfiles_t_tに変更する
1. 変更内容をadd/commitする
1. 各自のGitHUbのリモートリポジトリにpushプッシュする

### 05/18

1. 以下のリポジトリをクローンする
	- https://github.com/KimiyukiYamauchi/exe160518
1. 各自のGitHubに以下のリポジトリを作成
	- exe160518
1. クローンしたリポジトリに上記で作成したリモートリポジトリを追加
1. command.mdをエディタで開き、「grep」と同様に他のコマンドの説明  
を追加する
1. 各自のGitHUbのリモートリポジトリにプッシュする

### 05/17

1. 以下のリポジトリをクローンする
	- https://github.com/KimiyukiYamauchi/exe160517
1. 各自のGitHubに以下のリポジトリを作成
	- exe160517
1. クローンしたリポジトリに上記で作成したリモートリポジトリを追加
1. command.mdをエディタで開き、「ls」と同様に他のコマンドの説明  
を追加する
1. 各自のGitHUbのリモートリポジトリにプッシュする
>>>>>>> 160602
