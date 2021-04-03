# docker-for-php


<https://tech-blog.rakus.co.jp/entry/20200908/docker>

こちらのサイトを参考にDockerを使用して、phpをlocalhost:8080でプレビューする環境を構築しました。


##使用方法

1.Dockerをダウンロードします。
2.このリポジトリをダウンロードします。
3.src配下に閲覧したいphpプロジェクト内容をを配置します。
4.ターミナルを開いてダウンロードしたディレクトリまで移動し docker-compose build でdockerコンテナのビルドを行います。
5.ビルドが完了したことを確認して docker-compose up でコンテナが立ち上がったらブラウザの localhost:8080 でphpファイルのプレビューをすることができます。
6.終了は ctr. + c ２回目以降の起動は docker-compose up のみで完了。


