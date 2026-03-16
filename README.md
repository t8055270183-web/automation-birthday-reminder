# automation-birthday-reminder
RPA Birthday Reminder Automation built using UiPath Studio. The bot reads birthdays from an Excel file, compares them with the current date, and automatically sends reminders when a match is found. This project demonstrates how Robotic Process Automation can eliminate repetitive tasks and ensure important dates are never missed.
RPA Birthday Reminder Automation

An RPA automation project built using UiPath Studio that automatically checks a list of birthdays and sends reminders to users on the correct date.

This project demonstrates how Robotic Process Automation (RPA) can be used to automate repetitive tasks such as monitoring dates, retrieving data from spreadsheets, and sending notifications.

📌 Project Overview

Remembering birthdays manually can be difficult, especially when managing large contact lists. This automation solves the problem by automatically checking a birthday database and notifying users when a birthday occurs.

The bot reads birthday data from a spreadsheet, compares it with the current system date, and sends reminders when a match is found.

This eliminates the need for manual checking and ensures that important dates are never missed.

⚙️ How the Automation Works

The workflow performs the following steps:

The bot reads a list of people and their birthdays from an Excel file.

It retrieves the current system date.

It compares today's date with the birthdays in the dataset.

If a birthday matches today's date, the bot triggers a reminder notification.

The reminder can be sent through a desktop notification, email, or message.

🧠 Key Features

Automated birthday detection

Excel data integration

Date comparison logic

Automatic reminder notifications

Simple and scalable workflow

🛠 Technologies Used

UiPath Studio

Microsoft Excel

UiPath Activities

RPA workflow automation

📂 Project Structure
BirthdayReminderBot
│
├── Main.xaml
├── BirthdayData.xlsx
├── project.json
└── README.md
📊 Example Excel Dataset
Name	Birthday
Rahul	12-03
Priya	17-03
Aman	05-08

The bot checks if today’s date matches any birthday in the list.

▶️ Running the Bot

Open the project in UiPath Studio

Update the BirthdayData.xlsx file with contact names and birthdays

Run Main.xaml

The bot will check today's date and send reminders automatically

🚀 Future Improvements

Possible enhancements for this project include:

Email reminders using SMTP

WhatsApp or Teams notifications

Google Calendar integration

Daily scheduled bot execution

Cloud deployment using UiPath Orchestrator

🎯 Learning Outcomes

This project demonstrates practical knowledge of:

Robotic Process Automation

Workflow design

Data extraction from Excel

Conditional automation logic

Task scheduling

👩‍💻 Author

Tanvi Arvind Singh

💡 UiPath Workflow Prompt / Idea

If you want to recreate this automation, use this logic in UiPath Studio:

Automation Logic
Start
↓
Read Excel File (BirthdayData.xlsx)
↓
Store Data in DataTable
↓
Get Current Date
↓
For Each Row in DataTable
    Extract Birthday Column
    Compare with Today's Date
    If Match
        Show Notification
        Send Email Reminder
End
UiPath Activities Used

Excel Application Scope

Read Range

For Each Row

Assign

If Condition

Message Box / Send Outlook Mail Message
