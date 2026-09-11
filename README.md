# First Automation without AI

This n8n workflow automates lead capture and customer onboarding. It automatically processes new client information from a Google Sheet, updates Google Contacts, and handles email notifications.

## What This Workflow Does
1. Triggers: Checks a Google Sheet every minute for new client data submissions.
2. Onboarding Email: Automatically sends a "Thank you" email to the address provided by the client.
3. Contact Management: Creates a new contact record inside Google Contacts using the client's information.
4. Internal Notification: Sends an alert email to the administrator to notify them that a new client has been added.

## Requirements
- An account with n8n.
- A Google Workspace account (for Google Sheets, Google Contacts, and Gmail).
