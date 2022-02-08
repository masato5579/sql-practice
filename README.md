前提
TablePlus
docker, docker-compose コマンドが実行できること

# sql-practice

## コマンドの実行
docker-compose up -d

## tablePlus接続
Name:sql-practice
Host:127.0.0.1
Port:13306
User:root
password:root

上記でテストが通ればOK。

## tablePlusでデータベースを作成する(名前はなんでも良い)

## 下記のサイトから好きなサンプルDBデータをDL
https://dev.mysql.com/doc/index-other.html

## 解凍して、dumpファイルを出す(例：world.sql)

## TablePlus左上のFile>importを選択し、先程のdumpファイルを選択する

##　インポートする
