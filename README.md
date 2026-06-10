n8n Freelance Autopilot 🤖

AI-powered job hunting system that finds freelance jobs 24/7, scores them, generates proposals in 3 languages, and sends the best ones to your Telegram — while you sleep.


What it does

🔍 Scans Upwork, Malt, and Freelancer every 30 minutes
🧠 Scores each job 0–100 with AI based on your profile
✍️ Generates proposals in English, French, and German
📱 Sends the best jobs to Telegram with inline A/B buttons
📊 Tracks which proposal style gets more replies
⏰ Reminds you to follow up after 3 days
📈 Reports daily stats and weekly market trends


7 Workflows included
#WorkflowSchedule01Job DiscoveryEvery 30 min02Proposal Generator (A/B)On new job03Follow-up RemindersEvery 3 days04CRM via TelegramOn demand05Market IntelligenceDaily06Trend AnalysisWeekly07Lead GenerationWeekly

Tech stack

n8n — self-hosted workflow automation
Groq API (Llama 3.1) — AI scoring and proposal generation
Supabase — database and deduplication
SerpAPI — job board search
Apify — Upwork scraping
Telegram Bot API — alerts and commands
Docker — containerization
Cloudflare Tunnel — HTTPS webhooks

Running cost: ~$5/month in API calls. No SaaS fees.

Telegram bot commands
/jobs     — show latest jobs found
/stats    — dashboard with your stats
/learn    — weekly market intelligence report
/clients  — manage your client list

What's in this repo
This repository contains sanitized workflow JSON files for preview purposes.
All sensitive fields (API keys, tokens, chat IDs) have been replaced with placeholders like YOUR_GROQ_API_KEY.
To get the full working setup including:

✅ Pre-configured workflow files
✅ Step-by-step Setup Guide PDF
✅ Raspberry Pi / VPS deployment instructions
✅ All API connection guides

👉 Get it on Gumroad — €15 Early Access

Requirements

Raspberry Pi 3/4, VPS, or any always-on device
Docker + Docker Compose
Groq API key (free)
SerpAPI key (100 free searches/month)
Apify token (free tier)
Supabase project (free)
Telegram bot token


More info
🌐 Landing page: n8n-freelance-autopilot.netlify.app
🛒 Get the full package: bezruchko7.gumroad.com/l/iyhuvl
📧 Contact: ihorbezruchko5@gmail.com

Built by a 17-year-old IT student from Luxembourg 🇱🇺
