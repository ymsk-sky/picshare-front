# 開発環境を構築

## ローカル作業準備

リポジトリのクローン

```
git clone {URL}
```

作業ディレクトリへの移動

```
cd picshare-front
```

## vue開発環境の構築

コンテナを起動

```
docker-compose up -d
```

依存するライブラリをインストール

```
docker-compose exec workspace yarn install
```

サーバーの起動

```
docker-compose exec workspace yarn serve
```

下記URLへアクセス

```
http://localhost:8080
```
