# 🤖 AI-Powered Lead Qualification & Sales Automation

An AI-powered lead management automation built with **n8n** that automatically captures, validates, qualifies, scores, stores, and routes incoming leads.

The workflow helps businesses reduce manual lead processing and allows sales teams to focus on high-value prospects.

---

## 🚀 Workflow

```text
Lead Form (Tally)
       ↓
Data Validation
       ↓
Duplicate Check
       ↓
AI Lead Qualification
       ↓
Google Sheets
       ↓
Hot / Warm / Cold
       ↓
Telegram / Slack Notification
```

---

## ✨ Features

* 📥 Automatic lead capture
* ✅ Lead data validation
* 🔍 Duplicate lead detection
* 🤖 AI-powered lead qualification
* 🎯 Lead scoring from 0–100
* 🔥 Hot / Warm / Cold classification
* 📝 AI-generated qualification reason
* 👉 Recommended next action
* 📊 Automatic Google Sheets storage
* 🔔 Telegram & Slack notifications
* ⚡ Reduces manual lead processing

---

## 🧠 AI Qualification

The AI analyzes each lead based on:

* Budget
* Business requirement
* Buying intent
* Potential business value

It then generates:

```text
Lead Status
Lead Score
Reason
Next Action
```

### Example

```text
Status: Hot
Score: 95

Reason:
Strong budget and a clear business requirement
indicate high buying potential.

Next Action:
Contact the lead directly and schedule a discovery call.
```

---

## 🛠️ Technologies Used

* n8n
* Google Gemini
* Tally
* Google Sheets
* Telegram
* Slack
* JavaScript

---

## 📋 Example Lead

```text
Name: John Smith
Email: john@example.com
Company: Example Agency
Budget: 500
Requirement: I need an AI chatbot for my business.
```

### AI Result

```text
Status: Hot
Score: 95
Reason: Strong budget and clear business requirement.
Next Action: Contact the lead for a discovery call.
```

---

## 💼 Business Use Cases

This automation can be customized for:

* Real Estate
* Marketing Agencies
* SaaS Companies
* Consulting Businesses
* Web Development Agencies
* Digital Agencies
* Other Service-Based Businesses

The form fields and AI qualification criteria can be modified according to the business requirements.

---

## 🔧 How It Works

### 1. Lead Capture

Tally collects the lead information and sends it to the n8n webhook.

### 2. Data Validation

The workflow checks required fields such as name, email, company, budget, and requirement.

### 3. Duplicate Check

The lead's email is checked against existing records to help prevent duplicate leads.

### 4. AI Qualification

Google Gemini analyzes the lead and determines the lead quality.

### 5. Data Storage

The qualified lead is automatically stored in Google Sheets.

### 6. Lead Routing

Hot and Warm leads are routed to the appropriate notification channels.

### 7. Sales Notification

The sales team receives lead information through Telegram or Slack.

---

## 📂 Project Structure

```text
AI-Lead-Qualification-Automation/
│
├── README.md
├── workflow/
│   └── ai-lead-qualification.json
│
└── screenshots/
    ├── workflow.png
    ├── form.png
    └── execution-result.png
```

---

## 🔐 Security

Before importing or sharing this workflow:

* Remove API credentials
* Remove OAuth credentials
* Remove Telegram Bot credentials
* Remove Slack credentials
* Remove private webhook URLs/secrets
* Never commit API keys or access tokens

Use environment variables or n8n credentials for sensitive information.

---

## 🎯 Project Goal

The goal of this project is to demonstrate how AI and workflow automation can be combined to create a practical lead management system that reduces repetitive manual work and helps sales teams prioritize valuable leads.

---

## 📌 Future Improvements

Possible future upgrades:

* CRM integration
* Automated email follow-up
* Google Calendar meeting booking
* Lead nurturing sequences
* Retry & error recovery
* Rate limiting
* Advanced duplicate detection
* Database storage
* Human approval workflow
* Sales dashboard

---

## 👨‍💻 Built With

**n8n + Google Gemini + Tally + Google Sheets + Telegram + Slack**

Built as a practical AI Automation Engineering project.
