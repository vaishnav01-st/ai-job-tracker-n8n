# 🤖 AI-Powered Job Tracker using n8n

An automated workflow that fetches jobs daily, 
scores them using AI, and sends email digests!

## 🛠️ Tools Used
- n8n (Workflow Automation)
- JSearch API (Job Data)
- Groq + LLaMA 3.3 (AI Filtering)
- Airtable (Job Tracker)
- Gmail (Daily Digest)

## ⚙️ How It Works
1. Fetches 30+ jobs daily at 8 AM
2. AI scores each job for relevance (1-10)
3. Saves relevant jobs to Airtable
4. Sends separate emails for Remote & Onsite jobs

## 🚀 Setup Instructions
1. Import the workflow JSON into n8n
2. Add your API keys:
   - JSearch API (RapidAPI)
   - Groq API
   - Airtable Token
3. Connect your Gmail account
4. Activate the workflow!






