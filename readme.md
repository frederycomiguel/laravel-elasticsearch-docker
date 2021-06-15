
# Laravel-docker-elasticsearch



```yaml
elasticsearch:
      image: elasticsearch
      ports:
          - "9200:9200"
```


//Comandos

```
composer update
```
docker-compose build

docker-compose up -d
``` 

``` 
php artisan migrate
```