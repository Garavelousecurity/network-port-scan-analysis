# 🌐 Network Port Scan Investigation

## 📌 Scenario

A cybersecurity analyst detected unusual scanning activity targeting a company server.
A port scan was performed to identify open services and evaluate potential security risks.

The goal of this investigation is to analyze exposed network ports and recommend security improvements.

---

## 🔍 Scan Results

Example port scan output:

```
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https
3389/tcp open  rdp
```

---

## 🔎 Analysis of Open Ports

### Port 22 – SSH

Service: Secure Shell

Purpose:
Remote administration of servers.

Security Risk:
Attackers frequently attempt brute-force attacks against SSH services.

Recommendation:
Use key-based authentication and disable password login.

---

### Port 80 – HTTP

Service: Web server communication.

Security Risk:
Unencrypted traffic may expose sensitive data.

Recommendation:
Redirect traffic to HTTPS.

---

### Port 443 – HTTPS

Service: Secure web traffic.

Security Benefit:
Encrypted communication between users and the server.

Recommendation:
Ensure valid SSL/TLS certificates are installed.

---

### Port 3389 – RDP

Service: Remote Desktop Protocol

Security Risk:
RDP is a common target for attackers attempting unauthorized remote access.

Recommendation:
Restrict access using firewall rules or VPN.

---

## ⚠ Security Risk Assessment

Potential Threats:

* Brute-force login attempts
* Remote access exploitation
* Exposure of vulnerable services

Risk Level: Medium to High

---

## 🛠 Recommended Security Controls

* Restrict remote access services
* Enable firewall rules
* Implement Multi-Factor Authentication (MFA)
* Monitor network traffic
* Use intrusion detection systems

---

## 🎯 Skills Demonstrated

* Network security analysis
* Port scanning interpretation
* Attack surface assessment
* Cybersecurity risk evaluation
* Security documentation

