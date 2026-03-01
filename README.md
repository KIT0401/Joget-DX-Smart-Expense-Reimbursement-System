📘 Smart Expense Reimbursement System
- Low-Code & DevOps Assignment – Joget DX Application Guide

1️⃣ Introduction to Joget DX
- Joget DX is a low-code application platform that allows users to build workflow automation systems without heavy coding.

It provides:
- Drag-and-drop Form Builder
- Workflow Designer
- Process Automation
- User Management & Role-based Access
- Dashboard & Reporting

🔗 Download Joget DX
- You can download Joget DX Community Edition from the official website:
👉 https://www.joget.com/download/

Choose:
1. Joget DX Community Edition
2. Download installer (Windows / Linux / Mac)

2️⃣ System Overview
📌 Project Title
- Smart Expense Reimbursement System

📖 Purpose
- This system replaces traditional manual reimbursement processes with a modern low-code workflow automation system.

3️⃣ Problem Statement
- The traditional reimbursement system has several problems:

❌ Inefficiency of Manual Paperwork
- Paper forms can be lost or damaged
- Hard to retrieve old records

❌ Long Processing Time
- Waiting for physical signatures
- Email-based approvals

❌ High Risk of Human Error
- Manual calculation mistakes
- Duplicate claims
- Incorrect Excel entries

❌ No Real-Time Tracking
- Employees cannot see claim status

❌ Poor Financial Reporting
- Hard to aggregate expense data
- No real-time dashboards

4️⃣ Project Objectives

✅ Automate business process using workflow
✅ Implement role-based approval routing
✅ Provide real-time claim tracking
✅ Reduce calculation errors
✅ Provide dashboards & reports
✅ Improve operational efficiency

5️⃣ System Roles & Responsibilities
| Role         | Username | Password | Responsibilities                                                        |
| ------------ | -------- | -------- | ----------------------------------------------------------------------- |
| Admin        | admin    | admin    | Approves claims, sets approval limit, monitors system, set expense type |
| Finance Team | clark    | password | Processes payments                                                      |
| Employee     | cat      | password | Submit claims, upload receipts, check status                            |


6️⃣ Features Included
🔹 Workflow Automation

Claims automatically routed:
- Normal amount → Finance Team
- Exceed limit → Admin approval

🔹 Smart Approval Logic
- If claim exceeds admin limit → require Admin approval.

🔹 Dashboard Monitoring
Employees can see:
- Pending
- Waiting for Payment
- Completed
- Rejected

🔹 Automatic Calculation
- System auto-calculates totals to reduce human error.

🔹 Real-Time Reporting
- Charts and reports for spending analysis.

7️⃣ How to Download the Project from GitHub
1. Go to your GitHub repository.
2. Click Code.
3. Click Download ZIP.
4. Extract the ZIP file.
5. Locate the .jwa file (Joget Workflow Application file).

8️⃣ How to Import .JWA File into Joget DX (Step-by-Step)
Step 1 – Start Joget DX
1. Install Joget DX.
2. Start Joget Server.
3. Open browser and go to:
[http://localhost:8080/jw](http://localhost:8080/jw)

Step 2 – Login as Admin
Login using:
Username: admin
Password: admin

Step 3 – Go to App Center
1. Click App Center
2. Click Import App

Step 4 – Upload .JWA File
1. Click Upload
2. Select your APP_smart_expense_reimbursement_system-1-20260115150125.jwa
3. Click Import

Joget will automatically install:
- Forms
- Workflow
- User roles
- Dashboards
- Reports

Step 5 – Open the Application
1. Click the imported app.
2. Click Run App
3. The system is now ready to use.

9️⃣ How to Use the System (Role Guide)
👤 Employee (cat / password)
Submit Claim
1. Login as cat
2. Click Submit Expense Claim
3. Fill in Description, Expense Type, Amount, Upload Receipt
4. Click Submit

Check Status
Go to Dashboard:
- Pending
- Waiting for Payment
- Completed
- Rejected

💼 Finance Team (clark / password)
Make Transaction
1. Login as clark
2. Open Waiting For Transaction Claims
3. Process Payment And Upload Proof
4. Click Submit

👑 Admin (admin / admin)
Approve & Reject Claims
If claim exceeds limit:
- Admin can approve or reject before Finance processes

Set Approval Limit
Admin can:
- Configure amount threshold

View Reports
- View spending charts
- Monitor system performance

🔟 Workflow Summary
Employee Submit
- If amount ≤ limit → Finance → Payment → Completed
- If amount > limit → Admin Approval → Finance → Payment → Completed

1️⃣1️⃣ DevOps & Low-Code Concept Explanation (For Assignment)
🔹 Low-Code Implementation
Built using Joget DX:
- Drag & drop Form Builder
- Workflow Process Builder
- Role Mapping
- Built-in Reporting
No heavy programming required.

🔹 DevOps Concept Applied
- Version control using GitHub
- Application packaged as .jwa
- Easy deployment & migration
- Reusable workflow design
- Faster system updates

🎯 Conclusion
The Smart Expense Reimbursement System successfully:
- Eliminates manual paperwork
- Reduces processing delays
- Minimizes human error
- Provides transparency
- Improves reporting accuracy
- Increases operational efficiency

This project demonstrates how low-code platforms like Joget DX can modernize traditional business processes effectively.
