# graphql-tutorial-with-next-and-go
Next × Goを使用したGraphQLの学習

## 環境構築

```bash
cd frontend
npm ci
```

## GraphQL Go 自動生成

```bash
go run github.com/99designs/gqlgen
```

## 実行

#### API GraphQL

```bash
cd api
go run server.go
```

#### Frontend

```bash
cd frontend
npm run dev
```
