# ✨ AI-Powered Text Summarizer & Keyword Extractor

## 👨‍🎓 Project Info
- **Name:** SANJAI.S  
- **Roll No:** 71762234039  
- **Department:** M.Sc. Artificial Intelligence and Machine Learning  
- **Role(s) Applied:** AI & ML Intern  
- **Email ID:** sanjai4152@gmail.com  

## 📁 Project Access
- **Project Files:** [Google Drive Folder](https://drive.google.com/file/d/1gtlVuIhgDxklOMGVdlSma18Wel2P8qpV/view?usp=sharing)  
- **Colab Demo (with Streamlit):** [Google Colab Link](https://colab.research.google.com/drive/1Pqov84a2IfsSCPTJ14giCfNvUBlMBEcM?usp=sharing)  
- **Live Streamlit App:** [Streamlit App](https://c49d-34-27-5-152.ngrok-free.app/)

---

## 🧠 Problem Statement
To develop a lightweight AI-powered tool using HuggingFace and other ML libraries to:
- Summarize long paragraphs into concise **3-line summaries**.
- Extract the **top 5 relevant keywords** from a given input paragraph.

---

## ⚙️ Procedure

### 1. Library Setup
Installed the required libraries:
- `transformers`
- `torch`
- `keybert`
- `sentence-transformers`
- `streamlit`
- `pyngrok`

### 2. Model Selection
Users can choose from three summarization models:
- **T5** – General-purpose summarization
- **BART** – Balanced and robust
- **PEGASUS** – Best for abstractive summarization

### 3. Frontend Development
- Built using **Streamlit** with **custom CSS** for styling.
- Users can:
  - Paste a paragraph
  - Select the summarization model
  - Click "Summarize Text"
  - View the summary and keyword extraction results

### 4. Keyword Extraction
- Implemented using **KeyBERT** + **SentenceTransformer (all-mpnet-base-v2)**.
- Used **Maximal Marginal Relevance (MMR)** for diverse, relevant keywords.

### 5. Deployment
- Hosted using **Ngrok**.
- Automatically kills prior Streamlit sessions to avoid port conflicts.

---

## 💻 Code Overview

The entire logic resides in `summarizer_app.py` and includes:
- Text cleaning with regex
- Summarization using HuggingFace pipelines
- Keyword extraction via KeyBERT
- A vibrant UI using inline CSS in Streamlit

---

## ✅ Output
- ✔️ Concise 3-line summaries
- ✔️ Responsive, elegant UI
- ✔️ 5–10 semantically relevant keywords
- ✔️ Word count comparison (original vs summary)
- ✔️ Fast execution with GPU/CPU auto-detection
![image](https://github.com/user-attachments/assets/5495c564-62b0-4dce-9e43-955632dbda86)

![image](https://github.com/user-attachments/assets/d3a5b861-6fbc-4c98-bea3-8faf870b8d42)

![image](https://github.com/user-attachments/assets/14ddacbb-384c-4b15-a05e-9060b24e283a)



## 🔍 Inference
This project illustrates how state-of-the-art transformer models can:
- Condense long texts effectively
- Capture semantic essence via keyword extraction
- PEGASUS excels in abstraction, while T5 provides balanced results
- MMR enhances keyword diversity and coverage

---

## 🏁 Result

A deployable micro-utility useful for:
- 📘 Students summarizing academic material  
- 💼 Professionals distilling reports  
- 👨‍💻 Developers exploring NLP tools  

This aligns with the objective of creating a practical, scalable AI micro-utility using modern NLP architectures.

---

## 🧾 Explanation

- Utilizes **HuggingFace transformers** for summarization via the `pipeline` API.
- Keyword extraction powered by **KeyBERT** and **SentenceTransformer**.
- UI developed in Streamlit with colorful CSS enhancements.
- Public hosting enabled via **Ngrok**, avoiding full cloud deployment.

---

## 🚀 Scope for Improvement
- 📄 Add support for file uploads (PDF/DOCX)
- 🔧 Allow user-defined summary length via sliders
- 📊 Visualize keyword importance using bar charts
- 🌐 Add multi-language translation support
- 🔐 Implement user authentication & summary history saving

---

## 🙌 Ideal For
- Students, writers, and professionals needing quick content condensation.
- Developers experimenting with summarization and keyword extraction techniques.

---

