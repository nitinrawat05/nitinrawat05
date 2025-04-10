<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FF61F6&center=true&vCenter=true&width=700&lines=Hey+there%2C+I'm+Nitin+Rawat+(aka+Nits)+%F0%9F%91%8B;Data+Analyst+%7C+Future+Data+Scientist;Turning+Chaos+into+Insights+%F0%9F%93%8A" alt="Typing SVG" />
</h1>

---

### 🧠 About Me

<div align="left">
  <ul>
    <li>💡 Passionate about <b>data-driven decision making</b></li>
    <li>🤖 Exploring <b>ML</b>, <b>LLMs (GPT, LangChain)</b>, and <b>NLP</b></li>
    <li>📈 Turning messy data into crystal-clear dashboards</li>
    <li>💬 Ask me about: Data wrangling, EDA, predictive models, or debugging your SQL JOIN 😉</li>
    <li>🎯 Currently learning: <b>LangChain, Hugging Face, TensorFlow</b></li>
  </ul>
</div>

---

### 💻 Tech Stack & Tools

---

#### ⚙️ Languages & Libraries

<p align="center">
  <img src="https://skillicons.dev/icons?i=python" title="Python" />
  <img src="https://skillicons.dev/icons?i=sql" title="SQL" />
  <img src="https://skillicons.dev/icons?i=jupyter" title="Jupyter" />
  <img src="https://skillicons.dev/icons?i=numpy" title="NumPy" />
  <img src="https://skillicons.dev/icons?i=pandas" title="Pandas" />
  <img src="https://skillicons.dev/icons?i=scikitlearn" title="Scikit-learn" />
  <img src="https://skillicons.dev/icons?i=seaborn" title="Seaborn" />
  <img src="https://skillicons.dev/icons?i=git" title="Git" />
</p>

---

#### 📊 BI & Visualizations

<p align="center">
  <img src="https://skillicons.dev/icons?i=tableau" title="Tableau" />
  <img src="https://skillicons.dev/icons?i=powerbi" title="Power BI" />
  <img src="https://skillicons.dev/icons?i=excel" title="Microsoft Excel" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/plotly/plotly-original.svg" width="40" title="Plotly" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="40" title="Matplotlib" />
  <img src="https://raw.githubusercontent.com/mwaskom/seaborn/main/doc/_static/logo-wide-lightbg.svg" height="40" title="Seaborn" />
</p>

---

#### 🤖 AI & LLMs (Learning Phase)

<p align="center">
  <img src="https://skillicons.dev/icons?i=pytorch" title="PyTorch" />
  <img src="https://skillicons.dev/icons?i=tensorflow" title="TensorFlow" />
  <img src="https://avatars.githubusercontent.com/u/1399141?s=200&v=4" width="40" title="Hugging Face" />
  <img src="https://avatars.githubusercontent.com/u/116947076?s=200&v=4" width="40" title="LangChain" />
</p>

---

### ✨ Experiences

<div align="left">
  <h4>🔹 Jr. Data Analyst – <b>Elon Staffing (2023 – 2024)</b></h4>
  <ul>
    <li>🛠️ Automated Tableau & Excel dashboards for KPI monitoring</li>
    <li>🐍 Streamlined ETL using <b>Python (Pandas, NumPy)</b></li>
    <li>🧮 Queried & analyzed SQL datasets to derive actionable insights</li>
    <li>⚡ Reduced manual reporting time by <b>30%</b></li>
  </ul>

  <h4>🔹 Data Analyst Intern – <b>Personal Projects</b></h4>
  <ul>
    <li>📌 Projects: Sales Insights, Bank Loan Risk Models, Conversion Funnels</li>
    <li>🧰 Tools: MySQL, Scikit-learn, Seaborn, Power BI, Excel</li>
  </ul>
</div>

---

### 📊 Data Analysis in Action

<p align="center">
  <img src="https://your-github.com/assets/sales-analysis.png" alt="Sales Analysis Chart" />
  <br>
  <i>Visualizing revenue trends using Matplotlib & Seaborn</i>
</p>

---

### 🤖 Machine Learning Code Snapshot
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score

df = pd.read_csv("loan_data.csv")
X = df.drop("loan_status", axis=1)
y = df["loan_status"]

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42) # Added random_state for reproducibility
model = RandomForestClassifier(random_state=42) # Added random_state for reproducibility
model.fit(X_train, y_train)

preds = model.predict(X_test)
accuracy = accuracy_score(y_test, preds)
print(f"Accuracy: {accuracy:.2f}")
graph TD;
    A[Deep Learning] --> B[Hugging Face 🤗];
    B --> C[LangChain 🔗];
    C --> D[Prompt Engineering 💬];
    D --> E[LLM App Prototyping ⚙️];


