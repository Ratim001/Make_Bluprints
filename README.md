# Blueprint Index for Make.com Automation Projects

Welcome to the **Make_Bluprints** repository—an organized collection of automation workflows (blueprints) designed to streamline data processing, messaging, and integrations across multiple platforms.

---

## 📋 Blueprint Summary

### Typeform-Air-Slack
**Description:** Captures responses from Typeform, stores relevant data fields in Airtable (e.g., Name, Email, Interest Level, Need), and sends Slack direct messages for notification purposes.
![Typeform-Airslack](assets/typeform_airslack.png)

### LinkedIn Email Scraper
**Description:** Monitors Google Sheets for new search keywords, triggers Apify actor to scrape LinkedIn emails, and appends the results directly back to Sheets.
![LinkedIn Email Scraper](https://drive.google.com/file/d/1xmmu4YpQMuhETh_-VyNjWWUNVajoidW2/view?usp=sharing)

### Telegram Chat ID Retrieval
**Description:** Fetches recent chat updates using Telegram Bot API and extracts unique chat IDs for direct messaging workflows.
![Get Telegram id](https://drive.google.com/file/d/1tVMu5-yymVixI5_IbqY2r_jwS6sVhxBl/view?usp=sharing)

### Student's Grade Classifier
**Description:** Filters student performance data from Google Sheets, routes grades by thresholds (e.g., "Excellent," "Needs Improvement"), and logs rows to specific Sheets based on the classification.
![Student Grade Classifier](https://drive.google.com/file/d/1vddB8ibDhd4AFEHMqqA9oQ1mhtyDhrod/view?usp=sharing)

### Scheduling Posts – Airtable Integration
**Description:** Watches Airtable tables for scheduled LinkedIn posts, automates publishing through Buffer, and updates Airtable with posting status and assigned priorities.
![Scheduling Post with Airtable Integration](https://drive.google.com/file/d/15MYoe5xdi39aN2AzG0dnzEgMIe_y9xKK/view?usp=sharing)

### Customer Feedback Sentiment Analysis + WhatsApp
**Description:** Processes customer feedback data via webhook input, applies AI-driven sentiment analysis, and sends structured feedback summaries via WhatsApp using **GREEN-API**.
![Customer Feedback Sentiment Analyser+Whatsapp](https://drive.google.com/file/d/17C-WrITvzMm0nKULiHYsrnU79wa0rgqh/view?usp=sharing)

### Crypto Watcher (v1 and v1 copy)
**Description:** Fetches market data for Bitcoin and Ethereum from CoinGecko, sending email alerts based on price change thresholds.
![Crypto Watcher](https://drive.google.com/file/d/1LZoxHr6PBmOK4G28r-9enzXzqqJ69bfq/view?usp=sharing)
![Crypto WatcherV1+Webhook](https://drive.google.com/file/d/1uvuHqtthSFrPHIbEnoFZBDHY28ARNVZo/view?usp=sharing)
![Crypto WatcherV1](https://drive.google.com/file/d/1VF3SyR8PCsu1FYajiHE9X9lK76k24-sS/view?usp=sharing)

### Integration HTTP, JSON, Google Sheets
**Description:** Extracts random quotes via HTTP GET requests, parses JSON responses, and logs the structured quote data into Google Sheets.
![ntegration HTTP, JSON, Google Sheets](https://drive.google.com/file/d/1KYstb0kPPh0tvwGVHg2UltPix2EMn4Em/view?usp=sharing)

### Lead Scraping – Apify + Sheets
**Description:** Scrapes marketing agencies located in Austin, TX, via Apify, enriches entries with contact information, and stores organized leads in Google Sheets.
![Lead Scraping](https://drive.google.com/file/d/1pQHxz_2SDxwny5RAjVg1RHomGlt30tnX/view?usp=sharing)

### Airtable Record Update
**Description:** Triggers Airtable record fetching and updating using Make.com webhooks. Handles operations like image analysis and content generation workflows.
![Airtable Record Update](https://drive.google.com/file/d/1AnJBrA3nUQo6986w7BZNhJIG-mZ8a_By/view?usp=sharing)

### Iterator Deduplication
**Description:** Aggregates duplicated rows from Google Sheets, deduplicates entries using built-in functions, and prepares clean arrays for downstream use.
![Iterator Deduplication](https://drive.google.com/file/d/1Y6EtSRcQHCzJRiaQhEKMQtC9ul2zS7Rv/view?usp=sharing)

### Fetch Response from Google Forms
**Description:** Monitors Google Forms for new responses, parses structured answers, and prepares them for external processing or integrations.
![Fetch Response from Google Forms](https://drive.google.com/file/d/14vi2mjS9e8Esuywyna-qqgvlCFwgEwGX/view?usp=sharing)

### Integration Google Drive
**Description:** Automatically searches for files within specific Google Drive folders, downloads them in preferred formats, and logs file metadata into Google Sheets.
![Integration Google Drive](https://drive.google.com/file/d/1TeNSasAXWvzBAA6O9nbnur4yYWxFMq5I/view?usp=sharing)
---

## 🛠️ Technologies Utilized

- **Make.com:** Workflow orchestration and automation engine.
- **Airtable:** Lead generation, database management, and content collaboration.
- **Apify:** Advanced web scraping and data enrichment.
- **Slack and Telegram:** Messaging and real-time notifications.
- **Google Sheets & Forms:** Structured data input/output and reporting.
- **GREEN-API:** WhatsApp messaging for real-time feedback.
- **Buffer:** Social media scheduling and automation.
- **AI Tools:** Sentiment analysis and intelligent content generation.

---

## 📌 Repository Notes

- All blueprints have been thoroughly tested and optimized for real-time execution.
- Sensitive tokens, API keys, and configuration settings are excluded from public commits for security and compliance.
- Modular architecture ensures adaptability and integration across diverse platforms and workflows.

### 💡 Contribution Guidelines
We welcome contributions to improve these automation processes and blueprints. Feel free to submit your suggestions or enhancements via pull requests.

---

```list type="project"
data:
- name: "Typeform-Air-Slack"
  description: "Airtable's mapping and Slack DM notification."
  
- name: "Austin Lead Scraping"
  description: "Automatic lead scraping targeting outreach automation on Apify."

Make only certain production failed key PR final debugging chips.
  committer repo"
```
