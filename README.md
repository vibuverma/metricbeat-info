## Metricbeat
<h4> Metricbeat is the heart of this whole monitoring stack which we are planning to deploy. Metricbeat helps you monitor your servers and the services they host by collecting metrics from the operating system and services. In real-world scenarios, you can deploy Metricbeat on all your Linux, Windows, and Mac hosts, k8s clusters connect it to Elasticsearch. You will get system-level CPU usage, memory, file system, disk IO, and network IO statistics, as well as top-like statistics for every process running on your systems. You can transform or enrich your metrics then use Logstash/FluentD before sending it to Elasticsearch. </h4>

<br>
<br>


Metricbeat deployment and monitoring mainly involve the following steps - <br>
- install Metricbeat on each node/system which you want to monitor
- specify the metrics you want to collect
- send the metrics to Elasticsearch or you can send to logstash for data enrichment and then to Elasticsearch
- visualize the metrics data in Kibana using OOTB dashboards or build your own