# 🛡️ IHRA Workplace Psychology Questionnaire

> **BLM Batch – Group 5 | Institute of Human Resource Advancement (IHRA) – University of Colombo**

A bilingual (English / සිංහල) digital workplace psychology survey designed for insurance company employees. Responses are collected and saved automatically to Google Sheets.

---

## 🌐 Live Survey

👉 **[Click here to open the questionnaire](https://yourusername.github.io/ihra-questionnaire/)**

> *(Replace the link above with your actual GitHub Pages URL after deployment)*

---

## 📋 About This Survey

This questionnaire is part of an academic assignment for the **Bachelor of Labour and Management (BLM) programme** at IHRA – University of Colombo.

The survey investigates the relationship between **organizational culture, leadership style, motivation, and employee satisfaction** in Sri Lankan insurance organizations.

All responses are **completely confidential and anonymous**.

---

## 📂 Survey Sections

| Section | Topic | Questions |
|---------|-------|-----------|
| **A** | Basic Information | Designation, Service Period, Department |
| **B** | Organizational Culture | Q04 – Q08 (Likert 1–5) |
| **C** | Leadership Style | Q09 – Q13 (Likert 1–5) |
| **D** | Motivation & Incentives | Q14 – Q18 (Likert 1–5) |
| **E** | Employee Satisfaction | Q19 – Q23 (Likert 1–5) |
| **F** | Workplace Issues | Checkboxes (multi-select) |
| **G** | Open Comments | Optional suggestions |

---

## ✨ Features

- 🌍 **Fully bilingual** — English & සිංහල (Sinhala), one language at a time
- 📱 **Mobile responsive** — works on all screen sizes
- 💾 **Auto-saves to Google Sheets** — real-time data collection
- 🎉 **Animated thank-you screen** — confetti celebration on completion
- 🔒 **Anonymous & confidential** — no personal identification collected
- ✅ **Validation** — ensures all required questions are answered before proceeding

---

## 🛠️ Technology Stack

| Component | Technology |
|-----------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Backend | Google Apps Script |
| Database | Google Sheets |
| Hosting | GitHub Pages (free) |
| Fonts | Google Fonts (DM Sans, Playfair Display, Noto Sans Sinhala) |

---

## 📁 Project Files

```
ihra-questionnaire/
│
├── index.html        ← The complete survey (upload this to GitHub)
└── README.md         ← This file
```

> **Note:** `code.gs` (Google Apps Script backend) is hosted separately inside Google Apps Script — it is **not** uploaded to this repository.

---

## ⚙️ Setup Instructions

### 1. Google Apps Script (Backend)

1. Go to [script.google.com](https://script.google.com) and create a new project
2. Paste the contents of `code.gs` into the editor
3. Create an HTML file named `index` and paste `index.html` contents
4. Click **Deploy → New Deployment → Web App**
   - Execute as: **Me**
   - Who has access: **Anyone**
5. Copy the **Web App URL**

### 2. GitHub Pages (Frontend)

1. Upload `index.html` to this repository
2. Go to **Settings → Pages**
3. Set Branch to `main` and click **Save**
4. Your site will be live at `https://yourusername.github.io/ihra-questionnaire/`

### 3. Connect Frontend to Backend

In `index.html`, find this line and replace with your Apps Script URL:

```javascript
const URL = 'YOUR_APPS_SCRIPT_WEB_APP_URL_HERE';
```

Replace with:

```javascript
const URL = 'https://script.google.com/macros/s/YOUR_DEPLOYMENT_ID/exec';
```

---

## 📊 Data Collection

Responses are saved to the connected **Google Sheet** with the following columns:

`Timestamp` · `Language` · `Q01–Q03` (Basic Info) · `Q04–Q08` (Culture) · `Q09–Q13` (Leadership) · `Q14–Q18` (Motivation) · `Q19–Q23` (Satisfaction) · `F_Checkboxes` · `G_Suggestions`

---

## 👥 Team

| Role | Name |
|------|------|
| 📝 Survey Design | Thilina Jayasooriya |
| 💻 System Design | Thinith Madara |
| 🎓 Programme | BLM Batch – Group 5 |
| 🏛️ Institution | IHRA – University of Colombo |

---

## 📄 License

This project was created for academic purposes as part of the IHRA BLM programme.  
© 2025 BLM Batch Group 5 – IHRA, University of Colombo. All rights reserved.
