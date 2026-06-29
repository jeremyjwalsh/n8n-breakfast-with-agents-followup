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

The workflow below was built around a real AI practitioner event using representative attendee data to protect attendee privacy while demonstrating the automation. It downloads attendee information from Google Drive, converts the data into structured JSON, uses OpenAI to generate personalized follow-up emails, and creates Gmail drafts for human review before sending.

<img width="1927" height="1131"
     alt="Workflow for generating personalized follow-up emails from the Breakfast with Agents event using n8n, OpenAI, Google Drive, and Gmail"
     src="https://github.com/user-attachments/assets/810abad2-7763-4d1e-ab53-130c4a1be9ba" />

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

- ## Why I Built This

n8n's application encouraged applicants to build a first workflow.
Rather than creating a generic demo, I used an AI practitioner event I co-hosted with USEReady ("Breakfast with Agents") as inspiration.
The workflow demonstrates how AI can reduce repetitive follow-up work while intentionally keeping a human in the review loop by creating Gmail drafts instead of automatically sending emails.ﬁ
This project reflects the type of practical AI adoption work I've spent much of my career helping customers achieve.

---

Built by Jeremy Walsh
