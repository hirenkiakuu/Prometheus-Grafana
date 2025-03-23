### Grafana + Prometheus setup


1) make sure you have installed Docker and Docker Compose:
```
docker --version
docker-compose --version
```
2) clone repository
```
git clone <url>
cd /folder
```
3) start Docker daemon (Docker desktop or CLI)
4) run containers:
```
docker-compose up -d
```

<b>Prometheus:</b> localhost:9090
<b>Grafana:</b> localhost:3000
<b>cAdvisor:</b> localhost:8080

Prometheus - собирает метрики и хранит в виде временных рядов
cAdvisor - мониторинг потребляемых контейнерами ресурсов
Grafana - визуализация данных