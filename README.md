#### **📢 Liputan6 News Scraper**  
🚀 *A Python web scraper to extract news headlines and links from Liputan6 using BeautifulSoup & Requests.*  

### 📖 **Table of Contents**  
1. [About the Project](#about-the-project)  
2. [Features](#features)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Example Output](#example-output)  
6. [License](#license)  

---

## 📝 **About the Project**  
This project is a simple **web scraper** that extracts the latest **news headlines** from [Liputan6](https://www.liputan6.com/).  
It utilizes **BeautifulSoup** for parsing HTML and `requests` for fetching web content.  

---

## ✨ **Features**  
✅ Fetches the latest news headlines 📢  
✅ Extracts **titles and links** from the homepage 🔗  
✅ Formats the output as **a table using `tabulate`** 🗂️  
✅ Easy to run and modify ⚡  

---

## ⚙ **Installation**  
First, make sure you have **Python 3+** installed. Then, install the required libraries:  

```bash
pip install requests beautifulsoup4 tabulate
```

---

## 🚀 **Usage**  
Clone the repository and run the script:  

```bash
git clone https://github.com/yourusername/liputan6-news-scraper.git  
cd liputan6-news-scraper  
python liputan6_scraper.py  
```

If using **Jupyter Notebook**, open the `.ipynb` file and execute the cells sequentially.

---

## 📌 **Example Output**  
```
+---------------------------------+-------------------------------------------+
| Title                           | Link                                      |
+---------------------------------+-------------------------------------------+
| "Breaking News: ..."            | https://www.liputan6.com/...             |
| "Tech Trends in 2025"           | https://www.liputan6.com/...             |
+---------------------------------+-------------------------------------------+
