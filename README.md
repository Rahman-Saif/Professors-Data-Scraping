# Professors Data Scraping

A Python-based web scraping project designed to collect and structure **academic and professional information about university professors** from publicly available webpages.

The project uses **BeautifulSoup and Pandas** to extract professor profiles, academic backgrounds, publications, and other relevant information. It also explores scraping additional research information from **Google Scholar**.

## 🚀 Project Overview

Academic profiles often contain valuable information distributed across different sections of university websites and research platforms.

This project demonstrates how web scraping can be used to automatically collect and organize this information into a structured dataset.

The project focuses on extracting:

* Professor profile information
* Academic background
* Research interests
* Publications
* Professional information
* Google Scholar information

## 🛠️ Technologies Used

* **Python**
* **BeautifulSoup** – HTML parsing and web scraping
* **Requests** – Sending HTTP requests
* **Pandas** – Data processing and DataFrame creation

## 📊 Features

### Professor Profile Scraping

The project extracts publicly available information from an individual professor's academic profile, such as:

* Name
* Designation
* Department
* University
* Profile information
* Research interests

### 🎓 Academic Background

The scraper extracts academic background information where available, including:

* Degrees
* Universities
* Academic qualifications
* Educational history

### 📚 Publication Extraction

The project extracts publication-related information from the professor's webpage, such as:

* Publication titles
* Publication details
* Publication year
* Research-related information

The collected information is then converted into a structured **Pandas DataFrame**.

### 🔎 Google Scholar Exploration

As an additional part of the project, I explored scraping information from **Google Scholar** to retrieve publicly available academic metrics and publication information.

This part demonstrates the challenges involved in scraping websites with more complex structures and restrictions.

## 🔄 Workflow

```text
Professor's Academic Profile
          ↓
       Requests
          ↓
    HTML Response
          ↓
     BeautifulSoup
          ↓
    Data Extraction
          ↓
        Pandas
          ↓
     DataFrame
          ↓
   Data Analysis
```


## 🎯 Learning Outcomes

This project helped me explore:

* Web scraping with Python
* HTML parsing using BeautifulSoup
* HTTP requests
* Extracting information from structured webpages
* Handling different webpage layouts
* Converting unstructured web content into structured datasets
* Working with Pandas DataFrames
* Academic profile and publication data extraction
* Exploring Google Scholar scraping challenges

## ⚠️ Disclaimer

This project is intended for **educational and research purposes**.

When scraping websites, users should respect the website's:

* Terms of service
* `robots.txt`
* Rate limits
* Access restrictions
* Copyright and data-use policies

Only publicly available information should be collected and used responsibly.

## 🔮 Future Improvements

* Support multiple professor profiles automatically
* Build a reusable professor-profile scraper
* Extract publications from multiple academic sources
* Add Google Scholar citation metrics where permitted
* Export results to CSV/Excel
* Build an academic profile search system
* Store professor and publication information in a database
* Add automated data cleaning and deduplication

## 👨‍💻 Author

**Rahman Saif**

This project was developed as a practical exploration of **Python web scraping, data extraction, and academic data analysis**.
