# Grafana_Prometheus

# Criando container para o Prometheus
docker run --name prometheus --rm -d -p 9090:9090 -v /Users/adalbertoramosribeiro/Desktop/GRafana_Prometheus/prometheus.yml prom/prometheus

# abrindo console Prometheus
127.0.0.1:9090
