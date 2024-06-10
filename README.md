# SOC Project - Shadow Sentry

This project aims to create a Security Operations Center (SOC) by installing Elastic Cloud and Honeypot on DigitalOcean. The goal is to detect and analyze malicious activity on your network and develop pentest scripts to attack the honeypot and monitor alerts.

## Project Objectives

### 1. Deploy Elastic Cloud on DigitalOcean
- **Setup:** Install Elastic Cloud on DigitalOcean.
- **Referral Code:** Use referral to get $200 for 60 days.
- **Configuration:** Configure Elastic Stack components - Elasticsearch, Logstash, and Kibana (ELK Stack).
- **Connectivity:** Ensure proper communication between the components.

### 2. Choose Honeypot Solution(s) and Install on DigitalOcean
- **Selection:** Choose a honeypot solution
- **Deployment:** Deploy honeypot servers on DigitalOcean instances.
- **Network Configuration:** Ensure honeypot server listens on desired network interfaces and ports.
- **Logging Configuration:** Capture all incoming traffic, interactions, and attempted exploits.
- **Simulation:** Create a realistic environment with web servers, databases, and other network services.

### 3. Harden the Honeypot Server
- **Service Management:** Disable unnecessary services and ports.
- **Updates:** Apply security updates regularly.
- **Access Controls:** Implement strong passwords and access controls.
- **Firewall Rules:** Use UFW or iptables to restrict traffic.

### 4. Create Attack Scripts
- **Attack Types:** Simulate at least three different attack types using functions.
- **Descriptions:** Provide descriptions for each attack.
- **Network Discovery:** Display the IP addresses on the network.
- **Attack Selection:** Allow the user to choose a specific attack or a random one from the list.
- **Input Validation:** Ensure the user input is valid; display a message and exit if not.
- **Target Selection:** Allow the user to choose a target IP or select one randomly.
- **Automation:** Automate everything except user input.
- **Possible Tools:** Use tools like Nmap, Hydra, Masscan, Msfconsole, Hping3, Arpspoof, etc.

### 5. Integration with Elastic Stack
- **Log Ingestion:** Configure Logstash to ingest logs from the infrastructure.
- **Storage:** Use Elasticsearch for storing and indexing logs.

### 6. Alerting and Monitoring
- **Alert Rules:** Define alerting rules based on best practices and known attack patterns.
- **Dashboards:** Configure Kibana dashboards to visualize security events and alerts in real-time.

### 7. Testing, Validation, and Logging
- **Penetration Testing:** Execute pentest scripts against the infrastructure.
- **Monitoring:** Monitor the Elastic Stack for alerts and security events.
- **Validation:** Validate the effectiveness of the alerting and monitoring system.
- **Logging:** Save attack details to a log file in /var/log, including attack type, execution time, and IP addresses.

### 8. Documentation and Reporting
- **Setup Documentation:** Document the setup process, configurations, and settings.
- **Findings Report:** Create a report detailing findings, detected security events, and alerts.
- **Recommendations:** Provide recommendations for improving security based on observed vulnerabilities.

## Project Deliverables

### Installation Guide
- Step-by-step instructions for deploying Elastic Cloud on DigitalOcean.
- Configuration instructions for Elastic Stack components.

### Pentest Scripts
- Scripts for simulating various security attacks.
- Documentation explaining the purpose and usage of each script.

### Configuration Files
- Logstash configuration files for parsing and enriching logs.
- Alerting rules and configurations.

### Dashboard and Visualizations
- Kibana dashboards for visualizing security events and alerts.
- Custom visualizations to track key security metrics.

### Testing Results
- Report on the execution of pentest scripts and observed security events.
- Analysis of the effectiveness of the alerting and monitoring system.

### Final Report
- Comprehensive report summarizing the project objectives, methodologies, findings, and recommendations.

### Video Recording of Individual Presentation (optional)

## Comments
- Use comments in your code to explain what you did.
- If using code from the internet, add credit and links.
- Include the student's name, student code, class code, and lecturer's name in the script.

## Submission
- Submit the source code (.sh) and a PDF file with screenshots proving the functions work.
- Send the project to the trainer’s email. Use "project" as the email subject.

