### Resume Critique App 📑

This is a Streamlit-powered web app that provides **AI-driven resume feedback**. The app analyzes uploaded resumes and offers constructive suggestions to help users improve their resumes for job applications.

---

### ⚡ Features

- Upload your resume as a **PDF or TXT file**  
- Optionally specify a **target job role** for focused feedback  
- Get **AI-generated analysis and recommendations**  
- Custom **favicon and inline icon** next to the app title for a polished look  
- Powered by **OpenAI API** for natural language critique  

---

### 🛠 How to Run Locally

### Clone the repository:
```bash
git clone https://github.com/jem-thanmay/Resume_Critique.git
cd Resume_Critique
```
### Create Virtual Environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```
### Install the requirements
```bash
pip install -r requirements.txt
```

### Create a .env file and add your OpenAI API key:
```ini
OPENAI_API_KEY="XXXXXXXXXXXXXXXXXXX"
```

### Run the app:
```bash
streamlit run main.py
```

Now open,
```bash
localhost:8501
```

### Built with:
- Streamlit
- OpenAI API
- PyPDF2
- python-dotenv
