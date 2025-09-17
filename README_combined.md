# 🌍 Sustainable Smart City Assistant  

An AI-powered project designed to make cities greener, smarter, and more sustainable.  
This assistant provides **eco-friendly tips** and **policy summarization**, while the overall project vision includes **resource forecasting, anomaly detection, and citizen engagement**.  

---

## 📖 Project Overview  

**Purpose**  
The Sustainable Smart City Assistant empowers cities and citizens to thrive in an eco-conscious environment. By leveraging AI and real-time data, it optimizes resources like energy, water, and waste while guiding sustainable behavior.  

**Key Features**  
- Conversational Interface for natural language queries.  
- Policy Summarization for simplifying complex government documents.  
- Eco-Tip Generator with actionable sustainability advice.  
- (Planned) Forecasting, anomaly detection, and KPI dashboards for city officials.  
- Citizen feedback loop for community-driven improvements.  

---

## 🏗️ Architecture  

- **Frontend**: Streamlit / Gradio (user-friendly dashboards).  
- **Backend**: FastAPI REST APIs.  
- **LLM**: IBM Watsonx Granite + Hugging Face Transformers.  
- **Vector Search**: Pinecone (document embeddings + semantic search).  
- **ML Modules**: Forecasting & anomaly detection with scikit-learn & pandas.  

---

## ⚙️ Installation & Setup  

### Prerequisites  
- Python 3.9+  
- pip / venv  
- API keys (IBM Watsonx, Pinecone – optional)  

### Installation  
```bash
git clone https://github.com/your-username/smart-city-assistant.git
cd smart-city-assistant

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
```  

---

## 🚀 Running the Application  

### Option 1: Gradio App (Eco Tips + Policy Summarizer)  
```bash
python app.py
```  
This launches a local web app (use `share=True` for public link).  

### Option 2: Full Dashboard with FastAPI + Streamlit  
```bash
uvicorn app.main:app --reload
streamlit run smart_dashboard.py
```  

---

## 🖥️ Usage  

### Eco Tips Generator  
- Enter keywords like *plastic, solar, water waste, energy saving*.  
- Get personalized sustainability tips.  

### Policy Summarizer  
- Upload a **PDF** or paste text.  
- Receive concise summaries with key provisions and implications.  

---

## 📂 Folder Structure  

```
app/                 # FastAPI backend
app/api/             # Modular API routes
ui/                  # Streamlit/Gradio components
smart_dashboard.py   # Streamlit entry point
app.py               # Gradio demo app
README.md            # Project documentation
requirements.txt     # Dependencies
```

---

## 🐞 Known Issues  
- Development & maintenance costs.  
- Data privacy risks.  
- Digital divide & infrastructure challenges.  
- Energy demand & e-waste management.  

---

## 🔮 Future Enhancements  
- Large-scale renewable energy (solar, wind, bio).  
- AI + IoT for smarter waste & energy management.  
- Affordable smart solutions for all citizens.  
- Stronger cybersecurity & privacy.  
- Eco-friendly transport & green buildings.  

---

## 👨‍💻 Team  
- Vanitha M  
- Sri Karpagam G  
- Ranjeetha G  
- Sai Haripoornima S  
- Suvetha R  
