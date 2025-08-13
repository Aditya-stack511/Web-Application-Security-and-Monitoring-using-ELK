Web Application Security Assessment & Real-Time Monitoring

Overview:
This project was developed as part of my CDAC – PG-DITISS course. I performed a complete web application security along with real-time log monitoring to identify, analyze, and track vulnerabilities in a safe lab environment.
The project combined security testing tools with the ELK Stack to create a centralized monitoring solution for better security insights and proactive defense.

Objectives:

Identify and assess common web application vulnerabilities.

Use industry-standard tools for scanning, testing, and analysis.

Centralize logs from all security tools into ELK for monitoring.

Gain hands-on experience with SIEM-like workflows.

Tools & Technologies Used:
Vulnerability Assessment Tools:

OWASP ZAP – HTTP/HTTPS traffic interception and analysis.

Burp Suite – Automated vulnerability scanning.

Nikto – Web server assessment.

SQLMap – SQL Injection testing.

Wapiti – Web fuzzing for hidden vulnerabilities.

Nuclei – Template-based fast vulnerability scanning.

Log Monitoring & Visualization:

ELK Stack (Elasticsearch, Logstash, Kibana) – Log storage, analysis, and visualization.

Filebeat – Log shipper for integrating tool outputs with ELK.

Lab Setup:

Operating System: Ubuntu Linux (VM)

Target Application: DVWA / Mutillidae (vulnerable test web apps)

Network: Isolated lab network for ethical testing

Exercises Performed:

Traffic Interception – Captured and analyzed HTTP/HTTPS requests with OWASP ZAP.

Vulnerability Scanning – Used Burp Suite to detect vulnerabilities.

Web Server Assessment – Ran Nikto for outdated software and misconfigurations.

SQL Injection Testing – Used SQLMap for injection testing and database enumeration.

Fuzzing – Performed hidden attack vector discovery with Wapiti.

Template-based Scanning – Used Nuclei for fast vulnerability detection.

Log Integration & Monitoring – Sent all tool outputs to ELK via Filebeat and visualized them in Kibana dashboards.

Expected Outputs:

Detailed vulnerability reports from each tool.

Real-time Kibana dashboards showing scan logs.

Identification of high-risk issues such as SQL injection, outdated components, and insecure server configurations.

Key Learning:
Security is not only about finding problems — it’s about continuously monitoring systems and preventing attacks before they happen.

License:
This project is for educational purposes only. Do not use these techniques on systems without proper authorization.
