# Web Scraping Task with Form

## 📌 Overview
This project demonstrates a web scraping task that extracts various types of data from a webpage containing a form.  
It collects text data, table data, product information, form details, media links, and featured products, then saves them into structured files.

## 🛠️ Features
- **Text Extraction** → Saved in `Extract_Text_Data.csv` (34 rows)
- **Table Extraction** → Saved in `Extract_Table_Data.csv` (3 rows)
- **Product Information** → Saved in `Product_Information.json` (4 items)
- **Form Details** → Saved in `Form_Details.json` (5 fields)
- **Media Links** → Saved in `Media_Links.json` (YouTube video link)
- **Featured Products** → Saved in `Featured_Products.json` (1 item)

## 📂 Project Structure
📁 web-scraping-task
│-- 📄 scraping_notebook.ipynb
│-- 📄 Extract_Text_Data.csv
│-- 📄 Extract_Table_Data.csv
│-- 📄 Product_Information.json
│-- 📄 Form_Details.json
│-- 📄 Media_Links.json
│-- 📄 Featured_Products.json
│-- 📄 README.md



## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas

2.Open and run the Jupyter Notebook:
jupyter notebook scraping_notebook.ipynb

