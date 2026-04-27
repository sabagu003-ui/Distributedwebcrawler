# 🕷 WebCrawlr — Distributed Web Crawler

A modern **Distributed Web Crawler** built using **Dask, BeautifulSoup, Flask, and JavaScript UI**.
It allows users to crawl multiple websites in parallel, analyze word frequencies, view real-time progress, and search crawled data — all from a clean web interface.

---

## 🚀 Features

- 🌐 Crawl multiple websites simultaneously
- ⚡ Real-time crawling dashboard (live progress tracking)
- 📊 Word frequency analysis (Top words, charts, word cloud)
- 🔎 Search engine (TF-IDF based ranking)
- 📄 PDF report generation
- 📧 Email alerts on crawl completion
- 📊 Crawl history tracking
- 🔌 Google Colab + ngrok backend integration

---

## 🛠 Tech Stack

### Backend
- Python
- Flask
- Dask (parallel processing)
- BeautifulSoup (web scraping)
- NLTK (text processing)
- Pyngrok (public URL)
- Langdetect

### Frontend
- HTML, CSS, JavaScript
- Chart.js (visualizations)
- jsPDF (PDF reports)

---

## 📂 Project Structure

📁 WebCrawlr
│── index.html          # Frontend UI
│── crawler.ipynb       # Google Colab backend
│── README.md
│── requirements.txt

---

## ⚙️ Setup Guide

### 1️⃣ Clone the Repository
git clone https://github.com/your-username/webcrawlr.git
cd webcrawlr

### 2️⃣ Open Google Colab Notebook
Upload and open the .ipynb file in Google Colab.

### 3️⃣ Install Dependencies
pip install -r requirements.txt

### 4️⃣ Run Backend (Flask + ngrok)
- Add your ngrok auth token
- Run all cells
- Copy the generated URL: https://xxxx.ngrok-free.app

### 5️⃣ Connect Frontend
- Open index.html
- Paste ngrok URL
- Click Connect

---

## 🧪 How It Works

1. Enter URLs to crawl
2. Set number of pages
3. Start crawling
4. View live logs, word frequency charts, word cloud
5. Search crawled data using TF-IDF

---

## 📄 PDF Report
Generates full report: Total pages, Word counts, Top words, History

---

## 📧 Email Alerts
- Enable email notifications
- Requires Gmail App Password setup

---

## 🔮 Future Improvements
- Database integration (MongoDB / PostgreSQL)
- Authentication system
- Deployment on cloud (AWS / Render)
- Advanced search ranking

---

## 👩‍💻 Author
Your Name

---

## ⭐ Contribute
Pull requests are welcome! If you like this project, give it a ⭐ on GitHub.
