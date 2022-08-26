# learn grafana/k6

- https://github.com/grafana/k6
- https://k6.io/docs/

## install

```
brew install k6
```

## Run on local

run app server

```
docker compose up -d
```


tail app access logs

```
docker compose logs -f
```


run k6

```
k6 run script.js
```

run k6

```
k6 run --vus 10 --duration 10s script.js
```

