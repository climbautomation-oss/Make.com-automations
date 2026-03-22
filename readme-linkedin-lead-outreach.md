# 💼 LinkedIn Lead Outreach via Webhook

## What This Does
Receives a new lead from any source via webhook (Clay, Apollo, a spreadsheet, or a manual trigger), uses GPT-4o to generate a short personalised LinkedIn connection request message tailored to the lead's job title and company, sends a Slack notification to your team with the suggested message and LinkedIn URL, and logs everything to Airtable for pipeline tracking.

This workflow is designed for sales teams and freelancers who want to scale LinkedIn outreach without sending generic copy-paste messages that get ignored.

---

## 🔧 Tools Connected
| Tool | Purpose |
|---|---|
| **Webhook** | Receives lead data from any external source |
| **OpenAI GPT-4o** | Writes a personalised LinkedIn connection message |
| **Slack** | Notifies your team with the message ready to send |
| **Airtable** | Logs the lead and message to your outreach pipeline |

---

## ⚙️ How To Import & Use

1. Download the `linkedin-lead-outreach-webhook.json` file
2. Go to **make.com** and create a new scenario
3. Click the **three dots (⋯)** at the bottom of the screen
4. Click **"Import Blueprint"**
5. Select the downloaded JSON file
6. Connect your OpenAI, Slack and Airtable accounts
7. Copy the generated webhook URL from the webhook module
8. Paste that URL into your lead source (Clay, Apollo, Google Sheets, etc.)
9. Replace all placeholders (see below)
10. Turn the scenario **On**

---

## 🔁 What To Replace

| Placeholder | Replace With |
|---|---|
| `YOUR_WEBHOOK_URL` | Auto-generated when you activate the webhook module |
| `YOUR_SLACK_CHANNEL_ID` | Your Slack channel ID where notifications should go |
| `YOUR_AIRTABLE_BASE_ID` | Your Airtable base ID (found in the API docs) |
| `YOUR_AIRTABLE_TABLE_ID` | Your Airtable table name or ID |

---

## 💡 Example Use Case

A B2B sales agency runs Apollo.io to find leads. Every new lead Apollo identifies is sent via webhook to this workflow. Within seconds, GPT-4o writes a unique LinkedIn message for that specific person based on their title and company. The message pops up in Slack so the sales rep can copy and send it in one click — and the lead is automatically added to the Airtable pipeline.

**Result:** The team sends 50+ personalised LinkedIn messages per day in a fraction of the time it previously took.

---

## 📋 Workflow Steps

```
Webhook Receives Lead Data
        ↓
GPT-4o Writes Personalised LinkedIn Message
        ↓
Slack Notifies Team with Message + LinkedIn URL
        ↓
Airtable Logs Lead to Outreach Pipeline
```

---

*Built by Theo Murimwa — Automation Engineer & Make.com Specialist*
