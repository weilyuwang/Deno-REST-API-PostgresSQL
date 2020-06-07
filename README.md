# Deno REST API

> This is a simple REST API using Deno and Oak.
> No Database used for now - data is stored in memory

## Run

```
deno run --allow-net server.ts
```

## Routes

```
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
```