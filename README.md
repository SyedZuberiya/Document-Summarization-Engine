# 📚 Dual-Mode Summarization System (Extractive + Abstractive)

This project is a **NLP-based document summarization system** that allows users to upload `.pdf` or `.txt` files and get both **extractive summaries** (via TextRank) and **abstractive summaries** (via BART).

---

## 🚀 Features

🔹 Upload support for PDF or TXT  
🔹 Text extraction from PDFs using `PyMuPDF`  
🔹 **Extractive summarization** using `TextRank` (Sumy)  
🔹 **Abstractive summarization** using Hugging Face `facebook/bart-large-cnn`  
🔹 Sentence chunking to handle large documents  
🔹 Saves both summaries as `.md` files  

---

## 🛠 Technologies Used

| Library / Tool       | Purpose                                      |
|----------------------|----------------------------------------------|
| `pymupdf (fitz)`     | PDF text extraction                          |
| `sumy`               | Extractive summarization using TextRank      |
| `transformers`       | Pretrained summarization model (BART)        |
| `torch`              | Backend for transformers                     |
| `sentencepiece`      | Tokenizer dependency for some transformer models |
| `ipywidgets`         | Upload interface in Jupyter notebook         |
| `nltk`               | Sentence tokenization                        |

---

**Results**
![image](https://github.com/user-attachments/assets/79f8c114-570d-4e69-afd1-91ebd1612c1c)
![image](https://github.com/user-attachments/assets/a7debc18-2596-4fb4-919d-17dfe79e2dde)
![image](https://github.com/user-attachments/assets/cbfa960c-22fe-4c51-ae65-d15b9b61b36a)



## 🧩 Project Structure

.
├── summarizer.py # Main script
├── requirements.txt # Python dependencies
└── README.md # Project overview

🙋 Author
Developed by Syeda Zuberiya
