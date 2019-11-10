
## 環境準備

### node moduleインストール
```
yarn install
```

## コマンド

### build
```
cargo build

```

### ローカル環境実行
```
yarn sls invoke local -f rust-function-two --path application/tests/resources/example_request.json
```

### deploy
```
yarn sls deploy
```

### AWS上で実行
```
yarn sls invoke -f rust-function-two --path application/tests/resources/example_request.json
```

### リソース一式削除
```
yarn sls remove
```
