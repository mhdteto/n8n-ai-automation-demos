# How to Import the n8n Workflows

## Overview

This repository includes demo n8n workflow JSON files.

They are designed for learning, prototyping, SMB automation conversations and client workshops.

They are not production-ready without review and adaptation.

---

## Step 1 - Open n8n

Open your n8n instance.

You can use:

- n8n Cloud.
- A self-hosted n8n instance.
- A local test environment.

---

## Step 2 - Import a workflow

In n8n:

1. Go to **Workflows**.
2. Click **Import from file** or use the import option.
3. Select one JSON file from the `workflows/` folder.
4. Open the imported workflow.
5. Review every node before activating it.

---

## Step 3 - Replace placeholders

The workflows may contain placeholder nodes or example values.

Replace them with your own tools, such as:

- CRM.
- Email inbox.
- Google Sheets.
- Airtable.
- Slack.
- Microsoft Teams.
- Webhook source.
- AI provider.

---

## Step 4 - Add credentials safely

Add credentials inside n8n.

Do not store credentials directly in JSON files.

Never commit:

- API keys.
- OAuth tokens.
- Passwords.
- CRM credentials.
- Email credentials.
- Internal webhook URLs.
- Client data.

---

## Step 5 - Test with sample data

Before using real data, test with files from:

```txt
examples/sample-inputs/
```

Use fake leads, fake emails, fake meeting notes and fake content briefs.

---

## Step 6 - Add human review

AI-generated output should be reviewed before it affects customers, CRM records or outbound communication.

Recommended human review points:

- Lead qualification output.
- Email intent classification.
- CRM updates.
- Customer-facing messages.
- Content briefs.
- Any high-impact decision.

---

## Step 7 - Activate carefully

Before activation, check:

- Inputs.
- Outputs.
- Credentials.
- Permissions.
- Error handling.
- Data retention.
- Human review steps.
- Notification logic.

Start with a small test group before scaling.
