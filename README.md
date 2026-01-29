## Automated Branch Sales Analysis using n8n

## Project Description
This project automates the analysis of **daily sales data** for multiple branches of a company using **n8n workflow automation** and **Google Sheets**.

The workflow automatically:
- Reads sales data from Google Sheets
- Calculates total sales & orders per branch
- Identifies the **top-performing branch**
- Sends the result via **email notification**

This removes manual effort and provides quick business insights.

## Tech Stack
- **n8n (Workflow Automation Platform)**
- **Google Sheets**
- **JavaScript (n8n Code Nodes)**
- **Gmail (Email Notifications)**

## Workflow Architecture
text
Google Sheets
     ↓
Read Rows
     ↓
JavaScript (Process Data)
     ↓
Sort (Highest Sales)
     ↓
JavaScript (Pick Top Branch)
     ↓
Gmail (Send Email)
