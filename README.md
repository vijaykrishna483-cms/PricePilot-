# 🤖 PricePilot

**PricePilot** is a real-time e-commerce product tracker built with **Next.js** and **Bright Data's Web Unlocker**. It notifies users when a product drops in price or goes out of stock—perfect for smart shoppers and competitive sellers. All updates are handled automatically using cron jobs.

---

## ⚙️ Tech Stack

- **Next.js**
- **Bright Data**
- **Cheerio**
- **MongoDB**
- **Nodemailer**
- **Tailwind CSS** + **Headless UI**

---

## 🔋 Key Features

- 🎯 **Product Tracking** – Scrape and monitor Amazon products via link input  
- 📩 **Email Alerts** – Get notified when prices drop or products are restocked  
- 🛠️ **Cron Jobs** – Automated background scraping and updates  
- 🖼️ **UI Highlights** – Carousel, product cards, and modals for email tracking  
- 📦 **Reusable Codebase** – Modular structure for easy scaling and maintenance

---

## 🚀 Quick Start

### 1. Clone & Install

```bash
git clone https://github.com/vijaykrishna483-cms/PricePilot.git
cd PricePilot

```

2. Environment Variables
Create a .env file in the root directory:
```bash
# Bright Data
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

# MongoDB
MONGODB_URI=

# Email (e.g. Outlook or SMTP)
EMAIL_USER=
EMAIL_PASS=
```
3. Run Development Server
bash
Copy
Edit
```bash
npm run dev
```
Visit: http://localhost:3000

