# StyleNest — AI-Powered E-Commerce Automation

## Overview

StyleNest is an e-commerce automation project built using n8n. It automates customer request handling, order processing, inventory updates, and email notifications.

## Features

* AI-based classification of customer requests into Place Order, Product Question, and Complaint.
* Product lookup using Google Sheets.
* Automated stock availability checking.
* Automatic inventory updates after successful orders.
* Order records stored in Google Sheets.
* Customer order confirmation emails.
* Owner email alert when a product reaches zero stock after an order.
* Automated handling of customer complaints and product questions.

## Tools & Technologies

* n8n
* Google Sheets
* Gmail
* Google Gemini
* AI Agent
* Switch and IF nodes

## Workflow

1. Customer submits a form.
2. AI classifies the request.
3. The workflow routes it to the relevant process.
4. For orders, it checks product stock and calculates the total.
5. It updates inventory and records the order.
6. It sends the customer a confirmation email.
7. If stock reaches zero, it notifies the store owner.

## Project Files

* `StyleNest-Workflow.json` — exported n8n workflow.
* `Screenshots/` — workflow and sample output screenshots.

## Setup

1. Import the workflow JSON into n8n.
2. Connect your own Google Sheets, Gmail, and Gemini credentials.
3. Configure your own form and spreadsheet.
4. Test using sample data before using it in a real store.

**Note:** This is a portfolio project. Use your own credentials and test data when running it.

## Author

Beenish Iqbal
BS Artificial Intelligence Student

