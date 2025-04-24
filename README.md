# AiSysmptomChecker
An AI-powered symptom checker that provides preliminary health assessments based on user inputs. Built with machine learning to offer accurate, data-driven insights for better healthcare decisions.

## 🚀 Live Features

- 🧠 **Natural Language Understanding** using `spaCy`
- 🔍 **Real-Time Symptom Analysis** with ML classifiers
- 🎙️ **Voice-to-Text Support** for hands-free symptom entry
- 📄 **PDF Report Generation** summarizing predictions and suggestions
- 📦 **Multi-label Prediction Model** for handling complex symptoms
- 🌐 **Fully Web-based Interface** with `Streamlit`

---

## 🌟 What Makes It Special?

✅ Understands human-like descriptions (e.g., “I’ve had a sore throat and fever for 3 days”)  
✅ Uses **OpenAI GPT** to enhance symptom synonym matching  
✅ Built-in **confidence scoring** and **recommended actions**  
✅ Beautiful UI with interactive layout, charts, and voice recording  
✅ Instant **PDF report downloads** for medical follow-ups

---

## 🧰 Built With

| Tool            | Purpose                               |
|------------------|----------------------------------------|
| `Streamlit`     | UI framework                           |
| `spaCy`         | NLP for symptom extraction             |
| `scikit-learn`  | RandomForest-based disease classifier  |
| `OpenAI API`    | Synonym & language understanding       |
| `SpeechRecognition` | Voice input handling                |
| `FPDF`          | PDF report generation                  |

---


## ⚙️ How to Run Locally

### 📦 Installation

```bash
git clone https://github.com/yourusername/ai-symptom-checker.git
cd ai-symptom-checker
pip install -r requirements.txt
python -m spacy download en_core_web_sm
🚀 Launch the App
bash
Copy
Edit
streamlit run ai.py

📁 File Structure
bash
Copy
Edit
.
├── ai.py                   # Main Streamlit app
├── symbipredict_2022.csv   # Dataset of symptoms and diseases
├── mlb.pkl                 # MultiLabelBinarizer pickle
├── disease_encoder.pkl     # LabelEncoder pickle
├── requirements.txt
└── README.md
🌍 Use Cases
🏥 Healthcare triage systems

🩺 Digital symptom screening

👨‍👩‍👧 Family health management

🎓 NLP + ML educational tools

📄 Disclaimer
⚠️ This tool is for educational and informational purposes only.
It does not provide medical diagnosis or treatment.
Always consult a licensed healthcare professional for serious symptoms.

🤝 Contributing
Contributions and feedback are welcome!
Feel free to fork, improve, and open a pull request 🔁









