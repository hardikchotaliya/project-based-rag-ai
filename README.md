# DeepSeek RAG Agents UI

A **Project-Based RAG AI** implementation using **DeepSeek R1** and **ChromaDB**, built with **Streamlit** for an interactive chatbot UI.

---

## 🚀 Features
- **Retrieval-Augmented Generation (RAG)** for context-aware responses.
- **DeepSeek R1** as the LLM for generating answers.
- **ChromaDB** as the vector store for efficient document retrieval.
- **Nomic Embed Text** for embedding knowledge into a searchable format.
- **Streamlit UI** for easy interaction with the AI chatbot.

---

## 📂 Project Structure
```
.
├── deepseek-rag-agents-ui.py  # Main Streamlit App
├── requirements.txt           # Dependencies
├── istqb-ctfl.pdf             # Sample knowledge document
└── README.md                  # Project Documentation
```

---

## 🛠️ Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/project-based-rag-ai.git
cd project-based-rag-ai
```

### **2️⃣ Install Dependencies**
Make sure you have Python **3.8+** installed.
- Install Python
- Install Ollama

### **3️⃣ Start Ollama (Locally)**
Ensure you have **Ollama** installed and running:
```bash
#Install Ollama
```

Download DeepSeek R1:
```bash
ollama pull deepseek-r1:latest
```

Download Nomic Embed models:
```bash
ollama pull nomic-embed-text:latest
```

Install required packages:
```bash
pip install "praisonaiagents[knowledge]" ollama streamlit
```

Now Set your OpenAI API key just the requirement for SDK:
```bash
export OPENAI_BASE_URL=http://localhost:11434/v1
export OPENAI_API_KEY=fake-key
```

### **4️⃣ Run the Application**
```bash
streamlit run deepseek-rag-agents-ui.py
```

---

## 🏗️ How It Works
1. **Loads Knowledge** – Uses `sample.pdf` For Example `istqb-ctfl.pdf` for retrieval-based answering.
2. **Embeds Data** – Utilizes **Nomic Embed Text** for vectorized search.
3. **Retrieves Relevant Info** – Searches **ChromaDB** for the most relevant content.
4. **Generates Responses** – Feeds retrieved data into **DeepSeek R1** for contextual answers.

---

## 📌 Example Usage
1. Run the app and open the Streamlit UI.
2. Ask a question related to the uploaded document.
3. Get AI-generated responses based on retrieved knowledge!

---

## 🔥 Future Enhancements
- Will Add support for multiple document uploads.
- Will Improve UI/UX for better user experience.
- Will Deploy as a cloud-hosted RAG AI service.

---

## 📜 License
MIT License - Feel free to use and modify this project.

---

## 🤝 Contributing
Pull requests are welcome! If you'd like to improve the project, feel free to fork and submit changes.

---

## 📞 Contact
For questions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/hardikchotaliya/) or create an issue in this repository.

Happy coding! 🚀

