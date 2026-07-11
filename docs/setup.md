# Setup Guide

## Prerequisites

- n8n
- OpenAI API Key
- Google Sheets OAuth Credentials
- Gmail OAuth Credentials

---

## Installation

1. Clone this repository.

2. Open n8n.

3. Import

```
workflow.json
```

4. Configure the following credentials:

- OpenAI
- Google Sheets
- Gmail

5. Replace the Google Sheet ID with your own.

6. Execute the workflow.

---

## Expected Google Sheet

The workflow expects three columns.

| Name | Email | Topic |
|------|------|------|
| John | john@example.com | Artificial Intelligence |

---

## Output

The workflow will:

- Generate a personalized email
- Send it using Gmail
- Append **Sent** to the Google Sheet