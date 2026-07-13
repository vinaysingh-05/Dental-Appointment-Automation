# Workflow Explanation

## Workflow

```text
Website
    │
    ▼
Appointment Form
    │
    ▼
Webhook
    │
    ▼
Lead Validation
    │
    ▼
Google Sheets
    │
    ├──────────────┐
    ▼              ▼
OpenAI         Gmail
    │              │
    └──────► Email Sent
```

The workflow validates every enquiry before saving it into Google Sheets.

If the lead is valid:

- Save to Google Sheets
- Generate AI Email
- Send Confirmation Email

Otherwise:

- Mark as Fake Lead
- Save validation reason.