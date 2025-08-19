# AI Assistant LLM

An AI Assistant powered by Databricks LLM model endpoints.  
This project provides a simple web-based chat interface with feedback collection, built using Flask.

---

## 🚀 Features
- Chat interface (`chat.html`) to interact with the LLM.
- Feedback page (`feedback.html`) to capture user inputs and suggestions.
- Scripts  for frontend logic (chat handling, feedback submission).
- Flask backend serving API calls to Databricks LLM endpoints.

---

## ⚙️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ai-assistant-llm.git
   cd ai-assistant-llm

2. Create & activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows


3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Set environment variables (.env file):

   ```bash
   DATABRICKS_API_KEY=your_api_key_here
   DATABRICKS_MODEL_ENDPOINT=your_model_endpoint_url


5. Run the app:

   ```bash
   flask run


6. Open in browser:

   ```bash
   http://127.0.0.1:5000


## 🖼 Demo

### Chat Interface
![AI Assistant – Chat](static/images/chat-demo.png)

### Feedback Form
![AI Assistant – Feedback](static/images/feedback-demo.png)

