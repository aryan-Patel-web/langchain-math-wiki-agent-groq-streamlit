
# LangChain Math Solver & Wiki Assistant (Groq + Streamlit)

🚀 A conversational Streamlit app that solves **math problems** and performs **knowledge searches** using Groq’s Gemma 2 LLM and LangChain’s agents and tools.

---

## 💡 Features

✅ Math problem solving with step-by-step explanations  
✅ Wikipedia search for factual answers  
✅ Reasoning tool for complex logic questions  
✅ Interactive chat UI via Streamlit  
✅ Powered by Groq’s lightning-fast LLMs

---

## 🛠️ Requirements

- Python 3.10+
- Groq API Key

Install dependencies:

```bash
pip install -r requirements.txt

---

## ✅ requirements.txt

Here’s your requirements list:

```txt
streamlit
langchain
langchain-community
langchain-core
langchain-groq
python-dotenv
sqlalchemy


🔑 Environment Variables
Create a .env file (optional) with:

GROQ_API_KEY=sk-xxxxxx


🚀 Running the App

Start the Streamlit server:

streamlit run app.py


🎯 Usage
Enter your Groq API key in the sidebar.

Type a math problem or knowledge query into the text box.

Click Find My Answer.

Get step-by-step solutions or factual responses.

Example:

I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes.
Then I buy a dozen apples and 2 packs of blueberries.
Each pack of blueberries contains 25 berries.
How many total pieces of fruit do I have at the end?


👨‍💻 Author
Aryan Patel


🌟 Future Enhancements
Support graph plotting for math outputs

Add support for multilingual questions

Integrate additional tools (e.g. WolframAlpha)

Store chat history in a database for retrieval