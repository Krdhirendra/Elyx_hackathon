# Elyx Member Journey Analytics  

***⚠️⚠️WE HAVE ADDED THE PROMPTS IN report(4).pdf***

## 📌 Overview  
This project was built as part of the **Elyx Life Hackathon (Aug 2025)**.  

The challenge: *How do we make a member’s health journey transparent—so every decision, from medication to therapy, is explainable and traceable?*  

Our solution, **Elyx Member Journey Analytics**, is a web app that transforms raw conversations and health data into clear, interactive visualizations. It enables care teams and members to:  
- Understand **what decisions were made**  
- Trace **why those decisions were taken**  
- Track **progress, trends, and engagement** over time  

---
## 📂 Repository Structure  
```
Elyx_hackathon/
│
├── data/ # Sample data files
│ └── final_data.txt
│
├── idaten_app.py # Main Streamlit app
├── requirements.txt # Dependencies
├── LICENSE # License file
├── README.md # Project documentation
└── .devcontainer/ # Dev container config (optional)
```

## 🚀 Features  
- **Timeline View** – *Bi-weekly journey episodes* with goals, triggers, outcomes, and persona analysis  
- **Metrics Dashboard** – Visualizes consultations, role-wise effort, and response time trends  
- **Analytics View** – Tracks sentiment flow, topic evolution, and communication patterns  
- **Journey Assistant** – AI-powered chat to answer `why` questions with context and references  

---

## 🛠 Tech Stack  
- **Frontend / App**: Streamlit  
- **Backend / AI**: OpenAI API (LLMs for summarization & reasoning)  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Plotly, Seaborn, Matplotlib  

---

## ⚡ Quick Start (Local Setup)  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Krdhirendra/Elyx_hackathon.git
   cd Elyx_hackathon```
2. **Install Dependencies**
   ``` pip install requirements.txt```
3. **Add your API key**
Create a .env file in the project root with:
```OPENAI_API_KEY=your_api_key_here```

4. **Run the app**
   bash ```streamlit idaten_app.py```
   
---

**Hosted Version**
   👉 https://idaten.streamlit.app/
  
**Use This Sample data**
  ```data/final_data.txt```

**Video Demo**
    👉 https://youtu.be/psmGhIUHF7k

👥 Team

**Team IDATEN**
*Lokaranjan panda*
*Dhirendra Kumar*
