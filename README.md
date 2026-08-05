# 🤖 AI Resume Screening Agent

An AI-powered Resume Screening Automation built using **n8n**, **Google Gemini AI**, **Gmail API**, and **Google Sheets**. The workflow automatically processes resumes received via email, extracts candidate information, stores it in Google Sheets, and sends an acknowledgement email.

---

## 📌 Features

- 📩 Automatically monitors Gmail for new resume submissions.
- 📄 Downloads PDF resume attachments.
- 🤖 Extracts resume text using Gemini AI.
- 🧠 Uses AI to identify:
  - Name
  - Email
  - Phone Number
  - Skills
  - Education
  - Experience
- 📊 Stores structured candidate information in Google Sheets.
- ✉️ Sends an automated confirmation email to the applicant.
- ⚡ Fully automated with no manual intervention.

---

## 🛠 Tech Stack

- n8n
- Google Gemini AI
- Gmail API
- Google Sheets API
- JSON Schema
- JavaScript Expressions
- PDF Processing

---

## 🔄 Workflow

```text
Candidate
      │
      ▼
Send Resume via Gmail
      │
      ▼
Gmail Trigger
      │
      ▼
Get Email + Download Attachment
      │
      ▼
Extract Resume Text
      │
      ▼
Gemini AI
      │
      ▼
Structured Output Parser
      │
      ▼
Google Sheets
      │
      ▼
Confirmation Email
```

## 🚀 How It Works

### Step 1: Gmail Trigger
The workflow monitors a Gmail inbox for incoming emails with resume attachments.

### Step 2: Get Message
The email content and attached resume are downloaded.

### Step 3: Extract Resume
The attached PDF is converted into readable text.

### Step 4: AI Processing
Google Gemini AI analyzes the extracted resume and identifies:
- Name
- Email
- Phone
- Skills
- Education
- Experience

### Step 5: Structured Output
A JSON Schema ensures the AI always returns data in a consistent format.

### Step 6: Google Sheets
The extracted information is automatically stored in Google Sheets.

### Step 7: Confirmation Email
An acknowledgement email is automatically sent to the candidate.

---

## 💡 Future Improvements

- Resume scoring
- Job description matching
- Candidate ranking
- Duplicate resume detection
- HR Dashboard
- ATS Integration
- Database Support
- Candidate Analytics

---

## 🎯 Skills Demonstrated

- Workflow Automation
- Prompt Engineering
- AI Integration
- API Integration
- Data Extraction
- JSON Schema Design
- Google Workspace Automation
- Low-Code Development

---

## ⚠️ Note

This repository does **not** include API keys or OAuth credentials. Configure your own credentials after importing the workflow.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Anushka Vishwakarma**

GitHub: https://github.com/anushka-513


<img width="1856" height="847" alt="Screenshot 2026-08-05 235547" src="https://github.com/user-attachments/assets/dbcb7f43-1f29-4934-952f-87231369553e" />

