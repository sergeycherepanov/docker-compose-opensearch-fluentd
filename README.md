# docker-compose-opensearch-fluentd

Put a file to `log/nginx/access.log`



```
cp fluentd.conf.dist fluentd.conf
TRAEFIK_BIND_ADDRESS=9200 docker compose up -d
```

Open the http://localhost:9200/dashboards/.   
