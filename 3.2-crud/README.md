# CRUD

### Сборка образа

```
docker build ./ --tag stock_products
```

### Запуск контейнера

```
docker run --name=my_stock_products -d -p 6060:8000 stock_products
```