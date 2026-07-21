# 🚀 Career Compass — AI Career Briefing Automation

![n8n](https://img.shields.io/badge/n8n-Workflow-EA4B71?logo=n8n&logoColor=white)
![Claude AI](https://img.shields.io/badge/Claude-AI-D97757?logo=anthropic&logoColor=white)
![RSS](https://img.shields.io/badge/RSS-Feed-FFA500?logo=rss&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Integration-EA4335?logo=gmail&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-green)

An AI-powered workflow built using **n8n**, **Claude AI**, **RSS Feed**, and **Gmail** that automatically delivers a personalized career briefing every day at **5:00 PM**.

The workflow keeps users updated with the latest AI industry news while also providing career motivation and practical health tips.

---

# 📖 Project Overview

Career Compass is an intelligent automation workflow designed to improve daily learning and career growth.

Every day at **5:00 PM**, the workflow automatically:

- Fetches the latest AI industry news
- Selects the top 3 articles
- Uses Claude AI to summarize them
- Generates personalized career motivation
- Adds a practical health tip
- Sends everything directly to Gmail

This removes the need to manually search for industry news while keeping professionals informed and motivated.

---

# ✨ Features

- ⏰ Daily 5 PM Automated Execution
- 📰 AI Industry News via RSS Feed
- 🤖 Claude AI Powered Summarization
- 💼 Personalized Career Motivation
- 💪 Daily Health Tip
- 📧 Automatic Gmail Delivery
- ⚡ Fully Automated using n8n
- 🔄 Modular Workflow Design

---

# 🛠️ Technology Stack

## Automation

- n8n

## AI

- Claude AI (Anthropic)

## Data Source

- RSS Feed

## Email

- Gmail

---

---

# 🏗️ Workflow Architecture

```text
Schedule Trigger (5:00 PM)
          │
          ▼
      RSS Feed
          │
          ▼
   Top 3 AI Articles
          │
          ▼
      Claude AI
          │
   ┌──────┼────────┐
   ▼      ▼        ▼
AI News Motivation Health Tip
          │
          ▼
      Gmail API
          │
          ▼
        User

# 📂 Repository Structure

```text
Career_Compass_AI_Career_Briefing_Automation
│
├── workflow/
│   └── Career_Compass_Workflow.json
│
├── images/
│   ├── workflow_canvas.png
│   ├── workflow_2.png
│   └── workflow_3.png
│
├── docs/
│   └── Project_Documentation.pdf
│
├── LICENSE
└── README.md
```

---

## ⚙️ Workflow

1. Schedule Trigger runs every day at **5:00 PM**.
2. RSS Feed fetches the latest AI news.
3. The Limit node selects the top 3 articles.
4. Claude AI summarizes the articles.
5. Claude AI generates:
   - AI Industry Update
   - Career Motivation
   - Daily Health Tip
6. Gmail sends the final briefing automatically.

---

# 📸 Project Screenshots

## Complete Workflow

![Workflow](images/workflow_canvas.png)

---

## AI Agent Configuration

![AI Agent](images/workflow_2.png)

---

## Sample Output

![Output](images/workflow_3.png)

---

## 📄 Documentation

The complete project documentation, workflow explanation, setup guide, and implementation details are available in:

`docs/Project_Documentation.pdf`

---

## 🚀 Future Enhancements

- LinkedIn Job Recommendations
- Resume Improvement Suggestions
- AI Interview Questions
- Slack Integration
- Microsoft Teams Integration
- WhatsApp Notifications
- Google Calendar Integration
- Daily Coding Challenges
- Voice Assistant Support

---

## 📈 Project Outcome

- ✅ Automated daily career briefing
- ✅ Reduced manual effort
- ✅ Personalized AI-generated insights
- ✅ Improved awareness of AI industry trends
- ✅ Practical motivation and health guidance

---

## 👨‍💻 Author

**Santhosh S.**

- GitHub: https://github.com/santhu1711
- LinkedIn: https://www.linkedin.com/in/santhosh17/
