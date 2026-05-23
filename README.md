# 🧠 LangChain Complete Guide & Implementations

A **comprehensive, hands-on LangChain repository** covering **all core and advanced concepts** required to build modern LLM-powered applications — from **basic LLM usage** to **RAG pipelines, agents, tools, and chatbots**.

This repository is structured as a **learning + reference hub**, with each folder focusing on a specific LangChain concept and containing **clear, runnable examples**.

---

## 📌 What This Repository Covers

✔ Large Language Models (LLMs)
✔ Chat Models
✔ Embeddings
✔ Prompt Engineering
✔ Output Parsers
✔ Text Splitters
✔ Vector Stores
✔ Retrievers
✔ Chains & Runnables
✔ Tools & Tool Calling
✔ Agents
✔ RAG (Retrieval-Augmented Generation)
✔ YouTube Chatbot
✔ Document Loaders

---

## 🗂 Repository Structure

```bash
.
├── 1.LLMs/                     # Basic LLM usage
├── 2.ChatModels/               # Chat-based LLMs
├── 3.EmbeddedModels/           # Embeddings generation
├── 4.Prompts/                  # Prompt templates & engineering
├── 5.with_structured_outputs/  # Structured LLM outputs
├── 6.Output_parser/            # Output parsers
├── 7.Chains/                   # Chains (LLMChain, Sequential, etc.)
├── 8.Runnable/                 # Runnable interface
├── 9.Runnable_primitives/      # RunnablePassthrough, Parallel, Lambda
├── 10.Doc_loader/              # Document loaders (PDF, text, web)
├── 11.Text_splitters/          # Chunking strategies
├── 12.Vector_store/            # FAISS & vector databases
├── 13.Retrievers/              # Similarity & MMR retrieval
├── 14.Langchain_tools/         # Built-in & custom tools
├── 15.Tool_calling/            # Tool calling with LLMs
├── AI Agent/                   # Agent-based workflows
├── Yt_chatbot/                 # YouTube transcript chatbot (RAG)
├── docloaderpdfs/              # Sample PDF documents
├── prompts_ui.py               # Prompt UI utility
├── search.py                   # Search-based examples
```

---

## 🚀 Key Highlights

### 🔹 Modular Learning

Each folder is **self-contained** and focuses on **one LangChain concept**, making it easy to learn step by step.

### 🔹 Real-World Patterns

Implements **production-style pipelines**:

* RAG
* Agents
* Tool calling
* Parallel chains
* Context-grounded QA

### 🔹 Beginner → Advanced

Suitable for:

* Beginners learning LangChain
* Intermediate developers building RAG apps
* Advanced users implementing agents and tools

---

## 🧠 Technologies Used

* **Python 3.9+**
* **LangChain**
* **OpenAI / ChatOpenAI**
* **FAISS**
* **YouTube Transcript API**
* **tiktoken**
* **python-dotenv**
* **Jupyter Notebooks**

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/langchain-complete-guide.git
cd langchain-complete-guide
```

---

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate  # macOS / Linux
venv\Scripts\activate     # Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not present:

```bash
pip install langchain langchain-community langchain-openai \
            faiss-cpu tiktoken python-dotenv \
            youtube-transcript-api
```

---

### 4️⃣ Set Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

⚠️ **Never commit your API keys**

---

## 🧪 Example Use Cases Included

* 🔍 Ask questions about YouTube videos
* 📄 Chat with PDFs using RAG
* 🧠 Build custom LLM chains
* 🤖 Create AI agents with tools
* ⚡ Parallel and composable chains
* 🧾 Structured JSON outputs from LLMs

---

## 📚 Learning Path Recommendation

1️⃣ LLMs → ChatModels
2️⃣ Prompts → Output Parsers
3️⃣ Text Splitters → Vector Stores
4️⃣ Retrievers → Chains
5️⃣ Runnables → Tool Calling
6️⃣ Agents → RAG Applications

---

## 🛡️ Best Practices Demonstrated

* Context-only answering (no hallucinations)
* Chunk overlap for semantic continuity
* Low-temperature QA
* Modular chain composition
* Clean separation of concerns

---

## 🔮 Future Enhancements

* Streamlit / Flask UI
* Multi-document RAG
* Persistent vector databases
* Agent memory
* Evaluation & tracing
* Open-source LLM support

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🌟 Author

**Ruchin203**
LangChain | RAG | AI Agents | LLM Engineering

---

### 🧠 Learn LangChain by building real systems

**From prompts → agents → production-ready AI apps 🚀**

---

