# Interactive REST API Data Scraper & File Automation Tool

A lightweight Python data pipeline that fetches live JSON payloads from external REST APIs, provides interactive CLI keyword filtering, and automates structured local report generation with full exception handling.

## Features
* **REST API Integration:** Connects to public HTTP endpoints using `requests` with custom headers and network timeouts.
* **Dynamic CLI Search:** Filters raw JSON payloads based on user-defined search parameters (city or company).
* **Automated File Output:** Writes clean, formatted report summaries directly to disk.
* **Robust Error Handling:** Protects against network timeouts, HTTP errors (`403`, `404`), and file I/O failures.

## Prerequisites
* Python 3.x
* `requests` library

Install dependencies:
```bash
pip install requests
