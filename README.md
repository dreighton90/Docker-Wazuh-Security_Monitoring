# 🚨 Local SIEM Lab with Wazuh, Docker & Ubuntu 24.04

## ✅ Executive Summary

This project demonstrates the deployment of a local Security Information and Event Management (SIEM) lab using Wazuh, Docker, and Ubuntu 24.04 in VirtualBox. It highlights my ability to configure agents, containers, and endpoint monitoring across a simulated environment — all without bootcamp guidance.

By standing up this full security stack from scratch, I showcased hands-on skills in Linux administration, system logging, and open-source SIEM tooling.

---

## ✅ Realism and Business Relevance

- Mirrors tasks expected in SOC and SecOps roles such as agent configuration, threat detection, and log forwarding.
- Wazuh’s MITRE ATT&CK integration reflects enterprise-grade TTP monitoring.
- Demonstrates experience with infrastructure hardening, Docker orchestration, and endpoint security visibility.

---

## 🚀 Future Expansion Opportunities

This project is currently deployed locally, but is structured to scale into AWS with minor changes. Expansion plans include:

- Hosting Wazuh server on an EC2 instance
- Enabling S3-based log collection and archival
- Using Amazon CloudWatch for cross-platform log visibility
- Leveraging AWS Security Hub integration for central threat intel

---

## 🧠 What I Learned

- Installed and configured Docker on Ubuntu using CLI
- Deployed and validated Wazuh SIEM agent and dashboard locally
- Troubleshot systemctl errors and verified running services
- Located agent logs and validated dashboard threat intelligence
- Practiced `ip a`, system updates, and custom `/var/ossec/etc/ossec.conf` edits

---

## 📸 Project Walkthrough

![Ubuntu system update](screenshots/001_ubuntu_vm_update_upgrade.png)
*System update on Ubuntu 24.04 VM*

![Docker install success](screenshots/01_docker_install_succes.png)
*Docker installation successful*

![Docker running check](screenshots/02_docker_installed_running.png)
*Verified Docker is running*

![Docker Compose installed](screenshots/03_docker_compose_installed.png)
*Docker Compose installed*

![NGINX container running](screenshots/03-container-running-nginx.png)
*NGINX container launched successfully*

![NGINX accessible via localhost](screenshots/04-nginx-docker-success-localhost.png)
*Verified NGINX container via localhost in browser*

![Agent install](screenshots/Wazuh_Agent_Install_Redacted.PNG)
*Installing Wazuh agent on Ubuntu*

![Agent config file](screenshots/Wazuh_Ossec_Config_Redacted.PNG)
*Configured agent to connect to Wazuh manager*

![Agent enabled](screenshots/Wazuh_Agent_Enable_and_Stated.png)
*Wazuh agent enabled and running*

![Server login success](screenshots/Successful_Wazuh_Server_Login_Redacted.PNG)
*Successful login to Wazuh server after agent registration*

![Dashboard login screen](screenshots/Wazuh_Dashboard_Login_Redacted.PNG)
*Wazuh dashboard login interface*

![Dashboard overview](screenshots/Wazuh_Dashboard_Overview_Redacted.PNG)
*Wazuh SIEM dashboard showing active alerts and security modules*

---

## 🛠️ Tools & Technologies

- **OS:** Ubuntu 24.04 via VirtualBox
- **SIEM:** Wazuh v4.12 OVA
- **Containers:** Docker & Docker Compose
- **Monitoring:** Wazuh Dashboard
- **Security Stack:** MITRE ATT&CK, Threat Intelligence, File Integrity Monitoring

---

## 📈 Scalability Beyond Bootcamp

While this project was built post-bootcamp, its structure allows natural growth toward production-like deployment:

- Adding a centralized log shipper like Filebeat
- Building alert pipelines using Elasticsearch or OpenSearch
- Forwarding logs to a cloud SIEM like Chronicle or Azure Sentinel
- Adding compliance rulesets (PCI, NIST, HIPAA) inside Wazuh

---

## ⚠️ Legal Disclaimer

This project was conducted entirely within a locally hosted virtual lab. No public networks or external assets were scanned, breached, or accessed. All screenshots and tools were run in a sandboxed environment for educational purposes only.
