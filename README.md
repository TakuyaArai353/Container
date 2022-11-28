# Docker練習

## イメージのビルド
```
docker image build [オプション] PATH
```

## イメージの一覧を確認
```
docker image ls [オプション]
```

## コンテナの作成・起動
```
docker container run [オプション] イメージ [コマンド]
```

## コンテナの一覧を確認
```
docker container ls [オプション]
```

## コンテナ作成時にポートを公開
```
# ホストのポート8080とコンテナのポート80をマッピング
docker container run -p 8080:80 apache:latest
```
## ログの確認
```
docker container logs [オプション] コンテナ
```

## コンテナでコマンドを実行
```
docker container exec [オプション] コンテナ コマンド
```

## コンテナを停止
```
docker container stop [オプション] コンテナ
```

## コンテナを削除
```
docker container rm [オプション] コンテナ
```

## イメージの削除
```
docker image rm [オプション] イメージ
```
