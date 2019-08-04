![](https://i.imgur.com/TXWhxrO.png)

# CiPT Lite
macOS用デストップアプリケーション。

クリップボードのテキストをプレーンテキストにします。その際、安全に結合文字列を合成します。それでも結合文字が混在していたら警告します。絵文字モディファイアの混在も警告します。

## インストール
CiPT Lite.appをアプリケーションフォルダなどへコピーします。
* システム要件：OS X 10.9以降
* ダウンロード後、CiPT Lite.appを選択し、右クリックメニューの［開く］を選択してください。

## 使い方
CiPT Lite.appを起動しておきます。キーボードショートカットで実行します。
* メニューバー［CiPT Lite > 環境設定...］
    * キーボードショートカットを変更できます。
    * 結合文字列や絵文字モディファイアの警告をOFFにできます。

## 詳細
CiPT Liteは、CarbonアプリだったCiPTを64bit Cocoaアプリとして作り直したものです。Carbon版CiPTは仕様や設定が複雑すぎたので、Cocoa版は必要最小限に絞ってLiteとしました。

ソースは[Xojo](https://www.xojo.com/)のプロジェクトファイルです。[MBS Plugin](https://www.monkeybreadsoftware.de/xojo/)を使用しています。

### 旧バージョンとの違い
* 黒いフローティングウインドウがありません。
* 結合文字を検索する機能がありません。警告のみです。

## 旧バージョン
[CiPT 3.7.0](https://tama-san.com/cipt/)
* 2015.7.25
* システム要件：OS X 10.4以降
* Universal Binary