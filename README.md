# showdoc docker-compose running

## how to running

* start server

```code
docker-compose up -d
```

* copy data

```code
docker-compose exec doc cp -fr /showdoc_data/html/ /var/www/
```