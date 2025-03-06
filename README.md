# **🏎️ F1 Race Strategy Predictor – Gradio & Data Analytics** 🚀  

## **📌 Project Overview**  
This project analyzes **Formula 1 race strategies** using **FastF1, Python, and Gradio**.  
It provides insights into **lap times, tyre strategies, weather conditions, overtakes, and sector performance** to help understand race dynamics.  

---

## **🔹 Features Implemented**  

### ✅ **1. Race Selection & Data Fetching**  
- Choose **any F1 season and Grand Prix** from a dropdown menu  
- Fetch **real-time race data** using the FastF1 API  

### ✅ **2. Data Analysis & Visualizations**  
- **Lap Time Trends** 📊 – Compare drivers' lap performance  
- **Tyre Strategy** 🛞 – View pit stops & tyre compounds used  
- **Weather Impact** 🌡️ – Track temperature changes during the race  
- **Overtake Insights** 🔀 – Find out which drivers gained the most positions  
- **Sector Performance** ⏱️ – Analyze sector times for different drivers  
- **Speed Trap Insights** 🚦 – Identify top speeds recorded at different sections  

### ✅ **3. Gradio Web Application**  
- **Interactive UI** to select race details  
- **Instant Visualizations** for race analysis  
- **Automated Data Processing** with FastF1  

---

## **🔹 Technologies Used**  
🟡 Python (FastF1, Pandas, NumPy, Matplotlib, Seaborn)  
🟡 Data Visualization (Matplotlib, Seaborn)  
🟡 Gradio (Web Interface)  

## **🔹 How to Run the Project?**  

### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/yourusername/F1-Race-Strategy-Predictor.git
cd F1-Race-Strategy-Predictor
pip install -r requirements.txt
python app.py
📁 F1-Race-Strategy-Predictor
│── 📄 f1_strategy.py      # Main Python script for race analysis
│── 📄 app.py              # Gradio web application
│── 📄 requirements.txt    # Required Python libraries
│── 📄 README.md           # Documentation (this file)
│── 📁 cache/              # Stores FastF1 cache data (optional)

