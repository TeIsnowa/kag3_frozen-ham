# 冷凍鱧入りKAG3 for 吉里吉里SDL2
**オリジナルの** ***鱧入りKAG3 for 吉里吉里SDL2*** **の説明は** ***この下にあります。*** **スクロールしてご覧下さい。**

本プロジェクトは、鱧入りKAG3 for 吉里吉里SDL2からフォークしたプロジェクトです。  
冷凍鱧入りKAG3 for 吉里吉里SDL2は、一部ワイドスクリーン非対応リソースを対応させた 鱧入りKAG3 for 吉里吉里SDL2 です。

冷凍鱧入りKAG3 for 吉里吉里SDL2は、鱧入りKAG3 for 吉里吉里SDL2を拡張し、次の機能をもたせたものです：

* ワイドスクリーン(1280x720)に対応したリソース
* 大きなクイックセーブ・ロードボタン
* テキスト化された機能メニューのボタン
* 追加マクロ

鱧入りKAG3 for 吉里吉里SDL2の外観を継承しつつ、ワイドスクリーン対応や簡単なマクロを定義し、より簡単に、より便利に作品を作れるよう配慮されている感じです。

これらの機能を本プロジェクトではFroHam拡張と呼びます。  
FroHam拡張は、[鱧入りKAG3 for 吉里吉里SDL2](https://github.com/uyjulian/kag3_ham)から上記機能を拡張し、やや便利なマクロを定義したものです。  
余談ですが、こおりが変更した鱧なので**冷凍**鱧入りKAG3という訳です。

通常の鱧入りと異なる点はおよそ次のようなものです：

* 初期添付の背景画像の一部がワイドスクリーン(1280x720)向けにカスタム済み。
* 2倍程度のサイズを持った「Q.ロード」「Q.セーブ」ボタン。
* 文字で表現されたメニューボタン。
* 「ページ送りとテキストレイヤー消去」や「名前表示」,「テキストレイヤー最適化」などマクロの定義。

概ねワイドスクリーン向けの手軽さは鱧入りより高いですが、やはり鱧天よりも劣ります。  
お好みに合わせて使い分けてください。

# 鱧入りKAG3 for 吉里吉里SDL2

本プロジェクトは、KAG3 for 吉里吉里SDL2からフォークしたプロジェクトです。  
KAG3 for 吉里吉里SDL2は、吉里吉里SDL2で動くよう最低限の修正を加えられた KAG3 です。

鱧入りKAG3 for 吉里吉里SDL2は、KAG3 for 吉里吉里SDL2を拡張し、次の機能を持たせたものです：

* グラフィカルなセーブ/ロード画面
* グラフィカルなコンフィグ画面
* スクロールバーを備えたバックログ機能
* 右クリックまたは画面上のボタンから呼び出せる機能メニュー
* クイックセーブ機能

KAG3が本来持つ高いカスタマイズ性をなるべく損なわず、かつ、初めて吉里吉里SDL2/KAG3を扱うユーザーでもそこそこの外観を持つ作品を作れるよう配慮されている感じです。

これらの機能を本プロジェクトではHam拡張と呼びます。  
Ham拡張は、[鱧天 for 吉里吉里2](http://hamotem.f-sp.net)から上記機能を抜粋し、コードを幾分最適化したものです。  
余談ですが、鱧天の一部が入っているので「鱧入り」KAG3という訳です。

鱧天と異なる点はおよそ次のようなものです：

* 画面サイズをある程度自由に変更可能（800x600以上を推奨）。ただしHD以上にするなら、使用している画像部品のカスタマイズが必要になるでしょう。
* シナリオファイルの配置に制限が無い。ただしシーンスキップ機能は実装されていません。
* 立ち絵の形式に制限が無い。ただし「目パチ」は実装されていません。
* イベントCGファイルの配置に制限が無い。ただしCG鑑賞モードは実装されていません。
* 「どこでもセーブプラグイン」は同梱されていません。
* 鱧天で用意されているマクロ等はごく一部を除き定義されていません。

概ねカスタマイズ性というか自由度は鱧天より高いですが、手軽さは鱧天よりも劣ります。  
お好みに合わせて使い分けてください。

鱧天 for 吉里吉里SDL2は準備中ですが、鱧天 for 吉里吉里2の文字コードをUTF-8にしたり、KAG3のシステムをKAG3 for 吉里吉里SDL2に差し替えたりすることで動作します。

なお、吉里吉里SDL2ではメニューバーが非推奨となっています。  
鱧入りKAG3 for 吉里吉里SDL2を使用する場合も、配布時はメニューを無効にしておくことをお勧めします。

メニューバーから呼び出せる機能は八割方上記の機能メニューから呼び出せるようになっています。  
現状呼び出せないのは、フォント変更、前に戻る、このソフトについて、といった辺りです。  
このうち「このソフトについて」は近々呼び出せるようにするかもしれません（しないかもしれませんが、多少TJSが書けるなら、呼び出せるようにするのはさほど難しくありません）。

---
# KAG3 License
Copyright (C)2001-2009, W.Dee and contributors  改変・配布は自由です

