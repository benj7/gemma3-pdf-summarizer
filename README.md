# 📄 AI-Powered PDF Summarizer

🚀 **AI-Powered PDF Summarizer** is a tool that extracts and summarizes **research papers** from **ArXiv PDFs** using **Ollama (Gemma 3 LLM)**. The system provides structured, downloadable summaries to help researchers and professionals quickly grasp key findings.

![PDF Summarizer UI](https://github.com/arjunprabhulal/gemma3_pdf_summarizer/raw/main/PDF_Summarizer.png)

---

## 🛠 Features

- 🌐 **Input an ArXiv PDF URL** to fetch and summarize papers.
- 📑 **Extracts technical content** (architecture, implementation, results).
- 🔍 **Optimized for large text processing** with **parallel summarization**.
- 🎨 **Modern UI** built with **Streamlit**.
- 📥 **Download summary as a Markdown file**.

---

## 🚀 Tech Stack

| Component       | Technology |
|----------------|------------|
| **Frontend**   | [Streamlit](https://streamlit.io/) |
| **Backend**    | [FastAPI](https://fastapi.tiangolo.com/) |
| **LLM Model**  | [Ollama (Gemma 3)](https://ollama.com/) |
| **PDF Parsing**| [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/) |
| **Chunking**   | [LangChain RecursiveCharacterTextSplitter](https://python.langchain.com/docs/modules/data_connection/document_transformers/text_splitters/) |

---

## 🎬 Demo

1️⃣ **Enter an ArXiv PDF URL**  
2️⃣ **Click "Summarize PDF"** 🚀  
3️⃣ **Get a structured summary** with **technical insights** 📝  
4️⃣ **Download as Markdown** 📥  

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/arjunprahulal/gemma3_pdf_summarizer.git
cd gemma3_pdf_summarizer
