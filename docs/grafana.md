# Grafana

docker run -d --name=grafana -p 3000:3000 -e "GF_INSTALL_PLUGINS=grafana-azure-monitor-datasource" grafana/grafana:latest

