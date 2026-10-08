# AI-Gmail-Triagent
Autonomous multi-agent email &amp; notification triage engine powered by LangChain, Ollama, and AMD AI hardware. Features contextual email prioritization, zero-trust security scanning, personalized smart replies, and local Chroma DB memory.
# AI Gmail Triage Agent

### Autonomous Intelligent Email, Notification Management & Smart Reply Agent

**Team:** Agentic Nexus  
**Hackathon:** AMD AgentForge Hackathon 2026  
**Track:** Build for your Community

---

## 🚀 Overview

AI Gmail Triage Agent is an AI-powered communication assistant designed to reduce information overload caused by notifications and messages across multiple applications.

The core idea is simple:

**Important communications from different platforms → AI analysis → Prioritization → One intelligent Gmail experience**

Instead of constantly switching between applications, the agent helps identify what is important and provides useful actions such as prioritization, summarization, task extraction, phishing detection, and smart reply generation.

---

## 🎯 Problem Statement

Modern users receive communications from many different platforms including Gmail, LinkedIn, WhatsApp, Slack, GitHub, Microsoft Teams, Google Calendar, banking applications, shopping applications, and other productivity services.

Important messages can easily get buried under promotional emails, low-priority notifications, and general communication.

This creates:

- Information overload
- Too many application switches
- Missed deadlines
- Missed important messages
- Reduced productivity
- Difficulty identifying urgent communication

Users need a smarter way to understand and prioritize their communications.

---

## 💡 Our Solution

The **AI Gmail Triage Agent** acts as an intelligent communication assistant.

The agent analyzes communication and helps determine what requires attention.

The workflow focuses on:

1. Receiving communication data
2. Understanding message context
3. Identifying importance and urgency
4. Prioritizing communications
5. Summarizing lengthy conversations
6. Extracting tasks, meetings, and deadlines
7. Detecting suspicious or phishing-related content
8. Generating context-aware smart replies
9. Presenting useful results through a unified workflow

The goal is to reduce communication overload and help users focus on important information.

---

## 🧠 Key Capabilities

### 📩 Intelligent Triage
Analyzes communication and assigns meaningful priority based on its content and context.

### 📝 Summarization
Converts lengthy conversations into concise summaries.

### ✅ Action Extraction
Identifies useful information such as:

- Tasks
- Meetings
- Deadlines
- Reminders
- Required actions

### ✉️ Smart Replies
Generates context-aware reply suggestions based on the communication being analyzed.

### 🛡️ Security Awareness
Identifies potentially suspicious or phishing-related communication patterns.

### 🔎 Explainable Results
The system provides understandable reasoning behind important AI decisions wherever applicable.

---

# 🏗️ Architecture

```text
Communication Input
        │
        ▼
┌─────────────────────┐
│   AI Gmail Triage   │
│       Agent         │
└─────────┬───────────┘
          │
          ▼
   Context Analysis
          │
          ▼
   Priority Detection
          │
     ┌────┴─────┐
     ▼          ▼
 Summarize   Security
     │        Analysis
     │          │
     └────┬─────┘
          ▼
   Action Extraction
          │
          ▼
    Smart Reply
     Generation
          │
          ▼
 Intelligent Gmail
     Experience
```

---

# ⚙️ Technology Stack

- **Python**
- **LangChain**
- **LangGraph**
- **Ollama**
- **Qwen3**
- **Jupyter Notebook**

---

# 🖥️ AMD Compute

This project was developed and executed in the AMD-provided Jupyter environment for the **AMD AgentForge Hackathon 2026**.

The AI inference workflow uses:

- **AMD Ryzen AI MAX+ PRO 395**
- **AMD Radeon 8060S**
- **Ollama**
- **Qwen3 model family**

The objective is to perform AI inference locally on the provided AMD compute environment rather than depending on an external AI API for model inference.

---

# 🔄 Agent Workflow

```text
Input Communication
        ↓
Message Understanding
        ↓
Context Analysis
        ↓
Priority & Intent Detection
        ↓
Information Extraction
        ↓
Security Analysis
        ↓
Response Generation
        ↓
Final AI Result
```

The workflow is implemented using an agentic architecture with **LangGraph and LangChain**, allowing multiple processing steps to work together instead of treating the system as a simple single-prompt chatbot.

---

# 📓 Running the Project

## 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Gmail-Triage-Agent.git
```

```bash
cd AI-Gmail-Triage-Agent
```

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

## 3. Start Ollama

Make sure Ollama is installed and running in the AMD environment.

## 4. Download the required Qwen3 model

Use the Qwen3 model configured for the project.

Example:

```bash
ollama pull qwen3
```

> The exact model tag may differ depending on the model available in the AMD environment.

## 5. Open the notebook

Open:

```text
AI_Gmail_Triage_Agent.ipynb
```

Run the notebook cells sequentially.

---

# 📂 Repository Structure

```text
AI-Gmail-Triage-Agent/
│
├── README.md
├── requirements.txt
│
├── AI_Gmail_Triage_Agent.ipynb
│
├── src/
│   └── ...
│
├── assets/
│   ├── logo.png
│   ├── problem.png
│   └── solution.png
│
└── screenshots/
    ├── notebook.png
    └── amd_compute.png
```

---

# 🧪 Demonstration

The project demonstration shows the AI agent processing communication and producing useful outputs such as:

- Priority classification
- AI-generated summaries
- Extracted actions
- Meeting and deadline identification
- Security analysis
- Smart reply generation

The repository contains the Jupyter Notebook used for the working implementation.

---

# 📸 Screenshots

### Problem

![Problem](assets/problem.png)

### Solution

![Solution](assets/solution.png)

### AI Agent Execution

![Notebook](screenshots/notebook.png)

### AMD Compute

![AMD Compute](screenshots/amd_compute.png)

---

# 🔐 Privacy & Local AI

The project is designed around local AI inference using Ollama and the Qwen3 model family on the AMD environment.

This reduces dependence on external model APIs during inference and supports a privacy-focused architecture.

---

# 🌱 Future Scope

Possible future extensions include:

- Direct Gmail API integration
- Additional communication platform connectors
- Real-time notification synchronization
- Personalized long-term communication memory
- User-specific writing style adaptation
- Approval-based autonomous email sending
- Expanded phishing and attachment analysis
- Enterprise communication workflows

---

# 👥 Team

## Agentic Nexus

**Project:** AI Gmail Triage Agent  
**Hackathon:** AMD AgentForge Hackathon 2026  
**Track:** Build for your Community

---

# 📜 License

This project was developed as part of the AMD AgentForge Hackathon 2026.
