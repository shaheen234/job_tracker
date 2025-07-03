# n8n Job Application Tracker Workflow

This project contains an n8n workflow that automates job application tracking by integrating Gmail, Google Sheets, and AI-based information extraction.

## Features
- Automatically reads job application emails from Gmail.
- Extracts company name, position applied, Infers Status,and relevant dates based on Prompt provided.
- Deduplicates entries and updates a Google Sheet with new or changed information.
- Uses custom logic in n8n’s code nodes for data validation.

## How to Use
1. Import the `Job_Tracker.json` file into your n8n instance.
2. Set up credentials for Gmail, Gemini and Google Sheets.
3. Update sheet and field mappings as per your own Google Sheet.
4. Activate and test the workflow.

## Requirements
- n8n instance (self-hosted or cloud)
- Gmail API credentials
- Gemini Model API credentials
- Google Sheets API credentials

## Screenshots

![image](https://github.com/user-attachments/assets/2b048c71-04f1-4e5d-b787-e590d6344a8b)
![image](https://github.com/user-attachments/assets/8574b858-37e8-443f-8f73-b56467e26b77)




## Author
- [Your Name](https://github.com/shaheen234)
