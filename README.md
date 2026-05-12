# 🛡️ Cloud SOC Analyst Lab

## LetsDefend × Hack The Box

Hands-on SOC analyst investigations performed in a cloud-based Security Operations Center environment.

## 🚨 SOC Operations Dashboard

| Module                 | Status    | Description                                   |
| ---------------------- | --------- | --------------------------------------------- |
| 📡 Monitoring          | 🟢 Active | Real-time alert triage and incident ownership |
| 📊 Log Management      | 🟢 Active | Security event analysis and correlation       |
| 📁 Case Management     | 🟢 Active | Investigation lifecycle tracking              |
| 💻 Endpoint Security   | 🟢 Active | Host and endpoint investigation               |
| 📧 Email Security      | 🟢 Active | Phishing and email threat analysis            |
| 🧠 Threat Intelligence | 🟢 Active | IOC and reputation validation                 |
| 🧪 Sandbox Environment | 🟢 Active | Malware execution and behavioral analysis     |
________________________________________________________________________________________
## 🎯 About This Repository

This repository documents my practical experience using the LetsDefend Cloud SOC Analyst Lab, part of the Hack The Box ecosystem.

The lab simulates a real enterprise Security Operations Center (SOC) where I investigate and respond to security alerts involving:

Web attacks

Phishing attempts

Endpoint activity

Network anomalies

Malware behavior

Threat intelligence correlation

This repository is designed as a SOC investigation portfolio, showcasing:

Alert triage

Log analysis

Incident investigation

Root cause analysis

Security response workflow
______________________________________________________________________________________
## 🖥️ SOC Lab Environment

### 📡 Monitoring Center
<img width="1328" height="494" alt="image" src="https://github.com/user-attachments/assets/59def6ef-b0c0-4b61-ba4c-cac8b1a0133e" />

The Monitoring dashboard acts as the primary SOC alert queue.


### Features

Real-time alert monitoring

Severity-based prioritization

Rule name & Event ID tracking

Ownership assignment workflow

### Alert Workflow

Main Queue → Investigating → Closed

### Investigation Focus

Alert validation

Severity assessment

Event correlation

Threat prioritization
______________________________________________________________________________________
### 📊 Log Management
<img width="1063" height="484" alt="image" src="https://github.com/user-attachments/assets/68cd4bb5-9a20-4c60-82d6-c51c9133cb1e" />

Centralized event analysis and security log investigation.

| Field                 | Purpose                  |
| --------------------- | ------------------------ |
| `source_address`      | Identify attacker/source |
| `destination_address` | Target system            |
| `source_port`         | Originating service      |
| `destination_port`    | Targeted service         |
| `raw_log`             | Full event visibility    |
| `type`                | Event classification     |

#### Investigation Capabilities
Event searching

Traffic analysis

IOC identification

Attack timeline reconstruction
______________________________________________________________________________________
### 📁 Case Management
<img width="1200" height="567" alt="image" src="https://github.com/user-attachments/assets/e951c860-3846-49a0-841f-66293fddd410" />
SOC-style incident documentation and workflow tracking.

#### Workflow

Open investigation

Analyze evidence

Document findings

Assign root cause

Close or escalate incident

#### Purpose

Structured investigations

Incident lifecycle tracking

Documentation of findings

SOC process simulation
______________________________________________________________________________________
### 💻 Endpoint Security
<img width="1200" height="456" alt="image" src="https://github.com/user-attachments/assets/7b76923a-79b6-4af9-8ca6-ee3b694b4744" />
Endpoint visibility and device-level investigation.

#### Investigation Areas

Suspicious processes

Malware execution

Persistence mechanisms

Privilege escalation attempts

Host anomalies

#### SOC Activities

Endpoint inspection

Process monitoring

Behavioral analysis
_____________________________________________________________________________________
### 📧 Email Security
<img width="1248" height="386" alt="image" src="https://github.com/user-attachments/assets/a9aff732-561d-43aa-ab58-287f28ea1ce2" />

Analysis of phishing and email-based attacks.

#### Analysis Areas

Header analysis

Email spoofing detection

Attachment inspection

Malicious URL analysis

Sender reputation validation

#### Detection Focus

Phishing indicators

Social engineering attempts

Suspicious domains

Malicious payload delivery
______________________________________________________________________________________
### 🧠 Threat Intelligence
<img width="1237" height="498" alt="image" src="https://github.com/user-attachments/assets/c9015766-4a46-4f50-bcd2-59745f5f29c4" />

Threat enrichment and IOC validation.

### Used For

IP reputation analysis

Domain intelligence

IOC correlation

Blacklist verification

Threat actor infrastructure analysis
______________________________________________________________________________________
🧪 Sandbox Environment
<img width="1232" height="435" alt="image" src="https://github.com/user-attachments/assets/57f267a4-ebe2-4066-8484-f04debf5af40" />

Safe malware execution environment for Linux and Windows.

#### Capabilities

Suspicious file execution

Malware behavior analysis

Network activity inspection

Dynamic analysis

Safe testing environment

#### Platforms

Windows Sandbox

Linux Sandbox
______________________________________________________________________________________
