# 🧾 **Invoice Extractor AI**

_An AI-powered web application that extracts structured data (like invoice number, dates, amounts, etc.) from PDF or image-based invoices using OCR and LLMs. Built with Python and Streamlit, the app transforms raw invoice files into clean, structured CSV/Word output with ease.._

## 🚀 Features

- **Upload** invoice files (PDF or image)
- _AI-based text recognition using LLMs_
- 📥 Download extracted data as **CSV or Word**

## 🧰 Tech Stack
* Layer			:	Tools / Libraries
* Frontend	:	Streamlit
* Backend		:	Python, Tesseract OCR, PyMuPDF/pdfplumber
* AI Models	:	Gemini Pro / Hugging Face Transformers
* Output		:	CSV, Word
* Deployment:	Streamlit Cloud (GitHub-based CI/CD)

## ⚙️ Installation
<b>1. Clone the Repository </b><br>
git clone https://github.com/yourusername/invoice-extractor.git <br>
cd invoice-extractor

<b>2. Set up Virtual Environment (Optional but Recommended) </b><br>
python -m venv venv <br>
source venv/bin/activate   # On Windows: venv\Scripts\activate

<b> 3. Install Dependencies </b><br>
pip install -r requirements.txt

<b> 4. Run the App </b><br>
streamlit run app.py

## 📦 Sample Invoices
You can download and test with this sample:

➡️ [Download sample_invoice.pdf](sample_files/sample_invoice.pdf)

## 🧪 Future Scope
* Add line-item parsing with table recognition
* Add multi-language OCR support
* Improve accuracy using fine-tuned document models
* Add invoice classification (e.g., utility, retail, telecom)
