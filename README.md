# Automated Detect and Contain

Automated Detect and Contain is a policy-driven security automation system that detects malicious network activity via a SIEM and automatically enforces controlled network containment actions using Network Access Control (NAC).

The project implements a **detect → decide → respond → recover** workflow, focusing on secure automation, operational realism, and auditability rather than simple tool integration.

---

## 🔍 Problem Statement

Modern SOC environments generate large volumes of alerts, but response actions are often manual, slow, and inconsistent. Delayed containment allows attackers to move laterally, escalate privileges, or exfiltrate data.

This project addresses that gap by:
- Automatically reacting to validated security alerts
- Applying policy-based response decisions
- Enforcing network containment safely and reversibly
- Providing full visibility and audit trails for every action

---

## 🧠 Architecture Overview

High-level flow:

