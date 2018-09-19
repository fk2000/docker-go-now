# docker-go-now

## 公開するまでの手順

- Nowのアカウントを作成する
- DotTkで無料ドメインを取得する。
  - Nameserverにzeit.worldを４つくらい指定しておく。
- Dockerfile, main.go, now.jsonを作成する。
  - 取得したドメインをnow.jsonのaliasに記述しておく。
- nowで一旦デプロイできるか確認する。
- 問題なければnow aliasでproductionとしてデプロイする。

## Demo

https://docker-go-now.ml


