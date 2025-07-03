# n8n Job Application Tracker Workflow

This project contains an n8n workflow that automates job application tracking by integrating Gmail, Google Sheets, and AI-based information extraction.

## Features
- Automatically reads job application emails from Gmail.
- Extracts company name, position applied, Infers Status,and relevant dates based on Prompt provided.
- Deduplicates entries and updates a Google Sheet with new or changed information.
- Uses custom logic in n8n’s code nodes for data validation.

## How to Use
1. Import the `job-tracker-workflow.json` file into your n8n instance.
2. Set up credentials for Gmail, Gemini and Google Sheets.
3. Update sheet and field mappings as per your own Google Sheet.
4. Activate and test the workflow.

## Requirements
- n8n instance (self-hosted or cloud)
- Gmail API credentials
- Gemini Model API credentials
- Google Sheets API credentials

## Screenshots

![image](https://github.com/user-attachments/assets/6a218903-aaa0-4f16-a12a-0c2312e6c2d6)
![image](https://github.com/user-attachments/assets/5ea22ccf-093a-4498-aa9b-456ec82d5b83)



## Author
- [Your Name](https://github.com/shaheen234)
