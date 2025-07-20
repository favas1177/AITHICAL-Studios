# AITHICAL-StudiosProject Name: AI Social Media Assistant for Small Business Owners

Basic Details

Team Name: AITHICAI STUDIOSTeam Members: Muhammed Favas, Sayian Jude JacobTrack: Generative AIProblem Statement:
Small business owners often struggle to maintain a consistent and engaging social media presence due to lack of time, creative resources, or technical knowledge.

Solution: An AI-powered automation system accessible via WhatsApp , Telegram and Instagram that assists small business owners in:

Creating scroll-stopping image/video/text content

Auto-responding to DMs and converting inquiries into leads



Project Description:Our project simplifies social media management using an intuitive, chat-based interface. The AI agent handles content generation, lead response, and appointment booking . This empowers non-tech-savvy business owners to grow online effortlessly.

Technical Details

Tech Stack:

Automation: n8n (Self-hosted)

Backend & Storage: Supabase (auth, DB, storage)

AI Services:

OpenAI (GPT-4o for text + vision, DALL-E / Whisper)

Google Gemini (optional, fallback)

Messaging Platforms: WhatsApp Cloud API, Instagram ,Telegram Bot

Image Hosting: Google Drive /imageBB

Languages: JavaScript (n8n Function nodes), SQL,JSON

Libraries Used:

Supabase JS SDK

OpenAI API

Webhooks & HTTP Request nodes (n8n)

Implementation Highlights:

Use perplexity to , suggests viral similar ideas to business owner

Generates AI video/image posts based on prompts

Handles image uploads (Google Drive/ImageBB)

Responds to DMs and captures leads using keyword detection + AI chat



Installation & Execution Instructions

Prerequisites:

Supabase Project

WhatsApp Business API Access

n8n self-hosted instance

Setup:

Clone this repository

git clone https://github.com/yourusername/ai-social-media-assistant.git
cd ai-social-media-assistant

Setup environment variables (rename .env.example to .env and fill in your keys):

SUPABASE_URL=...
SUPABASE_KEY=...
OPENAI_API_KEY=...
TELEGRAM_BOT_TOKEN=...

Import workflows into your n8n instance (exported JSON files inside /workflows folder)

Connect credentials for:

Supabase HTTP API

OpenAI

Google Drive or Gofile (for image hosting)

Deploy Telegram Bot / Connect WhatsApp Number

Start chatting with the bot to:

Generate content

Upload product images

Get auto-written captions

Screenshots

1. Trending Video Suggestions



2. AI-Generated Product Post



3. WhatsApp/Telegram Lead Conversation


License

This project is licensed under the MIT License. See the LICENSE file for details.

Let us know if you'd like to contribute or integrate this into your local business tools!

