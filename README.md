Google Review Request Automation — Make.com

Automatically sends personalised Google review request emails to customers pulled from a Google Sheet — generating more 5-star reviews without any manual effort.

The Problem
Most businesses lose dozens of potential 5-star reviews every month simply because they forget to ask. Manually emailing every customer after a job or sale is:

Time-consuming and easy to skip
Inconsistent — some customers get asked, most don't
Impossible to scale as the business grows


The Solution
This Make.com automation watches a Google Sheet for new customer entries and automatically sends a personalised review request email — then follows up if there's no response. Zero manual effort required.

How It Works
Google Sheet (new row added)
        ↓
Make.com reads customer name, email & job details
        ↓
Personalised review request email sent automatically
        ↓
Follow-up reminder sent if no action taken
        ↓
Customer clicks link → leaves Google Review ⭐⭐⭐⭐⭐

Tools & Apps Used
Show Image
Show Image
Show Image
Show Image

Workflow Breakdown
StepModuleWhat It Does1Google Sheets — Watch RowsMonitors the sheet for new customer entries2Google Sheets — Get RowPulls customer name, email, and job details3Email — SendSends a personalised review request email with direct Google Review link4RouterChecks if the customer has left a review5Email — Send (Follow-up)Sends a polite reminder if no review after X days6Google Sheets — Update RowMarks the row as "Sent" to avoid duplicate emails

Results & Impact

⭐ More 5-star Google reviews generated on autopilot
⏱️ Saves 2–5 hours per week of manual follow-up per business
🔁 Automated follow-up reminders sent without any human involvement
📈 Consistent review volume — every customer gets asked, every time
🚫 No duplicate emails — sheet is updated after each send


Google Sheet Structure
Your sheet needs these columns for the automation to work:
ColumnDescriptionCustomer NameFirst name used to personalise the emailEmail AddressWhere the review request is sentJob/ServiceOptional — used to personalise the email bodyDate CompletedUsed to time when the request is sentStatusAuto-updated to "Sent" by the automation

How To Import & Use This Automation

Download the blueprint.json file from this repo
Go to make.com and create a new scenario
Click the three dots (⋯) at the bottom of the screen
Select "Import Blueprint" and upload the .json file
Connect your Google Sheets and Gmail accounts
Update the Google Review link inside the email module with your client's actual review URL
Set your Google Sheet ID in the Watch Rows module
Turn the scenario ON and set your preferred schedule


📁 Files In This Repo
📂 google-review-automation/
├── blueprint.json          ← Import this into Make.com
├── email-template.txt      ← The review request email copy
├── follow-up-template.txt  ← The follow-up reminder email copy
└── README.md               ← You are here

Customisation Ideas

🔀 Add an SMS channel alongside email for higher open rates
⏰ Adjust the follow-up delay — 3 days, 7 days, or custom timing
🏷️ Segment by service type — send different emails for different jobs
📊 Add a Slack notification when a new review is received
🌍 Multi-location support — route different customers to different Google Review links


 Want This Built For Your Business?
I build and deploy this automation for businesses that want more Google reviews without the manual work.
📧 Contact: climautomation@gmail.com/tmurimwas@gmail.com

Built with Make.com · Part of Climb Automation/Theo Murimwa's Automation Portfolio
