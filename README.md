# mysql-phpmyadmin-docker

使用 Docker Compose 建立 MySQL、phpMyAdmin 服務

## .env

```log
MYSQL_USER="user"
MYSQL_PASSWORD="password"
MYSQL_PORT=3306
PHPMYADMIN_PORT=8888
```

## Dev

```bash
# 啟動
$ docker compose up -d

# 關閉
$ docker compose down

# 查看狀態
$ docker compose ps
```
