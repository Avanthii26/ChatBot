# ChatBot

An intelligent conversational AI chatbot built with Google Gemini 2.0, LangGraph, FastAPI, and Streamlit.
It maintains context across messages, provides clear explanations, and interacts in a natural, human-like way.
The project is lightweight, easy to deploy in Google Colab, and accessible from anywhere using ngrok.

 **Features**

 1. AI-Powered Assistant – Uses Google Gemini 2.0 for high-quality and human-like responses.

 2. Context Awareness – Retains memory and state with LangGraph to ensure coherent multi-turn conversations.

 3. REST API Backend – Built on FastAPI, enabling robust, scalable, and flexible integration.

 4. User-Friendly Frontend – Streamlit interface for a clean and interactive chat experience.

 5. External Access – Easily share via ngrok-generated public URLs.

 6. Chat Management Tools – Clear history, monitor statistics, and test backend directly from the sidebar.

 7. Resilient Error Handling – Gracefully manages failures with backend logging.

 8. Conversation Analytics – Tracks user vs assistant messages, total message counts, and session stats.

 9. Secure by Design – API keys and secrets handled safely, suitable for Colab or local environments.

10. Lightweight & Deployable Anywhere – Can run locally, on Colab, or be adapted for cloud deployment.

**TO START** 

Clone the Repository
git clone https://github.com/your-username/conversational-ai-chatbot.git
cd conversational-ai-chatbot

Install Dependencies
pip install -r requirements.txt

Add API Key
Create a .env file in the project root and add your Google Gemini API key:
GEMINI_API_KEY=your_api_key_here

Run the FastAPI Backend
uvicorn backend.main:app --reload

Run the Streamlit Frontend
streamlit run frontend/app.py
