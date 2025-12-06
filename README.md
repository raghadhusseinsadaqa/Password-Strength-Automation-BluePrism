🚀 Password Strength Automation – Blue Prism Project

This project is a Blue Prism automation designed to analyze the strength of passwords, generate a detailed report, and automatically send the results via email.

📘 Project Overview

The automation performs the following tasks:

1️⃣ Receive Input Email

The bot starts after receiving an email request.

2️⃣ Access Kaggle Dataset

Visits Kaggle daily

Opens dataset: 10,000 Most Common Passwords

Downloads and extracts the dataset

3️⃣ Prepare Excel Report

Removes unnecessary columns

Adds fields:

Strength

Estimated Time

Extracts password list from the dataset

4️⃣ Check Password Strength (Bitwarden)

For each password:

Opens Bitwarden password-strength evaluator

Retrieves:

Strength Level

Estimated Cracking Time

5️⃣ Generate Final Report

Fills Excel file with results

Creates a summary sheet showing count of each strength level

Saves the output

6️⃣ Send Email with Final Results

Sends email with:

Subject: Password Strength Report

Attachment: Final Excel Report

🗂️ Project Structure
Raghad-FinalProject      → Blue Prism automation file
AutomatedPasswordPDD.pdf → Process design document
README.md                → Project documentation

🛠️ Tools & Technologies

Blue Prism

MS Excel

Outlook

Kaggle

Bitwarden Password Strength Tool

⭐ Business Benefits

80% reduction in processing time

Automated report generation

Higher accuracy & consistency

Improved monitoring via system logs

👩‍💻 Developer

Raghad Hussien Alsadaqa
Computer Science Graduate | Interested in Automation & RPA

