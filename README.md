# Git Clone

```
$ git clone https://github.com/ryojsb/prometheus-trial.git
```

# How to use

## docker build

```
# ls prometheus-trial/
docker-compose.yml	prometheus.yml

# cd prometheus-trial

# docker-compose up -d
Starting prometheus ... done
Creating grafana    ... done
```

## access to prometheus

```
http://localhost:9090
```

## access to grafana

```
http://localhost:3000
```

When you register prometheus as deta source, you have to write not localhost but prometheus_container_ip in HTTP URL.
