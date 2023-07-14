# Grafana_Prometheus

# Criando container para o Prometheus
docker run --name prometheus --rm -d -p 9090:9090 -v "/Users/adalbertoramosribeiro/Desktop/GRafana_Prometheus/prometheus.yml:/etc/prometheus/prometheus.yml" prom/prometheus

# abrindo console Prometheus
127.0.0.1:9090

# doc para client librearies(linguage for metrics)
https://prometheus.io/docs/instrumenting/clientlibs/

# for puthon @heart
https://github.com/prometheus/client_python