# sql-antipatterns

## 環境構築

### 初回の起動するコマンド

```bash
# .env 作成
cp .env.example .env
# 起動
docker compose up -d
# MySQL に接続
docker compose exec mysql mysql -uroot -p playground
```

### その他コマンド

```bash
# 停止
docker compose stop
# 再開
docker compose start
# ログ確認
docker compose logs
# コンテナ削除
docker compose down
# データも含めて初期化
docker compose down -v
# 起動状態を確認
docker compose ps
```

```sql
# テーブル一覧
SHOW TABLES;
```
