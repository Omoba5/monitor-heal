# monitor-heal
Observability using Prometheus and Grafana. 

To make use of this project, do the following:
1. Install docker-engine and docker-compose by following these [steps](https://docs.docker.com/engine/install/).
2. Modify the second element in line 17 of the `config/prometheus.yml` file to match your other node_exporter URL or remove it completely. 
3. Replace the Slack API webhook URL with yours in the `config/alertmanager.yml`.

Run the following in the projects directory to set this up:
```
sudo docker compose up
```
