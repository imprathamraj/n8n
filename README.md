# Automating Employee Addition Emails using OpenAI, Airtable, and Gmail

A production-ready workflow that automates email notifications for **new employee additions**. It uses **Airtable** as the data source, **OpenAI (ChatGPT/GPT-4o)** to generate a professional email subject and body, and **Gmail** to send the emails automatically. Built and orchestrated with Make.com (or any workflow automation tool of your choice).

---

## 🔎 Overview
When a new employee record is added in Airtable, the workflow:
1. **Triggers** on the new record.
2. **Generates** a clean, professional email (subject + body) using an OpenAI prompt.
3. **Sends** the email via Gmail to the HR team or designated recipients.

This removes manual effort, ensures consistent formatting, and improves response times.

---

## ✨ Features
- Airtable → OpenAI → Gmail end-to-end automation
- JSON or HTML email body rendering (with `<br>` line breaks)
- Clear separation of `email_subject` and `email_body`
- Minimal configuration; environment-driven secrets
- Easy to extend for multi-record digests or Slack/MS Teams notifications

