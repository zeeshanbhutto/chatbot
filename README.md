# 🤖 Groq + Streamlit AI Chatbot

A lightweight chatbot interface powered by **LLaMA 3** using **Groq API** and built with **Streamlit**. This project lets users interact with an intelligent assistant in real time via a sleek web UI.

## 🚀 Features

- Chat interface with markdown support
- Groq API (LLaMA 3 - 8B or 70B model)
- Stateless or session-based memory
- Simple and clean UI with `st.chat_input`

---

## 🧠 Tech Stack

- [Streamlit](https://streamlit.io/)
- [Groq API](https://console.groq.com/)
- [LLaMA 3 models](https://groq.com/blog/llama-3-running-at-500-tokens-per-second/)

---

## 📁 Project Structure

.
├── app.py # Main Streamlit app
├── .env # Contains your Groq API Key
├── requirements.txt # Python dependencies

pip install -r requirements.txt
Create a .env file:

ini
Copy
Edit
GROQ_API_KEY=your_groq_api_key_here
Run the app

bash
Copy
Edit
streamlit run app.py
💬 Example Prompt
"How does Groq work and what is LLaMA 3?"

🌐 Deployment on Streamlit Cloud
You can deploy this easily by:

Creating a GitHub repo with this code.

Going to https://streamlit.io/cloud

Connecting your GitHub, selecting the repo.

Setting the GROQ_API_KEY as a secret environment variable in the Secrets Manager.

bash
Copy
Edit
# On Streamlit Cloud secrets
GROQ_API_KEY=your_actual_key
