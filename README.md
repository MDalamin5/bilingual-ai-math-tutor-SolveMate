# Bilingual AI Math Tutor - SolveMate

Welcome to **SolveMate**, your bilingual AI-powered math tutor! This app helps high school students solve algebra problems step-by-step in both **Bangla** and **English**. Built with **Streamlit**, **LangChain**, and **Groq's LLM**, SolveMate ensures students understand each step before moving forward.

## 🌟 Features
- 🔁 Step-by-step math problem solving
- 🧠 Checks understanding before proceeding
- 🗣️ Supports both **Bangla** and **English**
- 💬 Interactive chat interface
- ⚡ Powered by Groq's ultra-fast LLM
- 🧱 Built with LangChain & Streamlit

## 🚀 Demo
![Demo GIF or Screenshot Placeholder](link-to-your-demo.gif)

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) — for UI
- [LangChain](https://www.langchain.com/) — for prompt chaining
- [Groq API](https://groq.com/) — for LLM inference
- [Python](https://www.python.org/) — core language

## 📦 Installation
```bash
# 1. Clone the repository
git clone https://github.com/MDalamin5/bilingual-ai-math-tutor-SolveMate.git
cd bilingual-ai-math-tutor-SolveMate

# 2. Create a virtual environment and activate it
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up environment variables
Create a `.env` file in the root directory with the following:
GROQ_API_KEY=your_groq_api_key

# 5. Run the app
streamlit run app.py
```

## 🧪 How It Works
- User selects language (Bangla or English)
- Enters a math problem via chat
- The app uses a dynamic system prompt to:
  - Break down the problem
  - Explain each step
  - Confirm user understanding
  - Adjust explanation if needed

## 🧠 Prompt Design Highlights
- Solves only one step at a time
- Waits for student confirmation before moving on
- Responds with hints or alternative explanations if needed
- Refuses non-math conversations

## 🌍 Languages Supported
- 🇧🇩 Bangla
- 🇺🇸 English

## 📁 Folder Structure
```
📦 bilingual-ai-math-tutor-SolveMate
 ┣ 📄 app.py
 ┣ 📄 .env.example
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
```

## 🧑‍💻 Author
- **Al-Amin**  
  🔗 [GitHub](https://github.com/MDalamin5)

## 📃 License
This project is open-source and available under the [MIT License](LICENSE).

---
Feel free to star ⭐ the repo if you found it helpful!

