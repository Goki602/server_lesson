- ディレクトリ内に存在するディレクトリやファイルを一覧表示する
	- $ ls -オプション パス
	- -a (	不可視ファイルも表示)
	- -l (タイプや権限、所有者や所有グループなどの詳細情報を表示)

- ワーキングディレクトリ がどこであるか出力
	- $ pwd

- ワーキングディレクトリを指定したディレクトリに変更する
	- $ cd パス
 	- $ cd ~ (ホームディレクトリ)
 	- $ cd / (ルートディレクトリ
 	- $ cd - (移動前に位置していたディレクトリ)
 	- $ cd . (ワーキングディレクトリ)
 	- $ cd .. (ワーキングディレクトリの一階層上のディレクトリ)
 	- $ cd ../../ (ワーキングディレクトリの二階層上のディレクトリ)

- ディレクトリを作成する
	- $ mkdir ディレクトリ名

- ファイルを作成する
	- $ touch ファイル名

- && 演算子 (左辺の実行が成功すれば、右辺を実行する)
	- 例　$ cd /home/test1 && ls

- ファイルあるいはディレクトリのコピーを行う
	- $ cp コピー元 コピー先

- ファイルやディレクトリの移動を行う
	- $ mv 変更元 変更先

- ファイルやディレクトリの削除を行う
	- $ rm 削除するファイルorディレクトリ

- 削除実行の際に警告メッセージを非表示
	- $ rm -rf /

- ワイルドカード
	- '*' (* 以外の部分がマッチするファイルやディレクトリ全てを対象として操作できる)
	- ? (指定した箇所の1文字のみの置き換えになる)

- 指定したファイルの内容をターミナル上に出力するコマンド
	- cat (CATnate)

- 左辺の実行結果の出力を右辺で指定したファイルに書き込む
	- '>'

- 左辺の実行出力結果を右辺で指定したファイルの末尾に書き込む
	- '>>'

- ターミナル上で即時起動できるエディタ
	- $vi

- viの操作
	- $i (インサートモードに切り替え)
	- $escキー (ノーマルモードに切り替え)

- vi ノーマルモード時操作
	- $j (下に移動)
	- $k (上に移動)
	- $h (左に移動)
	- $l (右に移動)
	- $:w (保存)
	- $:wq (保存して終了)
	- $:q! (保存せずに強制終了)
 	- $u (変更内容を１つ元に戻す)
	- $Ctrl + r (変更内容を１つ前に進める)
 

