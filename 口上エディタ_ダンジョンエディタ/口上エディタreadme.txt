
****************************************
口上エディタ未完成仮置き版readme
****************************************


・概要
	erablue_resort用の口上エディタです。
	といっても中身はERBを覗いて特定の文字列で切り分けてるだけなので、テンプレートを整備すれば他のバリアントでも使用出来ます。
	入力支援とかはないですが、項目ごとに切り分けるだけでもだいぶ入力しやすくなるかなと。

・使い方
	起動した後、「ERB読込」で任意の口上ファイルを開く。
	（この時、テンプレを読み込むとキャラNoで置換するダイアログが開くので、必要なら入力して置換する）

	左側のリストから変更したい部分を選び、中央のテキストボックスで口上を記述する。
	右側はメモのため自由に書き換えOK。

	記述が終わったら「ERB保存」あるいはCtrl+Sで保存する。
	おしまい。

・ERB内部の切り分け方
	「;--------------------------------------------------」でタイトルと編集部分を区切っています
	また、一番最初の「;--------------------------------------------------」より前は右部分に表示されます
	つまり、以下のような区切りとなります

;--------------------------------------------------
;（左側に表示するタイトル名）
;--------------------------------------------------
（中央部で編集出来る内容をここにずらっと）
～
～
～
～
～

	※※現状の口上テンプレートはこの区切りに対応していますが、既存の口上は対応していません※※
	※※使用する場合はこの区切りを必要な場所に入れてください※※

・ライセンス
	改造でも再配布でも好きにしてOKです。



