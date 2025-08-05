# 📄 DocuSense: Intelligent PDF Management

2023 Project. An intelligent PDF management and retrieval tool using NLP, clustering, and a content-based search engine to turn digital clutter into a queryable, organized library.

---

## 🎯 The Problem: Taming Digital Chaos

Students, researchers, and professionals are drowning in disorganized PDFs—lecture notes, research papers, and personal documents. This "digital clutter" leads to inefficient search, wasted storage from duplicates, and a lack of insight into the information you own. DocuSense was built to solve this.

## ✨ Key Features

- **📊 Analytics Dashboard:** Get instant insights on your PDF library, including total files, memory usage, and one-click duplicate detection.
- ** duplicates with MD5 hashing.
- **🧠 Content-Based Search:** A powerful search engine built with **TF-IDF and Cosine Similarity** that looks *inside* your documents to find what you need, not just matching filenames.
- **🤖 Automatic Clustering:** Uses **K-Means Clustering** to automatically group similar documents (e.g., all research papers on a specific topic, all resumes) without any manual folder creation.
- **📄 OCR Integration:** Leverages `Pytesseract` to extract text from scanned documents, ensuring no information is left behind.

## 🛠️ Tech Stack

- **Core Libraries:** Python, Pandas, NLTK, Scikit-learn, PyPDF2
- **Algorithms:** K-Means Clustering, TF-IDF Vectorization, Cosine Similarity
- **Utilities:** Jupyter Notebook, hashlib (MD5), Pytesseract (OCR)

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone https://github.com/mksree-gh/DocuSense.git
    cd DocuSense
    ```
2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Launch Jupyter Notebook and open the `DocuSense.ipynb` file.
    ```bash
    jupyter notebook
    ```

## 🔮 Future Roadmap

- **Text Summarization:** Integrate a transformer model to provide quick summaries of documents.
- **Supervised Classification:** Train a model on user-generated labels for smarter, personalized tagging.
- **Cloud Integration:** Connect directly to Google Drive, Dropbox, and OneDrive.