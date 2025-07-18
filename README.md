# Dynamic Insurance Premium Calculator 🧠📊

A smart and modular system that calculates dynamic life insurance premiums using real-world logic and machine learning. This project simulates how leading companies like LIC or SBI Life might approach premium calculation — combining business rules, risk assessment, and predictive modeling.

---

## 👨‍💻 About the Project

This project was developed as part of an internship application to demonstrate my ability to:

- Understand domain-specific logic (insurance industry)
- Design realistic simulation data
- Implement both rule-based and ML-based solutions
- Build clean, extensible Python code with real-world applicability

---

## 🚀 Key Features

- ✅ Calculates insurance premiums based on **14+ real-world factors**
- ✅ Handles **both rule-based and ML-based** premium estimation
- ✅ Includes **mortality risk logic**, **market factors**, and **regulatory compliance**
- ✅ Segments users as **Premium**, **Standard**, or **Budget** customers
- ✅ Clean CLI interface for real-time interaction

---

## 🧩 Technologies Used

- **Language:** Python 3
- **Libraries:**  
  - `pandas`, `numpy` – for data manipulation  
  - `scikit-learn` – RandomForestRegressor for modeling  
  - `datetime` – for seasonal adjustments  

---

## 📈 Premium Model Overview

- **Base Algorithm**: Random Forest Regressor
- **Training Data**: 5,000 synthetic rows
- **Target Output**: Monthly Premium
- **Input Variables**:  
  - Personal (age, gender, health)  
  - Lifestyle (smoking, alcohol, driving score)  
  - Financial (income, coverage, term)  
  - Risk (occupation risk, zone risk, family history)  
  - System (mortality risk table, profit margin, market adjustment)

---

## 🧪 How to Run

### 1. Clone this repo
git clone [https://github.com/your-username/dynamic-insurance-premium-calculator.git](https://github.com/Kamal-Shirupa/Dynamic-Insurance-Premium-Calculator)

dynamic-insurance-premium-calculator

### 2. Install dependencies
pip install -r requirements.txt

### 3. Run the program
python insurance_calculator.py

📌 Use Case
Designed for users (like insurance agents or clients) to enter real-world data and get dynamically adjusted premium estimates. The model ensures fairness (through regulations), profitability (via risk scoring), and adaptability (via market factors).

👤 Author
Shirupa Kamal
B.Tech CSE (AI & ML), BV Raju Institute of Technology
GitHub: https://github.com/Kamal-Shirupa

📄 License
Licensed under the MIT License

🙋🏻‍♀️ Feedback / Contact
If you're a recruiter or reviewer and have any feedback/suggestions, feel free to open an issue or connect on LinkedIn. I'm actively seeking internship opportunities where I can contribute meaningfully to real-world AI/ML systems.
