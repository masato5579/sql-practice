## 前提:
- TablePlusがインストール済
- docker, docker-compose コマンドが実行できること

## コマンドの実行
docker-compose up -d

## tablePlus接続
- Name:sql-practice
- Host:127.0.0.1
- Port:13306
- User:root
- password:root

上記で接続できれば、OK。  
できなかったら、頑張ってください。

## サンプルDBを回答してDBに反映する

1.tablePlusでデータベースを作成する(名前はなんでも良い)


Connection>open a Database > New

2.下記のサイトから好きなサンプルDBデータをDL

https://dev.mysql.com/doc/index-other.html

3.解凍して、dumpファイルを出す(例：world.sql)

4.TablePlus左上のFile>importを選択し、先程のdumpファイルを選択する

5.インポートする
