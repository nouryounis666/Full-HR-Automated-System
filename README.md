# 🤖 NourFlow HR | Enterprise AI & Automation Portfolio

An enterprise-grade, end-to-end HR automation and intelligent candidate screening platform built using **n8n**, **Docker**, **Oracle Cloud**, and multi-agent **LLMs (Gemini & Groq)**.

🌐 **[View Live Portfolio Website & Demo](https://nouryounis666.github.io/Full-HR-Automated-System/)**

---

## 🌟 Overview
NourFlow HR streamlines human resources operations by automating candidate intake, intelligent CV evaluation and scoring, error monitoring, and policy inquiries through a secure Retrieval-Augmented Generation (RAG) assistant.

---

## ⚙️ The 5 Deployed n8n Workflows

### 1. Recruitment 1 - Intake
Handles applicant submissions, validates applicant details, checks for duplicates, and securely logs records to Google Drive and Google Sheets.
![Intake Workflow](images/Intake%20Workflow.png)

### 2. Recruitment 2 - Batch Evaluation (AI Screening)
Periodically processes pending applications, extracts text from uploaded PDFs, and scores candidates using advanced AI LLM agents.
![AI Screening Workflow](images/AI%20Screening%20Workflow.png)

### 3. Recruitment 3 - Error Handler & Heartbeat
Global system monitor that catches execution failures, classifies error types, logs them to an error sheet, and triggers smart throttled alerts.
![Error Handler Workflow](images/Error%20Handler%20Workflow.png)

### 4. HR Policy Assistant (RAG + LLM)
An intelligent vector store RAG assistant that answers employee policy inquiries accurately with citation tracking.
![RAG Assistant Workflow](images/RAG%20Assistant%20Workflow.png)

### 5. Job Application Coach
Multi-agent orchestrator that reviews job descriptions and candidate CVs to generate automated coaching reports and cover letters.
![Job Coach Workflow](images/Job%20Coach%20Workflow.png)

---

## 🛠️ Tech Stack & Architecture
* **Orchestration:** n8n (Self-hosted on Docker via WSL2)
* **Cloud & Hosting:** Oracle Cloud Infrastructure & DuckDNS
* **AI & LLMs:** Google Gemini API, Groq LLM, Vector Embeddings
* **Storage & Databases:** Google Drive, Google Sheets
* **Frontend Portfolio:** HTML5, Tailwind CSS, JavaScript

---

## 📂 Repository Structure
* `index.html` — The main interactive portfolio dashboard.
* `workflows/` — Sanitized and cleaned n8n workflow JSON exports.
* `images/` — Architecture preview screenshots.

---

## 👨‍💻 Author
Built by **Nour Tamer** — Full Stack .NET Developer & AI Automation Specialist.
