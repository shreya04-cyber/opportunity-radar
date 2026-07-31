# 🚀 Opportunity Radar

> **An AI Career Agent that protects your attention by deciding which opportunities are worth interrupting you for.**

## 📌 Overview

Every day, students and professionals receive dozens of emails, Telegram messages, newsletters, and community posts about internships, hackathons, and career opportunities.

Most are ignored.
Some are irrelevant.
A few are life-changing—but they get buried.

**Opportunity Radar** acts as an AI Chief of Staff for your career.

Instead of forwarding every opportunity, it reads incoming opportunities, evaluates them against your profile, explains its reasoning, and only interrupts you when something truly deserves your attention.

---

## ✨ Problem

Finding opportunities isn't difficult.

Finding the **right** opportunity before it's too late is.

Current platforms overwhelm users with endless listings and notifications. Important opportunities are often lost among hundreds of irrelevant messages.

---

## 💡 Solution

Opportunity Radar filters the noise.

The AI:

- 📥 Reads incoming opportunities
- 🧠 Understands the content using Gemini
- 🎯 Matches opportunities with your profile
- ⚡ Decides whether to interrupt you
- 💬 Explains every decision in natural language
- ⏰ Reminds you before important deadlines

Instead of:

> "Here are 50 opportunities."

It says:

> "I checked 84 emails today and ignored 79 because they didn't match your interests. This hackathon matches your AI experience and closes tomorrow, so I thought it was worth interrupting you."

---

# 🤖 AI Agent Workflow

### 🔎 Scout Agent

Collects opportunities from supported channels.

Examples:

- Gmail
- Telegram
- Caspian

---

### 🧠 Gatekeeper Agent

Analyzes each opportunity.

Extracts:

- Title
- Type
- Deadline
- Registration Link

Then decides:

- Interrupt
- Watch
- Ignore

---

### 🎯 Evaluation Agent

Compares opportunities with the user's:

- Skills
- Interests
- Career goals
- Experience

Returns:

- Match Score
- AI Reasoning
- Recommended Action

---

### ⏰ Reminder Agent

Monitors saved opportunities.

If a deadline approaches, it reminds the user before it's too late.

---

# 🖥️ Features

- AI-powered opportunity analysis
- Personalized career matching
- Smart interruption logic
- Explainable AI reasoning
- Deadline reminders
- Telegram notifications
- Gmail integration
- Caspian multi-channel support

---

# 🛠️ Tech Stack

### Frontend

- React
- TypeScript
- Tailwind CSS

### Backend

- FastAPI
- Python

### AI

- Google Gemini API

### Database

- SQLite

### Communication

- Gmail API
- Telegram Bot API
- Caspian SDK

---

# 📂 Project Structure

```
opportunity-radar/
│
├── backend/
│   ├── app/
│   │   ├── agents/
│   │   ├── api/
│   │   ├── db/
│   │   ├── integrations/
│   │   ├── services/
│   │   └── main.py
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.tsx
│   └── package.json
│
└── README.md
```

---

# 🚦 How It Works

```text
Incoming Opportunity
        │
        ▼
 Scout Agent
        │
        ▼
 Gatekeeper Agent
        │
        ▼
 Evaluation Agent
        │
 ┌──────┴──────┐
 │             │
Interrupt    Ignore
 │             │
 ▼             ▼
Telegram     Archive
 │
 ▼
Reminder Agent
```

---

# 🎯 MVP Scope

The first version focuses on:

- Hackathons
- Internships

Future versions can support:

- Scholarships
- Fellowships
- Jobs
- Conferences
- Competitions

---

# 🌟 Why It's Different

Most recommendation systems tell you **what exists**.

Opportunity Radar decides **what deserves your attention**.

The AI doesn't simply notify—it makes decisions, explains its reasoning, and follows up before important deadlines.

---

# 🚀 Future Improvements

- Discord Integration
- WhatsApp Integration
- LinkedIn Opportunities
- Daily AI Career Briefings
- Resume-based Matching
- Calendar Integration
- AI Auto-Apply Suggestions

---

# 👩‍💻 Built For

Students

Early-career professionals

Developers

Hackathon enthusiasts

---

# 📄 License

MIT License
