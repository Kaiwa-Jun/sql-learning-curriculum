# 環境構築手順

```
git clone https://github.com/Kaiwa-Jun/sql-learning-curriculum.git
```

```
cd sql-learning-curriculum
```

```
docker-compose up
```

別のターミナルを開く
実行中の MySQL コンテナにアクセス

```
docker exec -it <container_name> mysql -u user -p
```

データベースを選択

```
USE mydatabase;
```

試しに user テーブルの内容を確認

```
SELECT * FROM user;
```

# 課題問題

## 問題 1

status が「アクティブ」のユーザーを取得する

## 問題 2

age が 30 歳以上のユーザーを取得する

## 問題 3

city が「東京」または「大阪」のユーザーを取得する

## 問題 4

name が「田中」で始まるユーザーを取得する
