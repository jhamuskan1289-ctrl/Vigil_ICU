# Vigil_ICU
#  VIGIL ICU – Beyond the Beep: Smarter Alerts, Safer Critical Care

**An intelligent ICU alert management concept designed to reduce alarm overload and help healthcare professionals prioritise critical patient conditions.**

##  Overview

Intensive Care Units (ICUs) rely on bedside monitoring devices to continuously track patients' vital signs, such as heart rate, blood pressure, and oxygen saturation.

However, these devices often generate frequent alarms of varying urgency. When critical warnings are mixed with repetitive or low-priority alerts, healthcare professionals may experience alarm fatigue, making it harder to recognise situations that require immediate attention.

**VIGIL ICU** aims to address this challenge through intelligent, context-aware alert management and risk-based prioritisation.

Instead of treating every alarm equally, the proposed system focuses on identifying potentially critical events and helping clinicians understand which alerts require attention first.

##  The Problem

- Continuous monitoring generates large volumes of patient data.
- Frequent alarms compete for healthcare professionals' attention.
- Repetitive and non-actionable alerts contribute to alarm fatigue.
- Important warnings may become harder to recognise, potentially delaying clinical responses.

##  Our Proposed Solution

VIGIL ICU proposes an intelligent alert management system that analyses incoming patient-monitoring data, identifies potential abnormalities, evaluates their urgency, and prioritises alerts accordingly.

The objective is to move from traditional alarm overload towards smarter, more meaningful notifications.

##  Key Features

### 1. Smart Event Detection
Analyses incoming patient-monitor signals to identify potentially critical events.

### 2. Context-Aware Filtering
Uses signal persistence and available patient context to reduce repetitive or non-actionable alerts.

### 3. Risk-Based Prioritisation
Assigns urgency levels to detected events so potentially life-threatening conditions receive higher priority.

### 4. Progressive Alert Escalation
Proposes notifying the assigned nurse first and escalating unacknowledged alerts to the next designated responder after a defined interval.

### 5. Acknowledgement & Audit Trail
Tracks alert acknowledgement, response status, timestamps, and escalation history.

##  Proposed Workflow

1. **Patient Monitor Signals:** Collect vital-sign data such as HR, SpO₂, BP, and ECG.
2. **Signal Processing:** Clean and validate incoming data.
3. **Abnormality Detection:** Identify sustained abnormal patterns.
4. **Risk Assessment:** Evaluate severity and available patient context.
5. **Alert Generation:** Generate prioritised notifications for the assigned healthcare professional.
6. **Acknowledgement Check:** Check whether the alert has been acknowledged within the defined time.
7. **Escalation:** Escalate unacknowledged alerts according to the configured response workflow.

##  Our Goal

To make ICU monitoring more meaningful by reducing unnecessary alarm interruptions and helping healthcare professionals focus on patients who need immediate attention.

## 🛠️ Technology Stack

*To be updated according to the technologies used in the actual prototype.*

- Frontend: [Add technology]
- Backend: [Add technology]
- Programming Language: [Add language]
- Database: [Add database, if applicable]
- Tools: Git, GitHub, VS Code

##  Getting Started

Clone the repository:

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

Navigate to the project directory:

```bash
cd <PROJECT_FOLDER
