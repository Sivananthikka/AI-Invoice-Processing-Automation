# Workflow Overview

The project was implemented as an n8n automation workflow.

## Flow

Gmail Email Trigger
→ Conditional Check
→ Extract Invoice from PDF
→ AI Agent (Google Gemini)
→ Merge
→ Edit Fields
→ Conditional Validation
→ Google Sheets
→ Gmail Notification

## Main stages

1. **Email Trigger** — starts the workflow when an invoice email is received.
2. **Conditional Check** — applies the initial workflow condition.
3. **PDF Extraction** — extracts invoice content from the attached PDF.
4. **AI Agent** — uses Google Gemini to analyze the extracted invoice information.
5. **Merge / Edit Fields** — combines and prepares the structured invoice fields.
6. **Validation** — evaluates the invoice and determines the next path.
7. **Google Sheets** — stores the processed invoice record.
8. **Gmail Notification** — sends the resulting invoice status automatically.

> The repository documents the implemented workflow and screenshots. The original n8n export JSON is not included because the original n8n workspace is no longer available.
