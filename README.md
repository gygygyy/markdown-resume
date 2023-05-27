# <center>Gary Chen(陳冠聿)</center>

Email: gary515chen@gmail.com

[Linkedin](www.linkedin.com/in/guanyu515chen)

## Education
* 2012/08 ~ 2016/06 
  * **Department of Information Management** ; *Chinese Culture University*

## Summary
* 3+ year of Site Reliability Engineer experience management Cloud infrastructure (GCP), CI/CD and monitoring.

## Experience

### Coolbe Inc., Taipei, 2021/01 - Current
#### Site Reliability Engineer
* Containerize applications, Ex. php, node.js, java, golang ...

* CI/CD
  * Deploy application to GKE by integrating GitLab CI/CD with Ansible.
  * Gitlab CI/CD combined with TerraformAutomate the creation of relevant resources such as Pub/Sub, Cloud Function, Dataflow, BigQuery, and Cloud Scheduler in GCP using GitLab and Terraform to accelerate Data Warehouse construction.

* Cloud Infrastructure
  * Create various services in GCP using Terraform.
  * GCP: IAM, VPC, GKE, GCE, Cloud SQL, Cloud Storage, Cloud Function, Cloud CDN, Cloud DNS, Big Query, Dataflow...

* Kubernetes
  * Elastic Cloud on K8s
  * Cert Manager
  * Externel DNS
  * K8ssandra
  * Kube-prometheus-stack
  * MinIO
  * Traefik
  * Keda

* Create Cassandra (K8ssandra) as the database for a one-on-one conversation application.

* Monitoring
  * Collect logs using ELK (Elasticsearch, Logstash, Kibana) and parse log levels using the open-source project `elastalert` to send alerts to Discord.
  * Utilize Kibana to visualize log levels in charts for easier tracking and monitoring.
  * Monitor infrastructure using Prometheus and Grafana, and in case of any abnormalities, send alerts to Discord through Grafana or Alertmanager.
  * Monitor the health status and expiration of certificates for various services using Blackbox.
  * Monitor whether scheduled tasks are executed within the specified time frame and check if the execution status is successful using Pushgateway.
  * Persist Prometheus metrics to object storage (S3, GCS, etc.) using Thanos for long-term storage.
  * Store alerts from Alertmanager using Alertsnitch and visualize the alert status using Grafana.
  * Integrate GCP Monitoring Alert with Pub/Sub and Cloud Functions to send notifications to Discord.

* Online service maintenance.

* Assist the RD (Research and Development) team in troubleshooting online system issues.
