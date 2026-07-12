<h1 align="center">🤖 AI Automation & Agent Projects</h1>

<p align="center">
  A collection of real, working automation workflows and AI agents I've built using
  <b>n8n</b>, <b>Zapier</b>, <b>Make.com</b>, and <b>Flowise</b> —
  connecting apps, AI models, and APIs to eliminate repetitive work.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Zapier-FF4A00?style=for-the-badge&logo=zapier&logoColor=white" />
  <img src="https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge&logo=make&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

---

## 👋 About

I build automation systems that connect the tools businesses already use — so the
repetitive, manual work runs on its own. Below are some of the workflows and AI agents
I've built and deployed. Each one is live and running.

**Tools I work with:** n8n · Zapier · Make.com · Flowise · Claude · Gemini · Google Workspace · Webhooks & APIs

---

## 🧠 AI Agents (n8n)

### 1. Lead Generation Agent
An AI-powered agent that receives lead data through a webhook, uses an AI model to
research and qualify the lead, and automatically appends or updates the record in a
Google Sheet — all with no manual work.

**Flow:** `Webhook → AI Agent (Claude) → Append/Update Google Sheet`
**Stack:** n8n · Anthropic Claude · Google Sheets · Webhooks

![Lead Generation Agent](Lead_Generation_Agent__n8n_.png)

---

### 2. WhatsApp AI Agent
A conversational AI agent that receives WhatsApp messages via webhook, processes them
through an AI model with memory, and responds intelligently in real time — around the clock.

**Flow:** `Webhook → Chat Trigger → AI Agent (Gemini + Claude) → Respond to Webhook`
**Stack:** n8n · Google Gemini · Anthropic Claude · Memory · Webhooks

![WhatsApp AI Agent](WhatsApp_AI_Agent__n8n_.png)

---

### 3. Content Writer Agent
An on-demand content generation agent. Send it a request via webhook and the AI agent
produces blog posts, captions, or marketing copy automatically.

**Flow:** `Webhook → AI Agent (Claude) → Generated Content`
**Stack:** n8n · Anthropic Claude · Webhooks

![Content Writer Agent](Content_Writer_Agent__n8n_.png)

---

### 4. n8n → Flowise Integration
Connects an n8n workflow directly to a deployed Flowise RAG chatbot through an HTTP
request — letting the automation trigger the AI chatbot and use its response downstream.

**Flow:** `Manual Trigger → HTTP Request (POST to Flowise API)`
**Stack:** n8n · Flowise · REST API

![n8n Flowise Integration](n8n___Flowise_Integration.png)

---

## ⚙️ Automation Workflows

### 5. Gmail → Google Sheets (Zapier)
Automatically logs every incoming email into a Google Sheet — capturing the sender,
subject, date, and body. Runs continuously in the background.

**Flow:** `Gmail (new email) → Google Sheets (create row)`
**Stack:** Zapier · Gmail · Google Sheets

![Zapier Gmail to Sheets](Zapier_Gmail___Sheets.png)

---

### 6. RSS → Email Alerts (Make.com)
Monitors an AI-news RSS feed and automatically emails me the moment a new article is
published — so I never miss an update. **Live and active**, with a successful execution history.

**Flow:** `RSS (watch feed) → Gmail (send email)`
**Stack:** Make.com · RSS · Gmail

![Make RSS to Email](Make_com_RSS___Email.png)

---

### 7. Gmail → Google Sheets (Make.com)
The same email-logging automation rebuilt in Make.com — demonstrating the same outcome
across a second platform. Shows a successful run history.

**Flow:** `Gmail (watch emails) → Google Sheets (add row)`
**Stack:** Make.com · Gmail · Google Sheets

![Make Gmail to Sheets](Make_com_Gmail___Sheets.png)

---

## 🔧 What These Demonstrate

- Building **AI agents** that make decisions and take actions autonomously
- Connecting apps through **webhooks, APIs, and REST requests**
- Working across **three major automation platforms** (n8n, Zapier, Make.com)
- Integrating multiple **LLMs** (Claude, Gemini) into live workflows
- Designing flows with **memory, triggers, and error-safe execution**
- Delivering the **same outcome across different tools** — choosing the right one per job

---

## 📫 Get in Touch

- **Portfolio:** [portfolio-pink-eta-84.vercel.app](https://portfolio-pink-eta-84.vercel.app)
- **Email:** asadullah541989@gmail.com
- **LinkedIn:** [linkedin.com/in/asad-ullah-b0190a236](https://www.linkedin.com/in/asad-ullah-b0190a236)

<p align="center"><i>Every workflow above is real and running. Screenshots are from my own live accounts.</i></p>
