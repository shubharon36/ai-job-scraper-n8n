# ai-job-scraper-n8n
Automated job scraper with AI summary using n8n, Gemini, and Google Sheets


This n8n workflow scrapes job listings (React, DevOps, AI/ML, etc.) from RapidAPI, summarizes them using Google Gemini, and saves results to Google Sheets.

## Features:
- Scrapes latest jobs every 24 hrs
- Summarizes job descriptions with Gemini (chat model)
- Saves structured data to Google Sheets

## Setup:
1. Import `job_scraper_workflow.json` into n8n
2. Set credentials for:
   - HTTP Request (RapidAPI)
   - Google Sheets
   - Gemini (API key)
3. Run or schedule it!
