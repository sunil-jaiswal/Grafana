# Grafana
Grafana cloud end to end setup for loki, traces and metrics on windows using Grafana Agent.

Hello I am going to tell you how I did setup grafana on my Windows OS.

First download the Grafana and install it. use below link to download grafana.
https://grafana.com/grafana/download?platform=windows

You can find agent installed in C:\Program Files\Grafana Agent.
You will be seeing **agent-config.yaml** file. I am attaching the file.
It contains the configuration for metrics(Prometheus is used), Traces (tempo is used), Logs(log file is used.)

The endpoint and username, password can be retried using below steps 
https://grafana.com/orgs/ and click on myaccount

![image](https://user-images.githubusercontent.com/19929747/217578506-ed93bac3-dda3-4bbe-88bd-b16f181a6185.png)
click on send metrics.

Hit below url in the browser

http://localhost:8080/hello


