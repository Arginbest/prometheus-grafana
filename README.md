# prometheus_grafana

<img width="750" alt="terraform-grafana" src="https://user-images.githubusercontent.com/48735802/81483562-cc19f880-9204-11ea-8181-b9e775e454cd.png">

terraform-grafana
**Prometheus and Grafana installlation **

Terraform project - Team 4

Prerequisites

t4.large
Terraform version - 0.11.14
Prometheusand Grafana server installation
Create VPC with:
3 private subnets
3 public subnets
Public subnets attached to IGW.
Private subnets attached to NG.
Configure Route Tables
Created instances with a Provisioner that installled Prometheus, Grafana, and Node Exporter .

What is Prometheus?

Prometheus is an open-source system monitoring and alerting toolkit origianally built at SoundCloud.

What is Grafana?

Grafana is an open-source visualization tool.

<img width="750" alt="screen_shot_2020-05-09_at_2 33 35_pm" src="https://user-images.githubusercontent.com/48735802/81483654-6843ff80-9205-11ea-8222-4f5039a661ae.png">

After sucessful installation you can log into Prometheus with :9090

After sucessful installation log into Grafana with :3000

![Untitled](https://user-images.githubusercontent.com/48735802/81483686-a50ff680-9205-11ea-8baa-560ba668db5e.png)

In Grafama add DataSource-Prometheus. From there you can build a Dashboard with Graphs that you pick.
