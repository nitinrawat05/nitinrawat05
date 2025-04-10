<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FF61F6&center=true&vCenter=true&width=700&lines=Hey+there%2C+I'm+Nitin+Rawat+(aka+Nits)+%F0%9F%91%8B;Data+Analyst+%7C+Future+Data+Scientist;Turning+Chaos+into+Insights+%F0%9F%93%8A" alt="Typing SVG" />
</h1>

---

### 🧠 About Me
<div align="left">

- 💡 Passionate about **data-driven decision making**  
- 🤖 Exploring **ML**, **LLMs (GPT, LangChain)**, and **NLP**  
- 📈 Turning messy data into crystal-clear dashboards  
- 💬 Ask me about: Data wrangling, EDA, predictive models, or debugging your SQL JOIN 😉  
- 🎯 Currently learning: **LangChain, Hugging Face, TensorFlow**

</div>

---

### 💻 Tech Stack & Tools

#### ⚙️ Languages & Libraries
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,sql,jupyter,numpy,pandas,scikit-learn,seaborn,git" />
</p>

<!-- 📊 BI & Visualizations -->
<h4 align="center">📊 BI & Visualizations</h4>
<p align="center" style="display:flex; justify-content:center; gap:15px; flex-wrap:wrap;">

  <a href="https://www.tableau.com/" target="_blank">
    <img src="https://skillicons.dev/icons?i=tableau" title="Tableau" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

  <a href="https://powerbi.microsoft.com/" target="_blank">
    <img src="https://skillicons.dev/icons?i=powerbi" title="Power BI" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

  <a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank">
    <img src="https://skillicons.dev/icons?i=excel" title="Microsoft Excel" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

  <a href="https://plotly.com/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/plotly/plotly-original.svg" width="40" title="Plotly" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

  <a href="https://matplotlib.org/" target="_blank">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="40" title="Matplotlib" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

  <a href="https://seaborn.pydata.org/" target="_blank">
    <img src="https://raw.githubusercontent.com/mwaskom/seaborn/main/doc/_static/logo-wide-lightbg.svg" height="40" title="Seaborn" style="transition: transform 0.3s;" onmouseover="this.style.transform='scale(1.2)'" onmouseout="this.style.transform='scale(1)'"/>
  </a>

</p>


#### 🤖 AI & LLMs (Learning)
<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow" />
  <img src="https://avatars.githubusercontent.com/u/1399141?s=200&v=4" width="40" title="Hugging Face"/>
  <img src="https://avatars.githubusercontent.com/u/116947076?s=200&v=4" width="40" title="LangChain"/>
</p>

---

### ✨ Experiences
<div align="left">

#### 🔹 Jr. Data Analyst – **Elon Staffing (2023 – 2024)**
- 🛠️ Automated Tableau & Excel dashboards for KPI monitoring  
- 🐍 Streamlined ETL using **Python (Pandas, NumPy)**  
- 🧮 Queried & analyzed SQL datasets to derive actionable insights  
- ⚡ Reduced manual reporting time by **30%**

#### 🔹 Data Analyst Intern – **Personal Projects**
- 📌 Projects: Sales Insights, Bank Loan Risk Models, Conversion Funnels  
- 🧰 Tools: MySQL, Scikit-learn, Seaborn, Power BI, Excel  

</div>

---

### 📊 Data Analysis in Action

![Sales Analysis Chart](https://your-github.com/assets/sales-analysis.png)
> *Visualizing revenue trends using Matplotlib & Seaborn*

---

### 🤖 Machine Learning Code Snapshot

```python
# Random Forest Classifier - Bank Loan Prediction
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

df = pd.read_csv("loan_data.csv")
X = df.drop("loan_status", axis=1)
y = df["loan_status"]

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = RandomForestClassifier()
model.fit(X_train, y_train)

preds = model.predict(X_test)
print(f"Accuracy: {accuracy_score(y_test, preds):.2f}")


graph TD;
    A[Deep Learning] --> B[Hugging Face 🤗];
    B --> C[LangChain 🔗];
    C --> D[Prompt Engineering 💬];
    D --> E[LLM App Prototyping ⚙️];
