# 🏗️ Civil Engineering Insight Studio

**An AI-Powered Multimodal System for Structural Analysis, Safety Auditing, and Progress Documentation.**

---

## 📌 Project Overview
The **Civil Engineering Insight Studio** is a specialized tool designed to bridge the gap between complex visual data on construction sites and actionable engineering intelligence. By utilizing **Gemini 1.5 Flash**, the system automates the interpretation of structural components, material identification, and safety compliance.

### 🌟 Key Features
* **Automated Structural Analysis:** Identifies structure types (e.g., RCC frames, Trusses, Suspension bridges) and key members.
* **Material Recognition:** Detects concrete, high-tensile steel (rebar), timber, and masonry.
* **⚠️ Safety Alert Flagging:** Scans for hazards like missing guardrails, unstable shoring, or PPE violations.
* **Risk Assessment:** Assigns a qualitative risk score (Low, Medium, High) to the site conditions.
* **Professional PDF Export:** Instantly generates downloadable engineering reports.

---

## 🚀 Use Case Scenarios

### 1. Material Identification
Assisting supervisors in verifying that the correct materials (concrete grades, rebar types) are being used in specific zones.


### 2. Progress Documentation
Streamlining daily logs by identifying completed structural phases (e.g., "Slab reinforcement stage").

### 3. Structural Health Assessment
Assisting engineers in identifying stress points, load paths, or signs of fatigue in aging infrastructure.


---

## 🛠️ Technical Stack
* **Language:** Python 3.9+
* **AI Engine:** Google Gemini 1.5 Flash (Multimodal LLM)
* **Web Framework:** Streamlit
* **PDF Logic:** FPDF2
* **Environment:** Python-Dotenv

---

## ⚙️ Installation & Setup

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/leela-2005/Civil-Engineering-Insight-Studio.git](https://github.com/leela-2005/Civil-Engineering-Insight-Studio.git)
   cd Civil-Engineering-Insight-Studio# Civil-Engineering-Insight-Studio
   ### 📋 Prerequisites & Requirements

This project requires **Python 3.9** or higher. The following libraries must be installed:

| Library | Purpose |
| :--- | :--- |
| `streamlit` | To power the web-based dashboard and UI. |
| `google-generativeai` | To connect with the Gemini 1.5 Flash multimodal model. |
| `fpdf2` | To generate and format the downloadable PDF reports. |
| `Pillow` | For image processing and handling user uploads. |
| `python-dotenv` | To securely manage your Google API Key via a `.env` file. |

**Install all at once:**
```bash
pip install streamlit google-generativeai fpdf2 pillow python-dotenv
