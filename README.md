# tsukuba-highway-app-with-ttl

## ダウンロード
`--recursive` オプションをつけてクローンしてください。
- `/app/master` と `/app/gh-pages` をサブモジュールとして登録しているため、オプションなしでクローンすると空のディレクトリになります。
- GitHubの **Download ZIP** 機能を使った場合も空ディレクトリになってしまうようです。

```
git clone --recursive https://github.com/hiroto7/tsukuba-highway-app-with-ttl.git
```

## ディレクトリ構成
- `/app/`
  - `/app/master/` : アプリのソースファイル。
  - `/app/gh-pages` : ビルド済みのアプリ。
- `/data/` : 作成したデータ。