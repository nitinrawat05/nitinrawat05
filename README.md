<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FF61F6&center=true&vCenter=true&width=700&lines=Hey+there%2C+I'm+Nitin+Rawat+(aka+Nits)+%F0%9F%91%8B;Data+Analyst+%7C+Future+Data+Scientist;Turning+Chaos+into+Insights+%F0%9F%93%8A" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://github.com/nitinrawat05/nitinrawat05/blob/main/assets/banner.gif" alt="Banner" width="100%" />
</p>

---

### 🧠 About Me

- 📌 Data Enthusiast focused on **insightful storytelling through data**  
- 🧬 Exploring the world of **ML**, **LLMs**, and **AI automation**  
- 📊 Specializing in **dashboard design**, **ETL**, and **data wrangling**  
- 💡 Current obsessions: **LangChain, Hugging Face, TensorFlow**  
- 💬 Fun fact: I love debugging JOIN queries like solving puzzles 🧩  

---

### 💼 Experience Snapshot

#### 🧠 MIS Intelligence Analyst – *AdByteHub*  
- Analyzed performance marketing data (CTR, CPC, ROAS, conversions) for Facebook Ads campaigns  
- Created detailed revenue, campaign, and ROI reports to provide actionable insights  
- Developed Tableau dashboards to track KPIs and campaign performance  
- Managed and cleaned large datasets to ensure accurate reporting and analysis  

#### 🚀 Jr. Data Analyst – *Elon Staffing*  
- Automated KPI dashboards using **Tableau** & **Excel**  
- Streamlined ETL pipelines using **Python (Pandas, NumPy)**  
- Performed ad-hoc SQL queries for fast insights  
- Reduced reporting time by **30%** via automation  

#### 🔍 Freelance Projects – *Data Analyst Intern*  
- ✅ Worked on Sales, Loan Prediction, and Marketing Analytics projects  
- 🛠️ Tools used: MySQL, Scikit-learn, Power BI, Seaborn, Excel  

---

### 🔧 Tech Stack & Tools

#### ⚙️ Programming, Analysis & ML  
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sql,jupyter,numpy,pandas,scikit-learn,seaborn,matplotlib,git" />
</p>

#### 📊 BI & Visualization  
<p align="center">
  <img src="https://skillicons.dev/icons?i=powerbi,tableau,excel" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/plotly/plotly-original.svg" width="40" title="Plotly" />
</p>

#### 🤖 AI & LLMs (Learning)  
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" />
  <img src="https://avatars.githubusercontent.com/u/1399141?s=200&v=4" width="40" title="Hugging Face" />
  <img src="https://avatars.githubusercontent.com/u/116947076?s=200&v=4" width="40" title="LangChain" />
</p>

---

### 📊 Project Gallery

#### 🔹 Sales Analysis  
![Sales Dashboard](https://github.com/nitinrawat05/nitinrawat05/blob/main/assets/sales_analysis.png)  
> *Trends & Revenue insights powered by Matplotlib & Seaborn*

#### 🔹 Loan Default Prediction  
```python
# ML: Random Forest for Bank Loan Classification
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

# Load data
df = pd.read_csv("loan_data.csv")
X = df.drop("loan_status", axis=1)
y = df["loan_status"]

# Train/Test Split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Model Training
model = RandomForestClassifier(random_state=42)
model.fit(X_train, y_train)

# Prediction & Accuracy
preds = model.predict(X_test)
print(f"Accuracy: {accuracy_score(y_test, preds):.2f}")

    keep_trying()
