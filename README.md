# fee-automation-reminder-n8n
# Fee Automation (n8n)

Automatic fee receipts and reminders for a school, built without code.

## The problem
Teachers write fee reminders by hand in every student's diary, every month.

## What it does
- Parent submits the fee in a Google Form
- The answer is saved in Google Sheets
- A receipt is created from a Google Docs template
- A "Fee received" email goes to the parent
- 7th of the month: friendly reminder to unpaid parents
- From the 11th: daily overdue email at 9 AM until the fee is paid

## Tools
n8n, Google Forms, Sheets, Docs, Drive, Gmail

## How to use
1. Import the .json file into n8n
2. Connect your own Google account
3. Make your own Form, Sheet and receipt template

## What I learned
- Google Docs accepts text only, so numbers need converting
- Each If condition needs its own exit wire

## Next
PDF attachment, WhatsApp messages

Tested with dummy data only.
