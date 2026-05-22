# 🤖 AI Chatbot — Powered by Groq API

> Built live on [ChethanAIChronicles](https://youtube.com/@chethanaichronicles) — a YouTube channel about AI tools and development.

![Thumbnail](./groq_chatbot_youtube_thumbnail.jpg)

---

## 📺 Watch the Full Tutorial

**[Build Your Own AI Chatbot in 20 Minutes — Free, No Coding | Groq API](https://youtube.com/@chethanaichronicles)**

In this video I build this entire chatbot from scratch — step by step, no coding experience needed.

---

## ✨ What This Chatbot Does

- 💬 **Real conversations** — chat naturally with an AI assistant
- 🧠 **Full memory** — remembers everything you say in the conversation
- 🎭 **Custom personality** — change the system prompt to make any kind of bot
- ⚡ **Ultra fast** — powered by Groq's LPU chip at 500+ tokens/sec
- 🔄 **5 AI models** — switch between Llama 3.3 70B, Llama 3.1 8B, Mixtral, and more
- 📊 **Live speed stats** — see tokens/sec and response time on every message
- 🆓 **Completely free** — Groq gives 14,400 free requests per day, no credit card needed

---

## 🚀 Quick Start (Under 5 Minutes)

### Step 1 — Get your free Groq API key

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up for free — no credit card required
3. Click **API Keys** in the left sidebar
4. Click **Create API Key** → name it anything → copy it
5. Your key starts with `gsk_...`

### Step 2 — Add your API key

Open `groq_chatbot.html` and find this line near the bottom:

```js
const GROQ_API_KEY = 'YOUR-GROQ-API-KEY-HERE';
```

Replace it with your actual key:

```js
const GROQ_API_KEY = 'gsk_xxxxxxxxxxxxxxxxxxxx';
```

### Step 3 — Run it

**Option A — Simplest:**
- Double-click `groq_chatbot.html` to open in your browser
- If you see a CORS error, use Option B

**Option B — Recommended:**
1. Install [VS Code](https://code.visualstudio.com) (free)
2. Install the **Live Server** extension
3. Open `groq_chatbot.html` in VS Code
4. Right-click → **Open with Live Server**
5. Your chatbot opens in the browser automatically ✅

---

## 🛠️ Available AI Models

| Model | Speed | Best For |
|-------|-------|----------|
| `llama-3.3-70b-versatile` | Fast | Best quality answers |
| `llama-3.1-8b-instant` | Fastest | Quick responses, testing |
| `llama-4-scout-17b-16e-instruct` | Fast | Latest Llama 4 model |
| `mixtral-8x7b-32768` | Fast | Long documents, big context |
| `gemma2-9b-it` | Fast | Google's open model |

Switch between models using the dropdown in the chatbot header.

---

## 🎭 Customise the Personality

The **Personality bar** at the bottom of the chatbot lets you change the system prompt without touching any code.

**Examples to try:**

```
You are a strict fitness coach. Be firm, motivating, and specific about nutrition and exercise.
```

```
You are a patient Class 10 study tutor. Explain concepts simply with examples a student would understand.
```

```
You are Brew, the friendly AI assistant for Chethan's Coffee. Help customers with the menu and orders. Always end with a coffee emoji ☕
```

```
You are a professional business email writer. Write formal, polished emails suitable for corporate communication.
```

---

## 📁 Project Structure

```
📦 groq-ai-chatbot
 ┣ 📄 groq_chatbot.html      ← entire chatbot (HTML + CSS + JS in one file)
 ┣ 📄 README.md              ← you are here
 ┗ 🖼️  thumbnail.jpg         ← YouTube thumbnail
```

No dependencies. No npm install. No server required. Just one HTML file.

---

## ⚙️ Configuration

All settings are at the top of the `<script>` section in `groq_chatbot.html`:

```js
// ════════════════════════════════
// CONFIG — Edit these!
// ════════════════════════════════

const GROQ_API_KEY = 'YOUR-GROQ-API-KEY-HERE';  // ← your Groq key
const MODEL = 'llama-3.3-70b-versatile';          // ← default model
```

---

## 🔧 Troubleshooting

| Problem | Fix |
|---------|-----|
| Blank screen / nothing happens | Press F12 → Console tab → read the error message |
| `401 Unauthorized` | API key is wrong or has extra spaces — check it carefully |
| `CORS error` | Use VS Code Live Server instead of opening the file directly |
| Very slow responses | Switch model to `llama-3.1-8b-instant` in the dropdown |
| Text appears as boxes | Make sure `<meta charset="UTF-8">` is in the file (it already is) |
| Rate limit error | You've hit 14,400 requests/day — wait until tomorrow or upgrade |

---

## 🆚 Why Groq Instead of ChatGPT?

| | Groq (this project) | ChatGPT API |
|--|--|--|
| Speed | **500+ tokens/sec** | ~50 tokens/sec |
| Free tier | **14,400 req/day, no card** | Limited, card required |
| Models | Llama 3.3, Mixtral, Gemma | GPT-4, GPT-3.5 |
| Setup | **5 minutes** | 10+ minutes |
| Cost | **Free to start** | Pay per token |

---



---

## 📜 Groq Free Tier Limits

| Limit | Amount |
|-------|--------|
| Requests per day | 14,400 |
| Tokens per minute | 30,000 |
| Requests per minute | 30 |
| Credit card required | ❌ Never |

More than enough for building, testing, and showing your friends.

---

## 🤝 Contributing

Found a bug or want to add a feature? Feel free to:

1. Fork this repo
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Submit a pull request

---

## 📄 License

MIT License — use this however you want, personal or commercial.

---

## 🙏 Credits

- **Groq** — for the blazing fast free API ([console.groq.com](https://console.groq.com))
- **Meta** — for the open-source Llama models
- **ChethanAIChronicles** — for building and documenting this

---

<div align="center">

**If this helped you, subscribe to the channel for more AI tutorials every week.**

[![YouTube](https://img.shields.io/badge/YouTube-ChethanAIChronicles-red?style=for-the-badge&logo=youtube)](https://youtube.com/@chethanaichronicles)
[![GitHub](https://img.shields.io/badge/GitHub-Star_this_repo-black?style=for-the-badge&logo=github)](https://github.com)

*Made with ❤️ in Bengaluru, India*

</div>
