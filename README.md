# robust-ai-resume-analyzer
⚡ AI-powered resume analyzer with OCR, PDF/DOCX support, skill detection, and job description matching. Built with Python &amp; Gradio.

# ⚡ Robust AI Resume Analyzer

Analyze resumes with AI in multiple formats (PDF, DOCX, TXT, Images) and match them to job descriptions.

## Features
- Extract text from PDFs, Word documents, text files, and images (PNG/JPG/TIFF)
- OCR support via `pytesseract` for scanned documents
- Clean and preprocess text using NLTK stopwords
- Detect relevant skills (customizable)
- Compute similarity score between resume and job description
- Easy web interface via Gradio

## Installation
```bash
pip install -r requirements.txt
