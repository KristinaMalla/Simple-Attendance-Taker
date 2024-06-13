# Simple-Attendance-Taker
This repository contains a Python script designed to manage and monitor attendance for students across multiple subjects using an Excel spreadsheet. The script allows instructors to track attendance and send automated emails to students based on their attendance status.
**Features:**
1. Excel Integration: Utilizes openpyxl library to load and update attendance records stored in an Excel workbook (attendance.xlsx).

2. Automated Email Notifications: Sends email notifications to students based on their attendance status:

3. Attendance Warning: Alerts students when they are close to reaching their absentee limit for a specific subject.
4. Attendance Alert: Notifies students when they exceed their absentee limit, prompting them to meet with their instructor.
5. Subject Selection and Absentee Input: Allows instructors to select a subject (CI, Python, Data Mining) and input absentee information:

6. Instructors can specify multiple absentees at once or individually enter roll numbers for students who were absent.
7. User Interaction: The program runs in a loop, enabling instructors to continuously check attendance across different subjects until they decide to exit.

**Usage:
Setup:**

**Ensure Python 3.x and necessary libraries (openpyxl, smtplib) are installed.
Update staff_mails list with appropriate staff email addresses.
Running the Program:**

**Execute attendance.py using Python interpreter.
Follow the prompts to select a subject, enter absentee information, and choose whether to check another subject.
Automated emails will be sent based on attendance thresholds defined in the script.
Email Configuration:

Update send_email() function with sender email credentials (from_id and pwd).
Customize email subjects and body messages in check_attendance() function based on subject-specific thresholds.
Files:
attendance.py: Main Python script to manage attendance tracking and email notifications.
attendance.xlsx: Excel workbook storing attendance records. Automatically created if it doesn't exist.
Dependencies:
openpyxl: For interacting with Excel files.
smtplib: For sending emails from Python script.**
