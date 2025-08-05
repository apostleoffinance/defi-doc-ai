# Free Document Q&A with Conversation Memory

A **free, privacy-first PDF Question & Answer app** powered by:
- [Groq API](https://console.groq.com) for fast LLM inference (free tier)
- [HuggingFace Sentence Transformers](https://www.sbert.net/) for local embeddings
- [Streamlit](https://streamlit.io/) for the web interface
- [FAISS](https://github.com/facebookresearch/faiss) for local vector search
- [LangChain](https://python.langchain.com/) for document processing

**Total cost: $0.00 — No credit card required!**

---

## 🚀 Features

- **Document Q&A:** Upload any PDF and ask questions about its content.
- **Conversation Memory:** The AI remembers your previous questions and answers.
- **Privacy First:** Your documents are processed locally; only relevant chunks are sent to the API.
- **Lightning Fast:** Groq's inference is typically under 1 second.
- **No Hidden Costs:** 100% free APIs, no credit card required.

---

## 🛠️ Installation

1. **Clone this repository:**
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```

2. **Create and activate a virtual environment (recommended):**
    ```bash
    python3 -m venv defi-doc
    source defi-doc/bin/activate
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up your `.env` file:**
    - Create a `.env` file in the project root with your Groq API key:
      ```
      GROQ_API_KEY=gsk_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
      ```

---

## 🏃‍♂️ Usage

1. **Start the Streamlit app:**
    ```bash
    streamlit run defi_doc.py
    ```

2. **Open your browser** to [http://localhost:8501](http://localhost:8501).

3. **Enter your Groq API key** in the sidebar (or set it in `.env`).

4. **Upload a PDF** and start asking questions!

---

## 💡 Example Questions

- "What is this document about?"
- "Who are the main authors?"
- "Can you elaborate on that?" (references previous answer)
- "How does it compare to what we discussed earlier?"

---

## 📦 Requirements

See [`requirements.txt`](./requirements.txt) for all dependencies.

---

## 📝 Notes

- Only relevant chunks of your document are sent to the Groq API for answering.
- All processing and embedding generation happens locally for privacy.
- For best results, use clear and specific questions.

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- [Groq](https://groq.com/)
- [HuggingFace](https://huggingface.co/)
- [Streamlit](https://streamlit.io/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [LangChain](https://python.langchain.com/)

---

**Enjoy your free, blazing-fast document Q&A