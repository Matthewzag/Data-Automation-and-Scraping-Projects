# Data Automation and Scraping Projects

## 📖 **Project Overview**

This repository contains two Python-based projects demonstrating expertise in data extraction and automation:
1. **Amazon Web Scraper**: A Python tool designed to monitor product prices on Amazon and alert users of price drops.
2. **API Data Automation**: A Python script to automate API data extraction, appending new data seamlessly, and managing workflows efficiently.

---

## 📂 **Project Descriptions**

### 1. **Amazon Web Scraper**
**Objective**:  
Track Amazon product prices and notify users when prices drop below a target threshold.  

**Key Features**:
- Scrapes product details, including price, title, and availability, using **BeautifulSoup**.
- Automates daily data extraction with scheduled tasks.
- Sends email alerts for price drops using the **smtplib** library.

**Technologies Used**:
- Python  
- BeautifulSoup  
- Requests  
- smtplib (for email notifications)  
- pandas (for data storage and manipulation)

---

### 2. **API Data Automation**
**Objective**:  
Automate the process of extracting data from APIs, appending it to existing datasets, and ensuring data consistency.  

**Key Features**:
- Connects to APIs to extract structured JSON data.
- Appends new data to an existing dataset, ensuring no duplicates.
- Includes error handling for failed API calls or network interruptions.
- Supports scheduling for recurring data extractions.

**Technologies Used**:
- Python  
- Requests (API calls)  
- pandas (data management)  
- os and datetime (file management and scheduling)

---

## 🛠️ **Setup and Installation**

1. **Clone this repository**:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```

2. **Install Dependencies**:  
   Make sure Python is installed, then install the required libraries:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:  
   - For the Amazon Scraper:
     - Add your email credentials for sending notifications.  
   - For the API Automation:
     - Set your API key in a `.env` file or in the script directly.

4. **Run the Scripts**:
   - **Amazon Web Scraper**:  
     ```bash
     python amazon_scraper.py
     ```
   - **API Data Automation**:  
     ```bash
     python api_automation.py
     ```

---

## 🔍 **Key Learnings**

- Mastered web scraping techniques to extract real-time data from dynamic websites.
- Developed robust error handling and automation workflows for scalable data pipelines.
- Improved proficiency in working with APIs and integrating them into analytical workflows.

---

## 🚀 **Future Enhancements**

1. Add a user interface for easier interaction with both scripts.
2. Use cloud services for deployment (e.g., AWS Lambda, Google Cloud Functions).
3. Implement advanced scheduling with tools like Apache Airflow or Cron jobs.
4. Expand the Amazon scraper to include multiple e-commerce websites.

---

## 📫 **Contact**

Feel free to reach out for collaboration or inquiries:  
**Matthew Zagada**  
- Email: mseanz@hotmail.com  
- [LinkedIn](https://www.linkedin.com/in/matthew-zagada-772252292)
