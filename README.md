# README

RailsでActiveAdminを触ってみるためのリポジトリ  

以下を参考に触ってみる  
[Railsで最速で管理画面を作る！](https://qiita.com/enomotodev/items/5f6d9348207124a41bf9)

* Ruby version: 2.4.1
* Rails version: 5.1.6
* ActiveAdmin version: 1.3.0
* devise version: 4.4.3

環境構築はDockerを用いている。(DBはmysqlを使用)  
このリポジトリをcloneした後、

```
$ docker-compose up -d
```

をすると環境が立ち上がる。  
初回起動時はrailsコマンドによるDBの設定が必要。

```
$ docker exec -it <webコンテナ名> bash
# rails db:create
```

MIT License
