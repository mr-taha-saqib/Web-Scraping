# Web Scraping with BeautifulSoup

## 1. Objectives
This project focuses on:
- **Web Scraping Tools and Library Installation**
- **Understanding HTML Tags for Web Scraping**
- **Hands-on Practice with BeautifulSoup**
- **Hands-on Practice with Selenium**
- **Using XPath for Advanced Scraping**

---

## 2. Web Scraping Overview

### 2.1 Python Libraries for Web Scraping
The following Python libraries are commonly used for web scraping:
- **Requests**: Simple HTTP requests (e.g., `pip install requests`).
- **BeautifulSoup**: Easy-to-use but slower for large datasets.
- **Selenium**: Suitable for dynamic websites with JavaScript but slower.
- **Scrapy**: Fast and efficient for large-scale scraping projects but complex.

> In this project, we focus on **BeautifulSoup** and **Selenium** for practical exercises.

### 2.2 Components of Web Scraping
Web scraping consists of the following components:
1. **Web Crawler Module**: Automates navigation of web pages.
2. **Extractor (Parser)**: Extracts specific data points (e.g., text, links, images).
3. **Data Transformation and Cleaning Module**: Cleans and formats the extracted data.
4. **Storage Module**: Saves the data in formats such as CSV, JSON, or databases.

---

## 3. HTML Tags Overview
Web scraping requires understanding the structure of HTML:
- HTML documents are organized as a tree of **nodes**.
- Each node can represent an element, attribute, or text.
- Nodes can have **siblings**, **children**, or **parents** based on the structure.

### Key Tags for Scraping
- `<a>`: Hyperlinks (e.g., URLs).
- `<div>`: Containers or sections.
- `<p>`: Paragraphs.
- `<span>`: Inline elements.
- `<img>`: Images.
- `<ul>/<li>`: Lists.

---
