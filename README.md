# 📧 Email Classification Workflow — n8n + AI

## What This Does
Imagine running a business where hundreds of emails flood your inbox every single day. Someone has to read each one, figure out who it's for, and forward it to the right team. That's hours of manual work — and humans make mistakes.
This workflow eliminates that problem completely.
It monitors your inbox 24/7, reads every incoming email, and uses AI to instantly decide which department should handle it — then logs everything automatically. No human sorting. No missed emails. No wrong department.
__________________________________________________________________________________________________________________________________________

## How It Works

The moment an email lands in your inbox, the workflow wakes up and gets to work:

Email Trigger — watches your inbox via IMAP and fires the workflow the second a new email arrives
Extract Email Data — pulls out the important stuff: the sender, subject, and body
AI Agent — powered by OpenAI GPT, it reads the email content and decides which department it belongs to
Switch Router — takes the AI's decision and routes the email down the correct path
Set Node — labels the email with the department name and timestamp
Google Sheets Logger — records everything into a clean spreadsheet in real time
---------------------------------------------------------------------
|##Departments It Classifies Into|
| Department  |    Example Emails📈|
| Sales | Pricing inquiries, product interest, renewals🎧|
| Customer Service | Complaints, support requests, refunds👥|
| Human Resources | Job applications, leave requests, recruitment💰|
| Finance | Invoices, payments, billing issues🚚 |
| Operations | Deliveries, logistics, scheduling📂 |
| Others | Anything that doesn't fit the above|
_________________________________________________
##Tools Used

n8n — the automation platform that powers the entire workflow
OpenAI GPT — the AI brain that reads and classifies emails
Google Sheets — stores the classification log
Gmail / IMAP — the email trigger

All of these tools have free tiers. You don't need to spend a single dollar to run this.

The Result
Every classified email gets logged into Google Sheets like this:
TimestampFromSubjectCategory2024-05-16 08:32john@gmail.comInterested in your pricingSales2024-05-16 09:14angry@customer.comMy order never arrivedCustomer Service2024-05-16 10:05staff@company.comAnnual leave requestHuman Resources
Clean. Organised. Automatic.

Why This Matters
Most businesses treat email sorting as a small problem — until they're drowning in 500 unread emails and the wrong team is handling the wrong messages.
This workflow solves that before it becomes a problem. It scales infinitely, works around the clock, and never gets tired or distracted.

Built By
Torobong Umoekam Edet (Eddie)
Law Student | AI & Automation Specialist
www.linkedin.com/in/torobong-umoekam-32b0b2291



