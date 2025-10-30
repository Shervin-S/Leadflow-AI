# ⚡ LeadFlow AI

AI-powered business lead generation — from Google Maps to personalized outreach in minutes.

Generate verified leads, create smart marketing content, and manage campaigns — all in one place.

---

## ✨ Highlights

- 🗺️ **Scrape business data from Google Maps** (name, address, phone, rating, website)
- 🤖 **Generate AI-powered templates** (email & WhatsApp) using OpenAI GPT
- 📊 **Run & monitor campaigns** via a modern web dashboard
- 🧠 **Score and rank leads automatically** with AI
- 📤 **Export results** in CSV or JSON

---

## 🚀 Quick Start

### Installation

```bash
# 1️⃣ Clone the repo
git clone https://github.com/asiifdev/business-leads-ai-automation.git
cd business-leads-ai-automation

# 2️⃣ Install dependencies
npm install

# 3️⃣ Add your OpenAI API key
cp .env.example .env
# Edit .env and add your OPENAI_API_KEY
```

### Run the Dashboard

```bash
npm run web
```

Then open 👉 **http://localhost:3000**

---

## 💡 Example Usage

```bash
node index.js -q "Coffee Shop Jakarta" -l 5 -m "Boost your cafe sales with online ordering"
```

### Output Files:
- `leads_[timestamp].csv` - Scraped business data
- `email_template.txt` - AI-generated email template
- `whatsapp_template.txt` - AI-generated WhatsApp template

---

## ⚙️ Tech Stack

| Layer | Tech | Purpose |
|-------|------|---------|
| 🧩 Backend | Node.js + Express.js | REST API, routing, and task orchestration |
| 🕸️ Scraping | Puppeteer | Automates Google Maps data extraction |
| 🧠 AI | OpenAI GPT API | Generates personalized marketing content |
| 💾 Database | SQLite | Lightweight local storage for leads & campaigns |
| 🖥️ Frontend | EJS + Tailwind CSS | Clean and responsive web dashboard |
| 🔔 Realtime | Server-Sent Events (SSE) | Live progress updates and notifications |

---

## 📋 Features

### Lead Generation
- Extract business information directly from Google Maps
- Automated data validation and verification
- Bulk scraping with customizable limits

### AI-Powered Content
- Generate personalized email campaigns
- Create WhatsApp message templates
- Smart lead scoring and prioritization

### Campaign Management
- Modern web dashboard for campaign oversight
- Real-time progress tracking
- Export capabilities (CSV/JSON)

---

## 🛠️ Configuration

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_openai_api_key_here
PORT=3000
```

---

## 📖 Documentation

### CLI Commands

```bash
node index.js [options]

Options:
  -q, --query <query>      Search query for Google Maps
  -l, --limit <number>     Number of leads to scrape
  -m, --message <text>     Marketing message for template generation
```

### API Endpoints

- `GET /` - Dashboard home
- `POST /api/campaigns` - Create new campaign
- `GET /api/campaigns/:id` - Get campaign details
- `GET /api/leads` - List all leads
- `POST /api/export` - Export leads data

---

## ❤️ Why LeadFlow AI?

- 💸 **100% Free & Open Source** - No hidden costs or subscriptions
- 🌏 **Optimized for Indonesian & local businesses** - Built with local markets in mind
- 👨‍💻 **Perfect for freelancers, agencies, and marketers** - Scale your outreach effortlessly
- 🛠️ **Customizable and developer-friendly** - Easy to extend and integrate

---

## 📧 Contact

For questions or support, please open an issue on GitHub.

---

## ⭐ Support

If you find this project helpful, please consider giving it a star on GitHub!

**Built with ❤️ to make lead generation faster and smarter.**

---
