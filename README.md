# 🤖 AI Resume & Cover Letter Generator (Streamlit + Gemini)

This AI-powered web application allows users to **refine resumes** and **generate cover letters** tailored to specific job descriptions using **Google Gemini AI**. It supports both **English and French**, and ensures outputs are **ATS-friendly** and professionally formatted as downloadable PDFs.

---

## ✨ Features

✅ Upload your resume (PDF or DOCX)
✅ Extract and edit personal details
✅ Paste or fetch job description from a URL
✅ Detect language automatically (English or French)
✅ Extract top keywords from resume and job description
✅ Refine resume sections using Gemini AI
✅ Generate a professional cover letter in JSON format
✅ Create and download beautiful PDF documents for both resume and cover letter
✅ Fully built with [Streamlit](https://streamlit.io/)

---



---

## 🚀 Getting Started


### 1. Set up your environment

Install required dependencies:

```bash
pip install -r requirements.txt
```

### 2. Add your Gemini API key

You will need a Google Gemini API key.
Get one from [Google AI Studio](https://makersuite.google.com/app).

Paste the key into the **sidebar input** when running the app.

---

## 🧐 Tech Stack

* **Python**
* **Streamlit**
* **Google Gemini API (via `google.generativeai`)**
* **NLTK** – for language and keyword processing
* **Langdetect** – automatic language detection
* **ReportLab** – PDF generation
* **BeautifulSoup** – scraping JD from URLs
* **PyPDF2 / python-docx** – file handling for resumes

---

## 📈 Output Formats

* **Refined Resume PDF**
* **Cover Letter PDF**
* Both are styled for ATS and readability.

---

## 📋 To-Do

* [ ] Add OpenAI fallback support (currently commented)
* [ ] Integrate with Django frontend (for client delivery)
* [ ] Export .docx formats
* [ ] Add multilingual support beyond English/French
* [ ] Unit tests and CI setup

---

## 🤝 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to change.

---

## 🛡️ License

This project is licensed under the MIT License.

---

## 🤝 Author

**Aditya** – [LinkedIn](https://linkedin.com/in/your-profile)
