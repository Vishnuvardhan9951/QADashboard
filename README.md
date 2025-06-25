# QADashboard
# Advanced Intent Annotation & QA Dashboard for Voice Command Data

This project simulates how Alexa-like systems process and label voice commands, with a focus on **natural language understanding**, **annotation consistency**, and **quality assurance**.

## 📌 Purpose

Voice assistants like Alexa need high-quality, labeled language data to understand user commands correctly. This project shows how to:

- Label voice commands with **intents** (e.g., TurnOnDevice)
- Assign **confidence scores** for multiple annotators
- Analyze agreement/disagreement between annotators
- Use a dashboard to **filter**, **inspect**, and **quality-check** labeled data

---

## 🧩 What’s in the Project

- **Sample voice command dataset** with intent labels and confidence ratings by two annotators
- **Annotation guidelines** for consistency
- **Python-based QA script** to flag mismatches, low-confidence, and disagreements
- **Interactive dashboard** built using `ipywidgets` (Jupyter-compatible) for filtering and inspection

---

## 📊 Dashboard Features

- Dropdown filter to view commands by intent
- Table view of all annotated commands
- Auto-display of filtered data without any external tool

---

## 🛠️ Tech Stack

- Python
- JupyterLab
- Pandas
- ipywidgets
- Markdown

---

## 🧠 How to Run

1. Clone this repo  
2. Launch in JupyterLab  
3. Run the notebook and use the filter dropdown  
4. Inspect QA outputs and flagged records

No installation or external tools required.

---

## 🔍 Example Use Case

“Turn on the heater” → Is it an intent to heat a room or control a smart device?  
Our system:
- Annotates it
- Compares annotators' confidence
- Flags any ambiguity for review

---

