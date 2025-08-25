# Elastic API & Threat Detection Rules

This project demonstrates the use of ElasticSearch and Kibana for both data management and security monitoring. It includes:

- **Elasticsearch API (CRUD):** Creating, inserting, updating, and deleting documents through Dev Tools.
- **Ingestion Pipelines:** Using processors (grok, date, lowercase, set, remove) to enrich and normalize logs.
- **Threat Detection Rules:** Writing detection rules in Kibana for suspicious PowerShell scenarios, such as:
  - Encoded commands
  - Execution policy bypass
  - Hidden window execution

## Requirements
- VMware/VirtualBox with Ubuntu & Windows VMs
- ElasticSearch & Kibana configured
- Winlogbeat or any Windows log shipper

## Author
Omar Hassan : https://www.linkedin.com/in/omar-hassan9999/
