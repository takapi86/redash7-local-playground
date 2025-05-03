# Redash7 Local Playground

ローカル開発・検証用のRedash 7.0環境です。

## 必要条件

- Docker
- Docker Compose

## 使用方法

1. 環境の起動:
```bash
docker compose up -d
```

2. アクセス:
- URL: http://localhost:5000
- デフォルトログイン情報:
  - メールアドレス: admin@example.com
  - パスワード: admin

## 環境情報

- Redash Version: 7.0.0.b18042
- PostgreSQL: 12
- Redis: 5.0-alpine

## 注意事項

- この環境は開発・検証用です。本番環境での使用は推奨されません。
- データは`postgres-data`ボリュームに保存されます。
