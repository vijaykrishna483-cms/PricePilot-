🤖 Project Overview
Built with Next.js and Bright Data's Web Unlocker, this app lets users track e-commerce products in real time. It alerts users when a product’s price drops or goes out of stock—ideal for buyers and competitors. All scraping and updates are handled automatically via cron jobs.


⚙️ Tech Stack
Next.js

Bright Data

Cheerio

MongoDB

Nodemailer

Tailwind CSS + Headless UI

🔋 Key Features
🎯 Product Tracking: Scrape and monitor Amazon products via link input

📩 Email Alerts: Get notified for price drops or stock updates

🛠️ Cron Jobs: Automate scraping and notifications

🖼️ UI Highlights: Carousel, product cards, and tracking modals

📦 Reusable Codebase: Modular structure for scalability

🚀 Quick Start
1. Clone & Install
bash
Copy
Edit
git clone https://github.com/vijaykrishna483-cms/PricePilot-
npm install
2. Environment Variables
Create a .env file in the root:

env
Copy
Edit
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

MONGODB_URI=

EMAIL_USER=
EMAIL_PASS=
3. Run Dev Server
bash
Copy
Edit
npm run dev
Visit http://localhost:3000
