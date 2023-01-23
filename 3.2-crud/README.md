# CRUD

### Сборка образа

```
docker build ./ --tag stock_products
```

### Запуск контейнера

```
docker run --name=my_stock_products -d -p 8000:6060 stock_products
```