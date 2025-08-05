# Custom-RAG-WebSearch-Agent

# Web-Based Retrieval-Augmented Generation (RAG) Agent

This project is a web-driven RAG pipeline that combines Google Custom Search, BeautifulSoup-based web scraping, and a lightweight QA model (e.g., fine-tuned RoBERTa or similar) to extract structured information from unstructured web content. Originally designed to extract homicide statistics and inflation-related figures, the system is generalizable to any domain-specific information extraction task from publicly available articles.

---

##  Features

- 🔎 Retrieve news articles using Google Custom Search API  
- 📰 Scrape and clean full-text news content from URLs  
- 🧠 Apply a QA-capable LLM to extract specific answers (e.g., homicide count, dates, statistics)  
- 📅 Extract metadata like publication or last-update dates from HTML  
- 📊 Save everything into a structured DataFrame (headline, link, content, extracted answer, date)

---

## 📦 Tech Stack

- **Python 3.10+**
- `requests` – For HTTP requests  
- `BeautifulSoup` – For scraping and parsing HTML  
- `pandas` – To store the final results  
- **LLM QA Model** – Hugging Face models like `deepset/roberta-base-squad2` or any fine-tuned QA model  
- **Google Custom Search API** – For retrieving relevant links  

---

## ⚙️ Setup & Usage

### 1. 🔑 Get Google API Key & CSE ID
- Sign up for [Google Custom Search](https://programmablesearchengine.google.com/)  
- Generate your **API Key** and **CSE ID**

### 2. 🐍 Install Dependencies

```bash
pip install requests beautifulsoup4 pandas transformers

👨‍💻 Author

Developed by Md. Nafis Tahmid Akhand.
Lecturer & Researcher | Data Science | Computer Vision | NLP | AI



