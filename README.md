# School Attendance Alert Automation 🚸✉️

This project is an automation workflow that sends automated email alerts to parents when their child is marked absent in a Google Sheet.

## ✨ Features

- Scheduled daily check (e.g., 9 AM).
- Reads student attendance data from Google Sheets.
- Identifies absent students.
- Sends personalized email notifications to parents via Gmail.
- Configurable message limit to avoid spam or quota issues.

## 🛠️ Tools Used

- [Make.com](https://www.make.com/) (or Integromat)
- Google Sheets (for attendance records)
- Gmail (for sending emails)

## 📁 How It Works

1. **Trigger:** Scheduled daily at a specific time.
2. **Data Fetch:** Pulls rows from the Google Sheet.
3. **Condition Check:** Filters rows where the student is marked `Absent`.
4. **Limit (optional):** Limits number of emails sent per run.
5. **Action:** Sends an email message to each corresponding parent.

## 📋 Sample Google Sheet Format

| Student Name | Attendance | Parent Email       |
|--------------|------------|--------------------|
| John Doe     | Present    | parent1@example.com |
| Jane Smith   | Absent     | parent2@example.com |

> The system will send an email to `parent2@example.com` for Jane Smith.

## 📧 Example Email

Subject: Student Absence Notification  Dear Parent,  We would like to inform you that your child was absent from school today. Kindly provide a reason for the absence and ensure that any missed assignments or classwork are followed up on.  If there is anything the school can assist with, please don’t hesitate to reach out.  Thank you for your attention and cooperation.  Warm regards, [Sowmya Sri] [class Teacher] Kakatiya High Shool


Body:
