# 📰 News Update Agent – n8n Automation

## Overview

**News Update Agent** is an automated n8n workflow that delivers a personalized morning news summary directly to your email.

Every day at **8:00 AM**, the agent:
- Fetches the latest news from a News API  
- Extracts relevant articles  
- Generates a concise summary highlighting key points  
- Filters content based on user preferences  
- Sends a clean, formatted email update  

---

## Workflow

1. **Cron Trigger (8:00 AM daily)**  
2. Fetch latest headlines from News API  
3. Filter articles based on user-defined topics  
4. Generate AI-powered summary (key highlights)  
5. Format structured email content  
6. Send news summary via email  

---

## Features

- ⏰ Scheduled daily execution (8 AM)  
- 🌍 Latest news fetching via API  
- 🎯 Preference-based filtering (topics, categories, keywords)  
- 🧠 AI-generated concise summaries  
- 📌 Key-point highlighting  
- 📧 Automated email delivery  
- 🔐 Fully customizable workflow  

---

## Tech Stack

- n8n  
- News API  
- OpenAI / GPT (for summarization)  
- Gmail

---

## Example Output Structure

**Subject:** Your Morning News Brief – [Date]

- 📰 Headline 1  
  - Key highlight 1  
  - Key highlight 2  

- 📰 Headline 2  
  - Key highlight 1  
  - Key highlight 2  

---

## Use Cases

- Personalized daily news digest  
- Industry-specific updates (AI, Cybersecurity, Finance, etc.)  
- Business intelligence monitoring  
- Trend tracking  
