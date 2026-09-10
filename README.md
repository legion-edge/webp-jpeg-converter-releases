# WebP JPEG Converter

WebPとJPEGを、画像・フォルダ・ZIPごとに相互変換するWindows向けの無料ポータブルアプリです。

[アプリ紹介](https://legion-edge.dev/#apps) · [正式版 v1.0.0](https://github.com/legion-edge/webp-jpeg-converter-releases/releases/tag/v1.0.0)

## ダウンロードと起動

1. [Windows x64版ZIP](https://github.com/legion-edge/webp-jpeg-converter-releases/releases/download/v1.0.0/WebpZipConverter-1.0.0-windows-x64.zip)をダウンロードします。
2. 書き込み可能な新しいフォルダへ、ZIPをすべて展開します。
3. `WebpZipConverter.exe` を起動します。Pythonのインストールは不要です。

`runtime`・`source`・`licenses` は同梱したままにしてください。詳しい操作は同梱の `使い方.md`、配布物の確認用SHA-256と注意事項はリリースページに記載しています。Windows 11 x64で動作確認済みです。

## 主な機能

- WebP / JPEGの相互変換。単体画像、サブフォルダを含むフォルダ、ZIPに対応。
- ドラッグ＆ドロップ、一括変換、進捗表示、中止、ログ保存。
- ZIP内画像の連番化と、元ファイル名を付けるオプション。
- 変換前後の容量と増減率を表示。元ファイルは変更せず、同名出力も上書きしません。
- 変換はローカルで完結し、画像をアップロードしません。

このリポジトリは正式配布物とリリース情報の公開用です。実行に必要な `source` は配布ZIPに含まれます。GitHubが自動生成する「Source code」のZIP/TARはアプリ本体ではありません。上記のWindows x64版をお使いください。
