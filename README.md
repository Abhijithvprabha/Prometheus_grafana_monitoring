# Prometheus_grafana_monitoring
Prometheus_Grafana_Monitoring This repository provides the setup and configuration for monitoring systems and applications using Prometheus and Grafana. It includes configurations, dashboards, and examples to help you quickly get started with monitoring and visualization.

Steps:

1) Update the system to the lates 
apt update -y
![alt text](image.png)

2) Create system user and the Directory for prometheus
![alt text](image-1.png)

3) Download the Prometheus binary files to the /tmp folder
cd /tmp/
wget https://github.com/prometheus/prometheus/releases/download/v2.46.0/prometheus-2.46.0.linux-amd64.tar.gz
![alt text](image-3.png)

4) We will use the tar command to extract the downloaded file
tar -xvf prometheus-2.46.0.linux-amd64.tar.gz
![alt text](image-4.png)
