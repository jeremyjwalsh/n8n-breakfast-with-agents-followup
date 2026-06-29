# Personalized Event Follow-up with n8n

AI-powered personalized event follow-up workflow built using n8n, OpenAI, Google Drive, and Gmail.

---

## Overview

This workflow automates the creation of personalized follow-up emails after an in-person AI networking event.

Instead of sending a generic thank-you email, it:

- Downloads attendee data from Google Drive
- Converts CSV data into structured JSON
- Uses OpenAI to generate a personalized email for each attendee
- Parses the AI response into Subject and Message fields
- Creates Gmail drafts for human review before sending

The workflow intentionally keeps a human in the loop by generating Gmail drafts rather than automatically sending emails.

---

## Workflow

*(Add your workflow screenshot here.)*

---

## Event Used

This project was built using attendee data from:

**Breakfast with Agents — USEReady AI Practitioner Series**

https://breakfastwithagents.com/event/breakfast-with-agents-finance-nyc-april-2026/

---

## Technologies

- n8n
- OpenAI
- Google Drive
- Gmail
- JSON
- CSV Processing

---

## Future Improvements

- Batch processing
- CRM integration
- Duplicate detection
- Contact enrichment
- Automated approval workflow

---

Built by Jeremy Walsh
