📌 Password Strength Automation – Blue Prism Project
This project is a Blue Prism automation designed to analyze the strength of passwords, generate a detailed report, and automatically send the results via email.

🔹 📘 Project Overview
The automation performs the following tasks:
1. Receive input email
-The bot starts when it receives an email request.

2. Access Kaggle dataset
-Visits Kaggle daily
Opens dataset: 10,000 most common passwords
Downloads and extracts the data

3. Prepare Excel report

Removes unnecessary columns
-Adds new fields:
Strength
Estimated Time
Extracts the password list

4. Check password strength (Bitwarden)
-For each password:
Opens Bitwarden: password-strength evaluator
-Retrieves:
Strength level
Estimated cracking time

5. Generate final report
-Fills Excel with results
Creates summary sheet with password strength counts

Saves the final output

6. Send the report
-Sends email with:
Subject: Password Strength Report
Attachment: Final Excel Report
Attachment: Final Excel Report

🔹 📁 Project Structure
Raghad-FinalProject       → Blue Prism automation file
PDD.pdf                   → Process design document
README.md                 → Project documentation

🔹 🧰 Tools & Technologies

Blue Prism
Excel
Outlook
Kaggle
Bitwarden

🔹 ✔️ Business Benefits

80% reduction in processing time
Automated reporting
More accuracy & consistency
Better monitoring using logs

🔹 👩‍💻 Developer

Raghad Hussien Alsadaqa
Computer Science Graduate | Interested in Automation & RPA
