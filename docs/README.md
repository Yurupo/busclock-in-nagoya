# BusClock in Nagoya 公式サイト

黒背景・指定アイコン・名古屋駅／金山／栄の実画面を使用した、ビルド不要の静的サイトです。CSS・JavaScript・画像はindex.html内に埋め込んであり、同ファイルだけでも表示できます。スクリーンショットは2026-11-23撮影で、現在の運行情報ではありません。

## 公開方法

この変更をmainに取り込んだ後、リポジトリの Settings → Pages → Build and deployment で Source を Deploy from a branch、Branch を main、フォルダを /docs にして Save してください。公開完了後、GitHubに表示されたURLで表示・画像切り替え・拡大表示・ダウンロード・Discord導線を確認してください。

## 更新箇所

文章・スタイル・画像切り替え処理はindex.htmlにあります。配布の主リンクはGitHub Releasesのlatestです。確認済み版の表記は手動更新です。Discord招待リンクは https://discord.gg/uymNK4VpK5 です。

基本検証済み：HTMLのIDと内部リンク、画像と元ファイルの一致、3画面の切り替え・選択状態・拡大表示の処理、JavaScript構文。実ブラウザのレイアウト検証は実行環境の制限により未実施です。
