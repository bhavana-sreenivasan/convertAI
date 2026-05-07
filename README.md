# ConvertAI 
### Multilingual Voice Agent for Partner Lead Conversion
> Built for **AI for Bharat 2** Hackathon · Theme 7 — AI Voice Agent for Partner Lead Conversion

---

##  Live Demo
[bhavana-sreenivasan.github.io/convertAI](https://bhavana-sreenivasan.github.io/convertAI)

> You'll need a free Groq API key to use the demo. Get one at [console.groq.com](https://console.groq.com)

---

##  The Problem
Rupeezy loses **82% of partner leads** due to:
- No 24/7 availability
- Language barriers (Hindi / Hinglish speakers)
- Inconsistent follow-up and objection handling

---

##  The Solution
ConvertAI is a real-time AI agent that handles the full partner recruitment conversation — from opening hook to signup — autonomously, at scale, in any language.

---

##  Features

| Feature | Description |
|---|---|
|  Multilingual | Responds in English, Hindi, or Hinglish |
|  Live Lead Scoring | Real-time Hot / Warm / Cold classification (0–100) |
|  Objection Handling | Detects & resolves the 5 core objections |
|  SEBI Compliance | Flags prohibited claims instantly |
|  Post-Call Summary | Auto-generates structured call summaries |
|  Low Latency | Sub-second responses via Groq |

---

##  Conversation Script

```
Hook → Benefits → Objection Handling → CTA
```

**3 Core Benefits pitched:**
- Zero joining fee
- 100% brokerage sharing
- Daily payouts to bank account

**5 Objections handled:**
1. Already with a broker
2. Not enough contacts
3. Client support concerns
4. Trustworthiness
5. Call me later

---

##  Tech Stack

- **LLM** — LLaMA 3.3 70B via [Groq](https://groq.com) (free tier)
- **Frontend** — Vanilla HTML / CSS / JS (zero dependencies)
- **Hosting** — GitHub Pages (free)

---

##  Run Locally

No installation needed. Just open the file:

```bash
git clone https://github.com/bhavana-sreenivasan/convertAI
cd convertAI
open convertai.html   # or double-click the file
```

Enter your Groq API key when prompted and start the session.

---

##  Getting a Groq API Key

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up for free
3. Navigate to **API Keys** → **Create API Key**
4. Paste it into the ConvertAI prompt on launch

> Your key is never stored — it lives only in memory for that browser session.

---

##  Target Impact

| Metric | Value |
|---|---|
| Current conversion rate | 18% |
| Target conversion rate | 40%+ |
| Cost per call | < ₹8.40 |
| Availability | 24/7 |
| Languages supported | English, Hindi, Hinglish |

---

##  Project Structure

```
convertAI/
└── index.html      # Entire app — UI + agent logic + analytics
```

