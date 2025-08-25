# ⚡ Elastic API & Threat Detection Rules

A practical project showcasing how to use **Elasticsearch** and **Kibana** for both log management and security monitoring.  
It walks through CRUD operations, ingestion pipelines, and building custom threat detection rules to spot suspicious PowerShell activity.  

---

## 🔹 Features
- **Elasticsearch API (CRUD):**  
  Create, insert, update, and delete documents directly from Kibana Dev Tools.  

- **Ingestion Pipelines:**  
  Enrich and normalize logs with processors: `grok`, `date`, `lowercase`, `set`, and `remove`.  

- **Threat Detection Rules:**  
  Detection scenarios for malicious PowerShell usage, including:  
  - Encoded commands (`-EncodedCommand`, `-e`)  
  - Execution policy bypass (`-ExecutionPolicy Bypass`)  
  - Hidden window execution (`-WindowStyle Hidden`)  

---

## 🛠 Requirements
- VMware/VirtualBox with **Ubuntu & Windows VMs**  
- **Elasticsearch & Kibana** properly configured  
- **Winlogbeat** (or any log shipper) on Windows  

---

## 👤 Author
**Omar Hassan**  
[LinkedIn](https://www.linkedin.com/in/omar-hassan9999/)
