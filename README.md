# 📄 RAG-Based PDF Chat Assistant

An AI-powered **Retrieval-Augmented Generation (RAG)** application that enables users to upload PDF documents and ask questions in natural language. The system retrieves relevant information from uploaded documents using semantic search and generates accurate, context-aware responses using Large Language Models (LLMs).

---

## 🚀 Features

- 📄 Upload and process PDF documents
- ✂️ Automatic text extraction and semantic chunking
- 🧠 Generate embeddings using OpenAI Embedding Models
- 🗄️ Store embeddings in Qdrant Vector Database
- 🔍 Semantic similarity search for relevant document context
- 🤖 AI-powered question answering using OpenAI LLMs
- 💬 Interactive Streamlit web interface
- ⚡ Background document ingestion with Inngest workflows

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Frontend | Streamlit |
| AI Framework | LlamaIndex |
| LLM | OpenAI GPT |
| Embeddings | OpenAI Embeddings |
| Vector Database | Qdrant |
| Workflow Engine | Inngest |
| AI Technique | Retrieval-Augmented Generation (RAG) |

---

## 🏗️ System Architecture

```text
                 PDF Upload
                      │
                      ▼
             PDF Text Extraction
                      │
                      ▼
              Text Chunking
                      │
                      ▼
           OpenAI Embedding Model
                      │
                      ▼
         Qdrant Vector Database
                      │
      User Question   │
             │        │
             ▼        ▼
      Semantic Similarity Search
                      │
          Relevant Context Retrieved
                      │
                      ▼
 Prompt + Retrieved Context + User Question
                      │
                      ▼
             OpenAI Language Model
                      │
                      ▼
             Context-Aware Answer
```

---

## 🔄 Workflow

1. Upload a PDF document.
2. Extract text from the document.
3. Split the text into semantic chunks.
4. Generate embeddings using OpenAI.
5. Store embeddings in the Qdrant Vector Database.
6. Ask questions about the uploaded document.
7. Retrieve the most relevant chunks using semantic search.
8. Inject the retrieved context into the LLM prompt.
9. Generate an accurate, context-aware response.

---

## 💡 Key Concepts

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings
- Prompt Engineering
- Context Injection
- Large Language Models (LLMs)
- Vector Databases

---

## 🎯 Use Cases

- AI-powered document assistant
- Enterprise knowledge base
- Research paper analysis
- Policy and legal document search
- Technical documentation assistant
- Internal company knowledge retrieval

---

## 🚀 Future Improvements

- Multiple document support
- Chat history and memory
- Source citations with page numbers
- Hybrid keyword + semantic search
- Local LLM support (Ollama/Llama)
- User authentication
- Document summarization
- Support for DOCX, TXT, and HTML files

---

## 👨‍💻 Author

**Vaishnav M**
