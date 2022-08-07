# dsapozhnikov76_microservices
dsapozhnikov76 microservices repository

## Docker-1 

Создал контейнер 

Сделал из него образ

Записал лог в docker-1.log

````
derek@dell5547 ~/otus/dsapozhnikov76_microservices $ docker system df
TYPE                TOTAL               ACTIVE              SIZE                RECLAIMABLE`
Images              3                   2                   63.16MB             63.15MB (99%)
Containers          2                   1                   18B                 0B (0%)
Local Volumes       6                   0                   268.9MB             268.9MB (100%)
Build Cache         0                   0                   0B                  0B`
````

### Docker-2


  1.  Создан инстанс на YC
  2.  Инициирован докер хост система на инстансе
  3.  Создана структура репозитория Docker
  4.  Создан образ приложения reddit-monolith
  5.  Запущен контейнер с приложением на инстансе
  6.  Запшуен образ приложения в docker hub

