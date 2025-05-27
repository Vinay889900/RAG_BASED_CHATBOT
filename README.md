# RAG-Based Chatbot 🤖📚

A Retrieval-Augmented Generation (RAG) chatbot that combines the power of Large Language Models (LLMs) with vector-based document retrieval to deliver accurate, context-aware responses.

---

## 🚀 Features

- 📄 **Document-Aware Question Answering**
- 🧠 **Powered by OpenAI LLMs (e.g., GPT-3.5 / GPT-4)**
- 📚 **Custom Knowledge Base Support**
- 🔍 **Vector Search with FAISS**
- ⚙️ **LangChain-Powered RAG Pipeline**
- 🖥️ **User Interface with Streamlit**

---

## 🛠️ Tech Stack

- Python
- [LangChain](https://www.langchain.com/)
- [FAISS (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)
- [OpenAI API](https://platform.openai.com/)
- Streamlit (for the frontend)

---

## 🧩 How It Works

1. **Document Upload**: User uploads PDFs or text documents.
2. **Text Splitting & Embedding**: The documents are chunked and converted into embeddings.
3. **Vector Storage**: Embeddings are stored in a FAISS index.
4. **Query**: User inputs a question.
5. **Retrieval**: Relevant document chunks are retrieved from the FAISS index.
6. **Generation**: Retrieved context and user query are passed to an LLM to generate the final response.

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/rag-chatbot.git
cd rag-chatbot

# Install dependencies
pip install -r requirements.txt

🔐 API Keys
Create a .env file in the root directory and add:

env
Copy
Edit
OPENAI_API_KEY=your_openai_api_key_here
▶️ Running the App
bash
Copy
Edit
streamlit run app.py
💡 Use Cases
Internal company knowledge bots

AI-based academic assistants

Customer support automation

Domain-specific chatbots
