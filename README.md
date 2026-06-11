# ttripleai-ai-agents

Autonomous B2B workflows and AI agents built with n8n, LangChain, and OCR. Official repository of @ttripleai.

## @ttripleai - Autonomous Business Ecosystems 🚀

Welcome to the official **@ttripleai** repository. In this space, I present the architecture of my B2B automation ecosystems, designed to transform manual processes into high-performance autonomous workflows.

As an Artificial Intelligence Engineering student (UNL, Argentina), my focus is on creating custom algorithmic logic, integrating AI agents with memory, computer vision (OCR), and real-time data synchronization.

---

## 📂 Featured Projects

### 1. 🏥 KineCust - Smart Management for Healthcare Centers
*(File: `Workflow_Kine_BETA.json`)* An advanced reception and triage system for medical clinics.
* **Semantic Triage:** The agent analyzes the patient's symptoms and automatically assigns the necessary resource (Magnetotherapy/Gym).
* **Constraint Management:** Controls maximum capacity per time slot by reading directly from Google Calendar.
* **Health Insurance Integration:** Checks requirements and co-pays in external databases before confirming appointments.
* **Medical Order OCR:** Processes images of medical prescriptions to autonomously extract diagnoses and session counts.

### 2. 💰 @ttripleai Finance - 24/7 Payment Verification
*(File: `Workflow_Inmobiliaria_BETA.json`)* An ecosystem designed for automated banking and administrative reconciliation.
* **Omnichannel Auditing:** Monitors inputs across Gmail and WhatsApp simultaneously.
* **Computer Vision (OCR):** Analyzes payment receipts (PDF/JPG) to extract amounts, dates, and transaction numbers with high precision.
* **Automated Reconciliation:** Cross-references data with Google Sheets to validate transactions and update debt statuses.

### 3. 🍔 BurgerMood - Transactional Sales Agent
*(File: `Workflow_BurgerMood.json`)* Gastronomic e-commerce workflow with strict data validation.
* **Knowledge Base:** The agent queries prices and stock in real-time from Google Sheets to prevent hallucinations.
* **Lead Capture:** Collects shipping data, preferences, and payment methods, sending the ready-to-cook order directly to the management system.

### 4. 🧠 Personal Executive Secretary
*(File: `SecretarioFacu.json`)* High-availability private assistant for productivity management.
* **Hybrid Interface:** Capable of transcribing and executing commands from WhatsApp voice notes or text.
* **Calendar and Email Management:** Creation and modification of complex events and reading of key emails.
* **Long-Term Memory:** Implementation of memory nodes to maintain the context of pending tasks.

---

## 🛠️ Tech Stack

* **Orchestration:** n8n (Self-Hosted Architecture on a VPS with Docker).
* **Artificial Intelligence:** Google Gemini 2.5 Flash / OpenAI, LangChain Agents.
* **Integrations:** WhatsApp Business API, Gmail API, Google Calendar API, Google Sheets API.
* **Custom Logic:** Implementation of JavaScript code nodes and regular expressions (Regex) for data cleaning.

---
*© 2026 @ttripleai - Innovative Engineering Solutions*
