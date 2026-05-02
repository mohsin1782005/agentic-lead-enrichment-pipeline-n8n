# AI-Driven Lead Enrichment Pipeline 🚀

A modular automation system that transforms raw lead data into high-priority sales opportunities using Agentic AI and custom scoring logic.

## 🛠️ Tech Stack
* **Orchestration:** n8n (iPaaS)
* **LLM Engine:** Google Gemini Pro
* **Logic:** Node.js / JavaScript
* **Database:** Google Sheets API
* **Ingestion:** Webhook / REST API

## 📋 Features
* **Custom Scoring Engine:** A JavaScript-based logic layer that evaluates leads based on company size, industry, and source.
* **AI Decision Layer:** Utilizes Gemini Pro to analyze lead context and draft personalized, two-sentence outreach messages.
* **Conditional Routing:** Automatically filters low-priority leads ("Do Not Contact") to keep your database clean.
* **Real-Time Sync:** Appends enriched data to Google Sheets instantly for sales team action.

## 🚀 Getting Started

### Prerequisites
* An **n8n** instance (Cloud or Desktop).
* A **Google Gemini API Key**.
* A Google Cloud Console project with **Google Sheets API** enabled.

### Installation
1. **Import Workflow:** Download the `workflow.json` from this repo and import it into your n8n canvas.
2. **Configure Credentials:** 
   - Add your Gemini API key in the AI Agent node.
   - Connect your Google account in the Google Sheets node.
3. **Environment Setup:** Ensure your webhook is set to "Production" for 24/7 automation.

## 📊 Logic Visualization
![Project Infographic](watermarked_img_8425199458760296222.png)

## 📄 License
MIT License - feel free to use this for your own automation projects!
