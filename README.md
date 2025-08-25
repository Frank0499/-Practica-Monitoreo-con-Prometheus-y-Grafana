# Monitoreo con Grafana y Prometheus usando Docker

Este proyecto es un ejemplo sencillo para levantar un sistema de monitoreo con **Prometheus**, **Grafana** y **Node Exporter** usando **Docker Compose**.

## 🚀 Instrucciones

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/grafana-prometheus-docker.git
   cd grafana-prometheus-docker
   ```

2. Levanta los servicios con Docker Compose:
   ```bash
   docker-compose up -d
   ```

3. Accede a los servicios:
   - Prometheus: [http://localhost:9090](http://localhost:9090)
   - Grafana: [http://localhost:3000](http://localhost:3000) (usuario: `admin`, contraseña: `admin`)
   - Node Exporter: [http://localhost:9100](http://localhost:9100)

4. Configura Grafana para usar Prometheus como fuente de datos:
   - URL: `http://prometheus:9090`

5. Crea dashboards y empieza a visualizar métricas 🚀

---
📌 Proyecto de práctica para monitoreo.
