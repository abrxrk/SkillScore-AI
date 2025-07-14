# 🎯 SkillScore.AI

**SkillScore.AI** is a simple Streamlit web app that allows users to rate their confidence in various tech skills and instantly get:

- A visual analysis of their strengths
- A personalized roadmap for improvement

---

## 🧠 Features

✅ Rate confidence in key tech skills  
📊 Visual radar chart of your skill levels  
🗺️ AI-powered roadmap for your weak areas  
💡 Clean and interactive UI using Streamlit

---

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/skillscore-ai.git
cd skillscore-ai
```

### 2. Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
streamlit run app.py
```

---

## 🗂️ Project Structure

```
skillscore-ai/
├── app.py                # Main Streamlit app
├── utils.py              # Logic for evaluating skills & roadmap
├── roadmap_templates.json# Skill-specific roadmap content
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 📦 Dependencies

- Streamlit
- Pandas
- Plotly

Install with:

```bash
pip install -r requirements.txt
```

---

## 🧩 Customization

You can modify the following:

- `skills` in `app.py`: Add/remove skills
- `roadmap_templates.json`: Add roadmaps for new skills
- UI elements using `st.markdown`, `st.slider`, etc.

---

## 📄 License

This project is for learning and demo purposes. You’re free to modify, improve, or use it in your own apps.

---
