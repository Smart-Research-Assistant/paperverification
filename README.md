## 🚀 Quick Start

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/frauddetection.git
cd frauddetection
```

### **2. Install Dependencies**
Make sure you have Python installed. Then, install the required Python libraries:
```bash
pip install -r requirements.txt
```

### **3. Run the Application**
Start the Flask server:
```bash
python server/app.py
```

Open your browser and navigate to `http://127.0.0.1:5000` to access the web app.

---

## 🧑‍💻 How to Use

1. **Upload Your File:** Drag and drop or select a PDF file to upload.
2. **Click Analyze:** Hit the "Analyze" button to start the AI-based analysis.
3. **View the Result:** See whether the document is AI-generated along with an explanation.

---

## 🤖 Technology Stack

- **Backend:**
  - [Flask](https://flask.palletsprojects.com/) for server-side logic
  - [FAISS](https://faiss.ai/) for vector search
  - [Hugging Face Transformers](https://huggingface.co/transformers/) for embeddings and LLMs

- **Frontend:**
  - HTML, CSS, JavaScript for a responsive and intuitive web interface

- **AI Models:**
  - Sentence Transformers: `all-MiniLM-L6-v2`
  - LLM: `Falcon-7b-instruct` (or any Hugging Face-compatible model)

---

## 📁 Sample Files

- Place your test PDF files in the `/uploads` directory.
- The FAISS vector database is stored in the `/vector_store` directory.

---

## 🤝 Contributing

We welcome contributions! Feel free to:

- Submit issues
- Suggest new features
- Fork and create pull requests

### **Steps to Contribute**
1. Fork this repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add a feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

---

## 🌍 Connect With Us

- **GitHub:** [frauddetection](https://github.com/frauddtection)
- **LinkedIn:** [************](------------)
<!-- - **Email:** support@frauddetection.io -->

---
