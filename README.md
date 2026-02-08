# terms-of-nitechphoto

[名工大写真映像部の部内規約(部則)](https://github.com/nitechphoto/terms-of-nitechphoto/blob/main/TermsOfNitechphoto.pdf)です。pdfファイルをご覧ください。(編集はtexファイル)

([ダウンロード](https://github.com/nitechphoto/terms-of-nitechphoto/raw/main/TermsOfNitechphoto.pdf))

## 使い方

### 環境構築の方法
- TeX Liveの最新版をインストール
  - `sudo apt install texlive-full` を実行する。(Linux)

### コンパイルの方法
- `latexmk TermsOfNitechphoto.tex`を実行する。

### フォーマットの方法
- `latexindent -w -l TermsOfNitechphoto.tex`を実行する。

## 改定
- [部則](https://github.com/nitechphoto/terms-of-nitechphoto/blob/main/TermsOfNitechphoto.pdf)の「第 9 条 改定」を参照。
- branch作成やforkを行ってPull Requestを作成する。ただしこの際に「表紙」と「第 11 章 制定」の日付については承認が降りた日とするので、`nn`で埋めておけば良い。
- 承認が降りたら、日付を変更し、マージを行う。

## ライセンス
- [CC BY 4.0](LICENSE)
- [C0de部の部内規約](https://github.com/c0demattari/terms-of-c0de) より改変して使用している。
