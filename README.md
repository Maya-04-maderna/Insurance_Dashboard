# 🏥 Insurance Cost Insights Dashboard

An interactive Streamlit dashboard that reveals how demographic and lifestyle factors (age, BMI, smoking status, and region) influence healthcare insurance costs—ideal for data-driven decision-making and strategy.

---

## 📌 Highlights of Insights

- 🌍 **Regional Cost Differences**: Southeast averages ~$15K, while Southwest and Northwest range ~$12–13K in insurance charges.  
- 🚬 **Smoking Effect**: Smokers incur significantly more variable and higher charges than non-smokers.  
- 📈 **Age & Smoking Trend**: Insurance costs rise with age for all, but smokers pay disproportionately more—especially in older brackets.  
- ⚖️ **BMI Profile**: Majority fall in BMI 25–35 (slightly overweight), potentially increasing health risk and cost.  
- 👥 **Dataset Balance**: Southeast region has the most participants, but dataset remains geographically diverse.

---

## 📊 Dashboard 
<link src="Screenshot/insurance_dashboard.png" alt="Dashboard" width=800 />


---

## 🧰 Tech Stack

- **Python 3.x**  
- **Streamlit** – interactive web app UI  
- **Pandas & NumPy** – data cleaning & analysis  
- **Matplotlib & Seaborn** – visualization tools  

---

## 🔧 Setup & Run

```bash
git clone https://github.com/yourusername/insurance-dashboard.git
cd insurance-dashboard
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
.\venv\Scripts\activate   # Windows
pip install -r requirements.txt
streamlit run app.py
