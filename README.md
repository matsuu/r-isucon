# r-isucon
r-isuconです。

## ローカル環境の立ち上げ方

### nodejs

makeコマンドで色々やります

* `make up`      : nodejs + mysqlのローカル環境を立ち上げます
* `make down`    : 環境を停止させます
* `make rm`      : コンテナの削除とmysqlボリュームの削除を行います
* `make buid/up` : コンテナのbuildと起動を行います

mysqlは middleware/tmp配下にデータを配置します。tmp以下の中身を消してコンテナを立ち上げ直せばクリーンな状態で再起動がされます。

### benchmark bootup

TODO: Yonashiro Nao


### License

MIT

### benchmark inspired by isucon7-qualify

https://github.com/isucon/isucon7-qualify/
