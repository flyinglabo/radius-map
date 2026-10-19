半径マップ Android ホーム画面追加用

【公開方法（GitHub Pagesを使う例）】
1. GitHubにサインインし、新しいPublic repositoryを作成します（例: radius-map）。
2. このZIPを解凍し、中のファイルをすべてリポジトリの一番上の階層にアップロードします。
   index.html / manifest.webmanifest / sw.js / icon.svg / icon-192.png / icon-512.png
3. リポジトリの Settings > Pages を開き、Build and deployment の Source を Deploy from a branch にします。
4. Branch を main、フォルダーを /(root) にして Save。
5. Pagesに表示された https://ユーザー名.github.io/radius-map/ のようなURLをAndroidのChromeで開きます。
6. Chromeの︙メニューから「アプリをインストール」または「ホーム画面に追加」を選びます。

注意:
- GitHub Pagesの公開サイトはインターネット上で公開されます。機密情報をアップロードしないでください。
- 地図タイルとLeafletは外部配信元から読み込むため、地図表示にはインターネット接続が必要です。
- 現在地取得にはAndroidの位置情報とChromeのサイト位置情報許可が必要です。
- ホーム画面追加後でも、現在地の許可は初回に求められる場合があります。
