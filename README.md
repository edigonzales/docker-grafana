# docker-grafana

```
docker run --rm -p 3000:3000 --user "$(id -u)" --volume "$PWD/data:/var/lib/grafana" --name=grafana grafana/grafana-oss:10.0.2
```

admin/admin
