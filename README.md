# n8n-freelance-autopilot
AI-powered freelance job hunting system built with n8n. Automatically finds jobs, scores them with AI, generates proposals in 3 languages, and sends Telegram alerts. Self-hosted on Raspberry Pi.
# 🤖 n8n Freelance Autopilot

AI-powered system that hunts freelance jobs 24/7 and generates proposals automatically.

## 🚀 What it does

- **Finds jobs** every 30 minutes from Google, Upwork, French market
- **AI scoring** 1-10 for each job (filters full-time, US-only, low budget)
- **Generates proposals** in 3 languages (EN, RU, FR) with risk assessment
- **Telegram alerts** with job details and AI analysis
- **CRM** to track clients and follow-ups
- **Market Intelligence** daily reports

## 🛠 Tech Stack

- **n8n** — workflow orchestration (self-hosted)
- **Raspberry Pi 5** — runs 24/7
- **Docker** — containerization
- **Supabase** — database
- **Groq (Llama 3.1)** — AI analysis and proposal generation
- **SerpAPI** — job search
- **Apify** — Upwork scraping
- **Telegram Bot API** — alerts and commands
- **Cloudflare Tunnel** — HTTPS access

## 📱 Telegram Bot Commands

| Command | Description |
|---------|-------------|
| `/start` | Show menu |
| `/jobs` | Latest found jobs |
| `/upwork` | Search Upwork directly |
| `/malt` | French market jobs |
| `/clients` | CRM clients list |
| `/add Name Company email` | Add client |
| `/dashboard` | Personal stats |
| `/stats` | Daily report |
| `/learn [skill]` | Learning roadmap |
| Send URL | Generate proposal |

## 📊 Workflows

1. **Job Discovery** — searches multiple sources every 30 min
2. **Proposal Generator** — AI proposals + risk assessment
3. **Follow Up Reminders** — daily client follow-up alerts
4. **Market Intelligence** — daily market report
5. **Lead Generation** — weekly proactive lead search
6. **Trend Analysis** — weekly automation trends report

## Monthly Cost

| Service | Cost |
|---------|------|
| SerpAPI | $0 (250 free) |
| Groq | $0 (free) |
| Supabase | $0 (free tier) |
| Apify | $20 credit |
| Raspberry Pi | One-time ~$35 |
| **Total** | **~$0-20/month** |

## 🔧 Built with

n8n • Docker • Raspberry Pi • Supabase • Groq • Telegram • Cloudflare
