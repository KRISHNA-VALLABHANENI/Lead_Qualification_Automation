# AI Lead Qualification Automation

## Overview

This project is an AI-powered lead qualification workflow built using n8n and Google Gemini AI. The system automatically analyzes customer form responses, categorizes leads as HOT, WARM, or COLD, and triggers different communication workflows based on lead type.

## Features

* Automated lead qualification
* AI-based customer categorization
* HOT / WARM / COLD lead routing
* Email notifications
* WhatsApp message automation
* Google Sheets data logging
* Workflow automation using n8n

## Workflow Process

1. User submits a form
2. JavaScript processes the input data
3. Google Gemini AI analyzes the customer response
4. Leads are categorized as HOT, WARM, or COLD
5. Automated actions are triggered:

   * HOT leads → Email notification + Google Sheets entry
   * WARM leads → AI-generated follow-up + WhatsApp message + Sheets entry
   * COLD leads → Automated email response

## Tech Stack

* n8n
* Google Gemini AI
* JavaScript
* Gmail
* WhatsApp API
* Google Sheets
* JSON
* REST APIs

## Project Structure

* lead_qualificatuon_automation.json → Exported n8n workflow
* L_Q_A_Screenshots/ → Workflow screenshots
* README.md → Project documentation

## Screenshot

<img width="1707" height="921" alt="lead_qualification_automation" src="https://github.com/user-attachments/assets/86d08ac1-6d59-41e7-a37e-8d46a093a23a" />


## Learning Outcome

This project helped me understand:

* Workflow automation
* API integrations
* AI-powered automation systems
* Conditional logic handling
* Automated communication workflows

## Future Improvements

* CRM integration
* Lead scoring system
* Dashboard analytics
* Multi-channel notifications
* Database integration
