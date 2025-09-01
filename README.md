# MySQL-practice
MySQLの操作練習&docker-compose&githubの練習です。<br>
MySQL公式がサンプルとして出している[WorldDataBase](https://dev.mysql.com/doc/index-other.html)をDocker内で起動してくれます(多分)。<br>

## 起動方法
`docker compose up -d`<br>
`docker exec -it <コンテナ名> bash -p`(コンテナ名は`docker container ls`で調べられるよ)<br>
(↑それかdocker desktopから直接ターミナルに侵入でもおｋ)<br>
`mysql -u root -p -h 127.0.0.1`でルートでsqlを起動<br>
PW:`password`

## MySQLの使い方
- MySQL内のデータベースを確認→`SHOW DATABASES;`<br>
- データベースの使用を宣言→`USE <データベース名>;`<br>
- データベース内のテーブルを確認→`SHOW TABLES FROM <データベース名>;`<br>
- テーブル内カラム(項目)を確認→`SHOW COLUMNS FROM <テーブル名> FROM <データベース名>;`<br>



