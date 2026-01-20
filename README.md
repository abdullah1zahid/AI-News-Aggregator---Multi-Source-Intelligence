# 📰 AI News Aggregator - Multi-Source Intelligence

**An intelligent, fully automated news delivery agent acting as a personal news anchor.**
This project aggregates news from global RSS feeds, utilizes **GPT-4o** to summarize and translate them into a bilingual (Urdu/English) "Daily Digest", and delivers it directly to WhatsApp using the **Meta Cloud API**.

---

## 🚀 Key Features
- **🤖 Smart Aggregation:** Fetches real-time news from **Dawn, BBC, and TechCrunch** RSS feeds.
- **🧠 AI Power:** Uses **OpenAI (GPT-4o)** to summarize content, translate it into Urdu/English, and format it with emojis.
- **🇵🇰 Localized Timing:** Automatically detects and formats date/time for **Pakistan Standard Time (PKT)**.
- **🛡️ Error Handling:** Intelligent fallback mechanism ensures the bot reports "No news available" instead of crashing if feeds are empty.
- **📲 Direct Delivery:** Sends a beautifully formatted message directly to the user's WhatsApp via **Meta Cloud API**.

## 🛠️ Tech Stack
- **Workflow Automation:** n8n (Self-hosted on VPS)
- **AI Model:** OpenAI GPT-4o Mini
- **Messaging:** WhatsApp Business Cloud API
- **Scripting:** JavaScript (Node.js) for advanced data parsing
- **Version Control:** Git & GitHub

## 📂 How to Use
1. **Download:** Get the `AI News Aggregator - Multi-Source Intelligence.json` file from this repository.
2. **Import:** Open your n8n dashboard, go to **Workflows**, and click **"Import from File"**.
3. **Configure:** Add your own **OpenAI API Key** and **Meta WhatsApp Credentials**.
4. **Activate:** Turn on the workflow to start receiving daily updates at 7:00 AM!

---

## 👨‍💻 Author
**Abdullah Zahid**
*Computer Science & Mathematics Educator*
*Passionate about AI & Automation*
