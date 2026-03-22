# 📧 Lead Email Outreach Sequence

## What This Does
Automatically captures new leads from a Typeform form, uses GPT-4o to write a personalised outreach email based on the lead's name, company, industry and pain point, sends it via Gmail, and logs every lead and email to a Google Sheet — all without any manual work.

This workflow eliminates the time-consuming task of writing individual outreach emails by hand. Every lead gets a unique, relevant message written by AI in seconds.

---

## 🔧 Tools Connected
| Tool | Purpose |
|---|---|
| **Typeform** | Captures lead details via form submission |
| **OpenAI GPT-4o** | Generates a personalised outreach email per lead |
| **Gmail** | Sends the email automatically to the lead |
| **Google Sheets** | Logs every lead, email body and send date for tracking |

---

## ⚙️ How To Import & Use

1. Download the `lead-email-outreach-sequence.json` file
2. Go to **make.com** and create a new scenario
3. Click the **three dots (⋯)** at the bottom of the screen
4. Click **"Import Blueprint"**
5. Select the downloaded JSON file
6. Connect your Typeform, OpenAI, Gmail and Google Sheets accounts
7. Replace all placeholders (see below)
8. Turn the scenario **On**

---

## 🔁 What To Replace

| Placeholder | Replace With |
|---|---|
| `YOUR_TYPEFORM_FORM_ID` | Your Typeform form ID (found in the form URL) |
| `YOUR_GOOGLE_SHEET_ID` | Your Google Sheet ID (found in the sheet URL) |
| `YOUR_EMAIL@gmail.com` | Your Gmail address to send from |

---

## 💡 Example Use Case

A freelance automation consultant uses this workflow on their website contact form. Every time a potential client fills in the form, they receive a personalised email within 60 seconds — written specifically about their company and industry — while the consultant is doing other work.

**Result:** Response rates increased because every email feels hand-written and relevant, with zero manual effort per lead.

---

## 📋 Workflow Steps

```
Typeform New Submission
        ↓
GPT-4o Writes Personalised Email
        ↓
Gmail Sends Email to Lead
        ↓
Google Sheets Logs Lead + Email Body
```

---

*Built by Theo Murimwa — Automation Engineer & Make.com Specialist*
