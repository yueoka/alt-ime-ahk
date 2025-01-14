# alt-ime-ahk

## 概要

左右 Alt キーの空打ちで IME を OFF/ON する AutoHotKey スクリプトをAlt → Controlに変更したものです。
Windows（USキーボード）のキーバインドをMac（USキーボード）と同じにしようとすると、スペースの左右にあるAltキーをControlにまず変える。そのあと、そのスペース左右にあるControlキーを単発クリックで英数/かな変換となるようにするために本リポジトリを使う。
Windowsを開く度に実行しなければならないかもなので、何かしら自動で立ち上がるようにしといた方が良いと思います。

* 左 Control キーの空打ちで IME を「英数」に切り替え
* 右 Control キーの空打ちで IME を「かな」に切り替え
* Control キーを押している間に他のキーを打つと通常の Control キーとして動作

## 動作環境

* Windows10

## 使い方

上記Githubリポジトリからファイルをダウンロードし、alt-ime-ahk.ahk を好きな場所に置き、ダブルクリックで起動してください。 タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは alt-ime-ahk.ahk を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

IntelliJ IDEA など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Alt キーを離した際に alt-ime-ahk.exe がエラー終了します。

## ブログの紹介ページ

[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off/)

