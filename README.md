# Splunk SIEM Monitoring & Threat Detection Lab

## Project Overview

This project demonstrates the design and implementation of a Security Information and Event Management (SIEM) solution using Splunk to monitor, correlate, and detect security events in a Linux-based server environment.

The objective was to simulate real-world SOC operations by improving visibility into system activity, detecting malicious behavior in real time, and strengthening incident response readiness.

---

## Lab Environment

- Linux Server (Primary Log Source)
- MySQL Database Server
- IPv4 Network Infrastructure
- SSL/TLS Encrypted Communications
- Centralized Log Ingestion into Splunk

System and authentication logs were forwarded and indexed within Splunk for real-time analysis.

---

## Detection Use Cases Implemented

### 1. SSH Brute-Force Detection
- Monitored repeated failed login attempts
- Created SPL-based alert when threshold exceeded
- Classified as High severity risk

### 2. Privilege Escalation Monitoring
- Tracked abnormal sudo usage
- Identified unauthorized root access attempts

### 3. Suspicious IP Correlation
- Detected repeated connections from unknown sources
- Correlated events across defined time windows

### 4. Data Exfiltration Indicators
- Flagged abnormal outbound traffic volume
- Assigned Medium severity alert classification

---

## Risk Detection Methodology

Risk Score = Likelihood x Impact

Events were categorized as:
- Low Risk
- Medium Risk
- High Risk

Alert thresholds were configured to reduce false positives while maintaining detection accuracy.

---

## Skills and Techniques Demonstrated

- Log ingestion and parsing
- SPL query development
- Event correlation logic
- Alert rule configuration
- Security event analysis
- Incident documentation
- Threat detection engineering

---

## Key Outcomes

- Improved centralized visibility across infrastructure
- Reduced Mean Time to Detect (MTTD)
- Strengthened proactive threat monitoring
- Simulated real-world SOC analyst workflow

---

## Future Enhancements

- Integration of threat intelligence feeds
- Automated incident response playbooks
- Advanced dashboard development
- Implementation of anomaly-based detection models
