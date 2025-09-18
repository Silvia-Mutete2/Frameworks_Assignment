
# 📊 Frameworks_Assignment
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Streamlit-Enabled-brightgreen?logo=streamlit">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
</p>

**CORD-19 Data Analysis & Interactive Streamlit App**

Explore COVID-19 research trends using the CORD-19 dataset! This project demonstrates a full data science workflow: loading, cleaning, analyzing, visualizing, and presenting insights through an interactive Streamlit web app.



## 🚀 Features
- 📥 Load and explore the CORD-19 research metadata
- 🧹 Clean and preprocess the dataset
- 📈 Analyze:
  - Publications by year
  - Top journals
  - Word frequency in paper titles
  - Distribution by source
- 📊 Visualize with Matplotlib, Seaborn, and WordCloud
- 🌐 Interactive Streamlit app with:
  - Year range filtering
  - Top journals bar chart
  - Word cloud of titles
  - Publications per year

---


## � Project Structure
```
Frameworks_Assignment/
├── app.py              # Streamlit app
├── analysis.ipynb      # Jupyter notebook (exploration & plots)
├── requirements.txt    # Required Python packages
├── README.md           # Project documentation
└── data/
  └── metadata.csv    # Dataset (from Kaggle)
```


---

pip install -r requirements.txt
jupyter notebook

## ⚙️ Installation & Setup

1. **Clone the repository**
  ```bash
  git clone https://github.com/Silvia-Mutete2/Frameworks_Assignment.git
  cd Frameworks_Assignment
  ```
2. **Create and activate a virtual environment**
  ```bash
  python3 -m venv venv
  source venv/bin/activate   # On Linux/Mac
  # venv\Scripts\activate   # On Windows
  ```
3. **Install dependencies**
  ```bash
  pip install -r requirements.txt
  ```
4. **Run the Jupyter Notebook**
  ```bash
  jupyter notebook
  ```
5. **Launch the Streamlit App**
  ```bash
  streamlit run app.py
  ```

---

## � Author

**Silvia Mutete**

---

<p align="center">
  <em>Happy Analyzing! 🚀</em>
</p>


