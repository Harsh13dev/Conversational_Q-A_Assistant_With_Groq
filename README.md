# Conversational Q&A Assistant with Groq

This project implements an **end-to-end conversational Q&A assistant with memory**, built using **LangChain** and powered by **Groq**. It provides a simple **Streamlit web interface** to interact with large language models efficiently.

---

## 🚀 Features
- **Conversational Q&A**: Engage in an interactive question-and-answer session.
- **Memory Support**: Maintains context across multiple turns in a conversation.
- **Groq Integration**: Leverages Groq for **fast and efficient LLM processing**.
- **Streamlit UI**: A user-friendly web interface for seamless interaction.

---

## 🛠 Technologies Used
- **[LangChain](https://www.langchain.com/)**: Framework for LLM-based applications.
- **LangChain-Groq**: Integration of LangChain with Groq models.
- **[Python-dotenv](https://pypi.org/project/python-dotenv/)**: For managing environment variables.
- **[Streamlit](https://streamlit.io/)**: Web app framework for ML and data apps.

---

## ⚙️ Setup and Installation

### ✅ Prerequisites
- Python **3.13** or higher

### 🔽 Steps to Install

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Harsh13dev/Conversational_Q-A_Assistant_With_Groq.git
   cd Conversational_Q-A_Assistant_With_Groq
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   or
   ```bash
   uv pip install -e .
   ```

3. **Get your Groq API Key**:
   - Visit [console.groq.com](https://console.groq.com) to obtain a **free API key**.

4. **Create a `.env` file**:
   Create a file named `.env` in the root directory and add:
   ```
   GROQ_API_KEY="your_groq_api_key_here"
   ```

5. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

---

## ▶️ Usage
1. After starting the app, open the local URL (usually `http://localhost:8501`).
2. Enter your **Groq API Key** in the sidebar.
3. Select your desired model (e.g., `llama3-8b-8192` or `gemma2-9b-it`).
4. Type your questions in the chat box and press **Enter** to interact.

---

## 📂 Project Structure
```
.
├── app.py                 # Streamlit application
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## 🛡 License
This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgments
- [Groq](https://groq.com/) for providing the LLM infrastructure
- [LangChain](https://www.langchain.com/) for the LLM framework
- [Streamlit](https://streamlit.io/) for the interactive UI
