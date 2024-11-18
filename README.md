# 📘 Resume Matcher and Skill Extractor

Resume Matcher is an innovative Python project tailored to simplify and enhance the hiring process. By leveraging **Natural Language Processing (NLP)** and **BERT embeddings**, this tool identifies key skills and ranks resumes based on their alignment with job descriptions. With support for parsing PDFs and an intuitive GUI, Resume Matcher bridges the gap between recruiters and candidates efficiently.

---

## 📜 Table of Contents
- Features
- Tech Stack
- File Descriptions
- Usage
- Future Enhancements
---

## ✨ Features

1. **Skill Extraction**:
   - Extracts job-relevant skills from resumes using predefined skill dictionaries and NLP techniques.
   - Handles both structured and unstructured text formats.

2. **Semantic Matching**:
   - Employs **BERT embeddings** to calculate similarity scores between resumes and job descriptions.
   - Provides ranked results to streamline candidate shortlisting.

3. **PDF Parsing**:
   - Reads and preprocesses resumes directly from PDF files.
   - Cleans text by removing unwanted elements like special characters, emails, and URLs.

4. **Interactive GUI**:
   - Allows users to upload job descriptions and resumes effortlessly.
   - Displays analyzed results in an easy-to-read format.

5. **Customizable Framework**:
   - Enables users to update skill dictionaries and refine matching parameters.

---

## 🛠️ Tech Stack

- **Python**: For backend processing and NLP tasks.
- **spaCy**: Handles tokenization, named entity recognition, and skill extraction.
- **Transformers**: Implements BERT-based embeddings for semantic similarity.
- **PyTorch**: Backend for processing BERT models.
- **Tkinter**: Framework for building a user-friendly GUI.
- **PyPDF2**: Extracts text from PDF resumes for further analysis.

---

## 📂 File Descriptions

### 1. **`BOW.ipynb`** (Bag of Words Approach)
This notebook focuses on:
- Extracting and preprocessing text from PDF resumes.
- Using a dictionary-based approach to match and highlight skills in resumes.
- Implementing an interactive GUI where users can:
  - Paste job descriptions.
  - Upload a folder of resumes.
  - View extracted skills and matching scores.

### 2. **`BERT.ipynb`**
This notebook implements:
- Advanced semantic similarity scoring using **BERT embeddings**.
- Preprocessing job descriptions and resumes for embedding generation.
- Computing cosine similarity scores to rank resumes based on their relevance.
- Detailed visualization of similarity metrics.

---

### Thank you for exploring Resume Matcher! 🚀
