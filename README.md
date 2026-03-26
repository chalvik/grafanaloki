#  Loki and Grafana

Первый запуск:

## Установка плагина Docker 
```shell
docker plugin install grafana/loki-docker-driver:2.9.4 --alias loki --grant-all-permissions
```


```shell
git clone  git@github.com:chalvik/grafanaloki.git
docker compose up -d 
```

