# 香川研究室論文テンプレート

-   香川大学から配布されるテンプレートに追記する形で作成しています。
-   論文本体は out/main.pdf です。
-   risepaper.cls には、卒論/修論用スタイルファイルの使い方が書かれているので読んでおいてください。
-   git による変更履歴の管理を忘れずに行ってください。

## 使用方法

1. git clone もしくは use this template で香川研究室にリポジトリを作成。
2. tex と vscode の拡張機能の latex workshop をインストール。
3. vscode で作業。

## ディレクトリ構成

| 名前          | 用途                                            |
| ------------- | ----------------------------------------------- |
| /.vscode      | vscode の設定                                   |
| /assets       | 画像、ソースコード用                            |
| /bib          | 参考文献データベース                            |
| /chapters     | 各章の tex ファイル用                           |
| /out          | pdf,log ファイル等の出力先                      |
| /references   | 参考文献 pdf 用(できる限り残しておいてください) |
| main.tex      | メイン                                          |
| risepaper.cls | 大学配布のクラスファイル(スタイルファイル)      |
| .latexmrkc    | ビルド用                                        |

### 注意
 一部のtexliveのバージョンでは、出力先フォルダから参照を行うため（out/bib/ref.bibを探すなど）、参考文献が見つからないエラーが発生しています。　　
 .vscode/setting.jsonの"latex-workshop.latex.tools","args"から　 -outdir=%OUTDIR% を削除してみてください。

### 参考にしたサイト

https://texwiki.texjp.org/?Visual%20Studio%20Code%2FLaTeX  
https://qiita.com/rainbartown/items/d7718f12d71e688f3573
