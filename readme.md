# 福岡キャンプマップ

## DEMO

  - デプロイしている場合はURLを記入（任意）

## 紹介と使い方

  - 福岡のキャンプ場のマップ。現状は福岡市内のキャンプ場のみ。
  - 現在地（HERE）が中心に来るようにしています。
  - 施設詳細は未完成。キャンプ場の標高や天気の情報を入れたかったです。
  - 公式サイトへのリンクを貼っています。

## 工夫した点

  - 通常のマップとグレースケール等の切り替え。（鳥瞰図を入れたかったが反応せず。非対応？）
  - infoBoxで公式サイトへ飛べたら便利だと思ったので入れました。
  - キャンプ場の緯度経度は固定で入れればいいと思い、グーグルマップで緯度経度を調べて入力しました。少しずれていますが、おおよその位置で表示できました。

## 苦戦した点

  - Open-Meteo APIの情報を組み込みたかったのですが現状できていません。（情報の取得まではできました。）
  - BingMapsAPIで現在地からキャンプ場までのルート表示などをしたかったですができませんでした。
  - 星をみるひとというAPIを使ってキャンプ場からどんな星座が見えるかというのを表示したかったです。

## 参考にした web サイトなど

  - 講義資料とラーニングシステム
  - Open-Meteo APIの使い方  https://paiza.hatenablog.com/entry/2021/11/04/130000
  - Open-Meteo APIを使った実例 https://neos21.net/blog/2021/11/20-01.html