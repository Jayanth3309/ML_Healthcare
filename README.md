# 🧠 ML_Healthcare

A Flask-based web application that uses machine learning to detect network intrusions such as DDoS, brute force, and SQL injection attacks. Upload network traffic data and get real-time predictions using a pre-trained model.

---

## 🔧 Tech Stack

- **Backend**: Python, Flask
- **ML**: scikit-learn, pandas, joblib
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite

---

## 🚀 Features

- User login/signup system
- Upload `.csv` files for attack prediction
- Pre-trained model (provided as `model.zip`)
- Clean UI with Bootstrap
- Jupyter notebook for training reference

---

## 📦 Setup Instructions

```bash
git clone https://github.com/Jayanth3309/ML_Healthcare.git
cd ML_Healthcare
pip install -r requirements.txt
unzip model.zip
python app.py
Access the app at: http://127.0.0.1:5000

📁 Main Files
app.py – Flask app logic

Notebook.ipynb – Model training steps

model.zip – Zipped trained model (model.sav)

requirements.txt – Python dependencies

📄 License
MIT © 2025 Jayanth Maddula
