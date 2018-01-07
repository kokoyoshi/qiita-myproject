# 初心者向けMacフロントエンド向け最低限の環境構築 + scssのビルド環境
https://qiita.com/kokoyoshi/items/12896561164aa7eb7c48

## インストール

```shell
$ cd path/to/wantdrop #これを落としたい場所に移動
$ git clone git@github.com:kokoyoshi/qiita-myproject.git
$ npm install
```
## ビルド

`./src/scss/**/*.scss`のファイルをビルドする。

```shell
$ npm run scss
```

`./src/scss/**/*.scss` -> `./dist/css/`

## ウォッチ

`./src/scss/**/*.scss`のファイルが更新されるたびにビルドする。

```shell
$ npm run scss:watch
```

`./src/scss/**/*.scss` -> `./dist/css/`
