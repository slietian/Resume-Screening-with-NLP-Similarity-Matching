# 🤖 Resume Screening & Skill Matching Tool


An automated **Resume Screening application** built using **Python and Streamlit**.  
This project helps in shortlisting resumes by extracting important candidate details and matching them against a given **Job Description (JD)**.  
The results can be viewed in a tabular format and exported as an **Excel file**.

---

## 🚀 Features

- Upload multiple PDF resumes
- Paste job description text
- Automatically extract:
  - Email ID
  - Phone Number
  - Location
- Calculate resume–JD match score
- Display results in an interactive table
- Export results as `.xlsx` file
- Simple and user-friendly interface

---

## 🧠 How It Works

1. Resume PDFs are uploaded through the interface  
2. Text is extracted using PDF parsing  
3. Job description text is analyzed  
4. Resume content is compared with JD using similarity logic  
5. A match percentage is generated for each resume  
6. Results are displayed and can be downloaded as Excel  

This simulates the **initial HR screening process** used in real recruitment workflows.

---

## 🛠 Tech Stack

- **Frontend**: Streamlit  
- **Backend**: Python  
- **Resume Parsing**: PyMuPDF (fitz)  
- **Data Handling**: Pandas  
- **Similarity Matching**: difflib  
- **Excel Export**: OpenPyXL  

---

## 📦 Libraries Used

- `streamlit`
- `pandas`
- `fitz` (PyMuPDF)
- `re`
- `difflib`
- `openpyxl`
- `io`
- `base64`

---

## ▶️ Run the Project Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/resume-skill-matcher.git
cd resume-skill-matcher
