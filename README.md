# Clinical Note CPT Coder & Optimizer

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Type](https://img.shields.io/badge/type-single--page--app-blue)
![License](https://img.shields.io/badge/license-MIT-purple)

Clinical Note CPT Coder & Optimizer is an AI-powered tool that analyzes clinical documentation to assign appropriate Evaluation & Management (E&M) and procedure CPT codes, score documentation completeness, and provide actionable recommendations to optimize note quality and reimbursement capture.

---

## 🩺 Features

- **E&M Level Scoring** — Automatically determines E&M visit level (99202–99215) based on MDM or time-based criteria
- **Documentation Completeness Score** — Grades note quality across HPI, ROS, Exam, Assessment, and Plan components
- **CPT Code Recommendations** — Suggests primary and add-on procedure codes with rationale
- **Optimization Tips** — Actionable suggestions to improve documentation and support a higher visit level
- **Patient Type Toggle** — Switch between new patient and established patient E&M frameworks
- **Color-Coded Scoring Cells** — Visual indicators for minimal, low, moderate, and high complexity
- **Tabbed Results View** — Organized output across Code Summary, Documentation Score, and Recommendations tabs
- **Fade-In Animations** — Smooth, professional UI transitions

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Edge, Firefox, Safari)
- No installation, build tools, or server required

### Run Locally
```bash
git clone https://github.com/your-username/ClinicalNoteCPTCoder.git
cd ClinicalNoteCPTCoder
open index.html
```

### Deploy to GitHub Pages
1. Push `index.html` to your repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Live at `https://your-username.github.io/ClinicalNoteCPTCoder`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Core application |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [Lucide Icons](https://lucide.dev/) | UI iconography |
| [Inter](https://fonts.google.com/specimen/Inter) | Typography |
| [AppSDK AI](https://github.com) | Clinical NLP & coding engine |

---

## 📁 Project Structure

```
ClinicalNoteCPTCoder/
└── index.html       # Complete self-contained application
```

---

## 📊 E&M Scoring Framework

The app evaluates notes using the **2021 AMA E&M guidelines**:

| MDM Level | Code Range | Complexity |
|---|---|---|
| Straightforward | 99202 / 99212 | Minimal |
| Low | 99203 / 99213 | Low |
| Moderate | 99204 / 99214 | Moderate |
| High | 99205 / 99215 | High |

---

## 🎯 Target Users

- Primary care and specialty physicians
- Advanced practice providers (NPs, PAs)
- Clinical documentation improvement (CDI) specialists
- Medical coding educators and trainees

---

## ⚠️ Disclaimer

This tool is intended to assist clinicians with documentation improvement and coding guidance. It does not replace a certified medical coder or compliance review. Always verify codes against current AMA CPT guidelines and payer policies.

---

## 📄 License

MIT © 2026

