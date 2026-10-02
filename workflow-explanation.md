# Workflow Explanation

The workflow was created as a hands-on learning project in workflow automation.

An incoming email containing an invoice starts the automation. The invoice PDF is extracted and passed to an AI Agent powered by Google Gemini. The workflow then prepares structured fields such as invoice number, vendor, and total amount.

Conditional logic is used to validate the processed invoice and determine an approval status and risk score. The resulting record is appended to Google Sheets, and an automated Gmail message communicates the result.

The example captured in the project shows:

- Invoice: INV-1001
- Vendor: ABC Pvt Ltd
- Amount: 25,000
- Status: APPROVED
- Risk score: 10
