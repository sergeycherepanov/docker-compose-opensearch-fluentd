# docker-compose-opensearch-fluentd

Put a file to `log/nginx/access.log`



```
git clone git@github.com:sergeycherepanov/docker-compose-opensearch-fluentd.git
cd docker-compose-opensearch-fluentd
cp fluentd.conf.dist fluentd.conf
TRAEFIK_BIND_PORT=9200 docker compose up -d
```

Open the http://localhost:9200/dashboards/.   
