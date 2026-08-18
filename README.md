# 🧠 Nexus AI: Autonomous Agentic Workflow OS
**A Self-Healing Multi-Agent System for Enterprise Productivity.**

Nexus AI is a sophisticated Multi-Agent System (MAS) designed to close the "Coordination Gap" in office environments. It transforms static meeting transcripts into dynamic, self-monitoring workstreams that can detect human bottlenecks and autonomously reassign tasks to AI backups.

---

## 🤖 Understanding the Model & Agents
To understand the "Intelligence" of this system, we have divided the logic into four specialized AI Agents that communicate in a real-time pipeline:

1.  **📝 Neural Extraction Agent:** The "Ear" of the system. It parses raw, messy conversational text and uses keyword-intent mapping to extract structured objects (Task, Owner, Deadline).
2.  **📡 SLA Monitoring Agent:** The "Watchdog." It continuously scans the task registry to compare deadlines against the system clock. It specifically looks for "Today" or "Urgent" markers.
3.  **⚠️ Failure Detection Agent:** The "Alarm." When the monitor finds a high-risk task assigned to a human, this agent triggers a system-wide alert and activates the Voice Protocol.
4.  **🔄 Self-Correction Agent:** The "Healer." Without needing human permission, it re-routes the failing task to **Backup-Agent AI** to ensure the project deadline is never missed.

---

## 🏗️ Technical Architecture
The system is built using a **State-Based Pipeline**. Data flows from the **Input Area** through each agent sequentially, updating the **Central Session State** so that all UI elements stay synced in real-time.



---

## 🚀 Setup & Installation (Build Process)

Follow these steps to deploy the system on your local machine:

### 1. Prerequisites
Ensure you have **Python 3.9+** installed on your system.

### 2. Clone & Prepare
Open your Terminal (Command Prompt on Windows, or the terminal inside VS Code).
# Clone the repository
```bash
git clone [https://github.com/](https://github.com/)[sahil-ks]/Nexus-AI-Agentic-OS.git
cd Nexus-AI-Agentic-OS
```

# Create the requirements file (if not already there)
```bash
echo "streamlit\npandas" > requirements.txt
```
## 🚀 How to Run the Project Locally

### 1. Install Dependencies
Before running the app, install the required libraries using the following command:
```bash
pip install -r requirements.txt
```
### 2. Run the application
```bash
python -m streamlit run app.py
```

📈 Commit History & Build Stages
This project was developed in four distinct phases to ensure system stability:

v1.0 (Initial Commit): Core UI layout with Streamlit and Basic Task Table.

v2.0 (Intelligence Layer): Integration of the Extraction and Monitoring Agents.

v3.0 (Self-Healing Update): Added the Failure Detection and Auto-Reassignment logic.

v3.5 (The UX Polish): Integrated Web Speech API for voice alerts and Real-time Audit Logs.

