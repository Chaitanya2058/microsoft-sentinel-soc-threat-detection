# Cloud-Based SOC Threat Detection & Response Using Microsoft Sentinel

## Project Overview
This project demonstrates a cloud-based Security Operations Center (SOC)
implementation using Microsoft Sentinel. The objective of this project is to
simulate real-world SOC operations by detecting, analyzing, and responding
to security threats across identity, endpoint, and access control layers
within an Azure environment.

A centralized Log Analytics workspace is used to ingest security logs from
multiple sources, and Microsoft Sentinel is leveraged to create analytics
rules, incidents, and SOC dashboards (Workbooks) for continuous monitoring
and investigation.

---

## 🎯 Project Objectives
- Build a centralized SOC monitoring solution using Microsoft Sentinel
- Detect real-world attack scenarios using KQL analytics rules
- Perform SOC-style alert triage, analysis, and incident decision-making
- Visualize threats and incidents using Sentinel Workbooks
- Map detections to the MITRE ATT&CK framework

---

## 🛠️ Tools & Technologies
- Microsoft Sentinel (SIEM)
- Azure Log Analytics Workspace
- Microsoft Defender for Endpoint
- Azure Active Directory (Entra ID)
- Kusto Query Language (KQL)
- Microsoft Sentinel Workbooks (Dashboards)

---

## 🚨 Security Scenarios Implemented

### 1️⃣ Suspicious Azure AD Sign-In Activity
- Multiple failed login attempts
- Unusual IP address or location
- Identity-based attack detection

### 2️⃣ Privilege Escalation / Role Assignment Activity
- Monitoring Azure AD role changes
- Detection of high-risk privilege assignments
- Access control and identity security monitoring

---

## 📊 SOC Dashboard (Workbook)
A centralized SOC dashboard was created using Microsoft Sentinel Workbooks to:
- Monitor identity threats
- Track endpoint-based suspicious activity
- Visualize privilege escalation events
- View security incidents by severity

---

## 🧠 SOC Analyst Workflow Demonstrated
- Alert generation using analytics rules
- Incident creation and severity classification
- Initial triage and investigation
- Security analysis and decision-making
- Recommended response and preventive controls

---
