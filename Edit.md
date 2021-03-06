# IntelliJ IDEA Editor Tutorial Ja - Edit -

## はじめに

* これは JetBrains 社の IntelliJ IDEA のエディタ部分のチュートリアルです。
* vim tutor にインスパイアされて作りました。
* 基本的に上から順番に試してみることでエディタ上の基本操作と、Edit メニューの基本操作が網羅できるようになっています。
* キーボードショートカットのリファレンスとしても使えます。
* Windows版表記になっています。Mac版は適宜読み替えてください（大抵の場合 Ctrl = Cmd。特殊キーはFnで代替）。

## Edit

* 移動：ファイル末尾へ Ctrl + End

> Mac) Cmd + Fn + 右矢印

* 移動：行番号へ Ctrl + G
* 移動：行末へ End
* 移動：行頭へ Home

> Mac) Fn + 矢印

* 移動：１ページ進む PageDown
* 移動：１ページ戻る PageUp

* 移動：単語区切りで移動 Ctrl + ←(→)

> 日本語は文節しか区切れないけど、英語だとうまく動くみたい。（、や。で止まる）
> For English, blank,'," or ,.


* 移動：カーソル位置がウィンドウの中央に来るようにスクロール Ctrl + M
* 移動：カーソルを現在のページの先頭の行に移動 Ctrl + PageUp
* 移動：カーソルを現在のページの最後の行に移動 Ctrl + PageDown


* 選択：ファイル内全選択 Ctrl + A
* 選択：選択解除 Esc
* 選択：選択 Shift + 矢印
* 選択：単語選択 (キャレット (範囲) を拡大縮小) Ctrl + W / Ctrl + Shift + W

> "範囲"にカーソルを置いて Ctrl + W を数回テスト

* 選択：カーソル位置から行末尾 Shift + End
* 選択：カーソル位置から行先頭 Shift + Home
* 選択：カーソル位置からファイル先頭 Ctrl + Shift + Home
* 選択：カーソル位置からファイル末尾 Ctrl + Shift + End

* 編集：（選択状態で）コピー Ctrl + C
* 編集：（選択していない状態で）行コピーして選択 Ctrl + C

* 編集：貼り付け Ctrl + V

* 編集：元に戻す（Undo） Ctrl + Z
* 編集：元に戻すを戻す（Redo） Ctrl + Shift + Z

* 編集：行コピーして貼り付け Ctrl + D
* 編集：行削除 Ctrl + Y

* 編集：行連結（カーソル行に下の行を連結） Ctrl + Shift + J
    連結される行

> Mac) control + Shift + J

* 編集：（選択状態で）削除（Cut） Ctrl + X
* 編集：（選択していない状態で）行削除 Ctrl + X

* 編集：カーソル位置から単語の終わりまでを削除 Ctrl + Delete
* 編集：カーソル位置から単語の始まりまでを削除 Ctrl + Backspace


* 選択：矩形選択その１ Alt + マウスでドラッグ

> 下の３行を Alt + マウスドラッグで矩形選択（そして Ctrl + C でコピーする）

    JAVA
    PHP
    Ruby

* 編集：矩形貼り付けその１ Alt + マウスで貼り付け位置を選択して Ctrl + V

> 下の[]の間に貼り付けてみるにはマウスで[]の間をクリックして Alt キーを押しながらドラッグしてから Ctrl + V

    私は[]使いです
    私は[]使いです
    私は[]使いです

* 選択：矩形選択その２（矩形選択モード） Alt + Shift + Insert

> Alt + Shift + Insert してから下の３行を Shift + 矢印で矩形選択（そして Ctrl + C でコピーする）

    HTML
    CSS
    JavaScript

* 編集：矩形貼り付けその２（矩形選択モードの場合）

> 下の[]の間に貼り付けてみるには[]の間を Shift + 矢印で矩形選択してから Ctrl + V

    私は[]使いです
    私は[]使いです
    私は[]使いです

> ヒント： Esc で選択解除。もう一度 Alt + Shift + Insert で矩形選択モード解除

* 編集：ブロックを連結（ Edit メニューから Fill Paragraph ）

> カーソル行と連続した行（空白行のない塊）をまとめて連結する

    I'm
    IntellJ
    User!

* 編集：インデント（行頭で） Tab
* 編集：インデント解除（行頭に限らず） Shift + Tab

* 編集：（アルファベットの）大文字小文字切り替え Ctrl + Shift + U

> 選択して切り替え

    i am IntelliJ user.

* 検索：文字列の検索 Ctrl + F
* 検索：文字列の置換 Ctrl + R

* 編集：カーソル行の上に空行挿入 Ctrl + Alt + Return
* 編集：カーソル行の下に空行挿入 Shift + Return


## わかってないこととか（やり方があったら教えてください！）

> わからないこととか教えて欲しいことをここに書いておく。
> やり方がわかったら転記して削除する


## 免責その他

* 自己責任でご利用ください。
* 勉強用に作ったものです。誤字脱字間違い追加要望等は Pull Request でご指摘ください。
* 厳密には実際の機能と違う、または状況に応じて異なる意味、異なる名前を持つものもありますが、エディタ作業中ではだいたいこんな感じの操作である、くらいで使ってください。
* 著作権は放棄です。好きに使ってください。


* 移動：ファイル先頭へ Ctrl + Home

> Mac) Cmd + Fn + 左矢印
