# docker-fake-prometheus
Docker fake prometheus

```bash
docker build -t docker-fake-prometheus:v0.1 docker-fake-prometheus/
docker run -d -p 5000:5000 docker-fake-prometheus:v0.1
docker pull kal1sha/docker-fake-prometheus # 0.0.0.0:5000/metrics
```