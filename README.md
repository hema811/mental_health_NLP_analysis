# mental_health_NLP_analysis
This project explores how public emotional trends reflect mental health patterns by combining Reddit posts with the **CDC BRFSS (Behavioral Risk Factor Surveillance System)** survey data. Using **Natural Language Processing (NLP)** and **Machine Learning**, this project builds models to detect mental health distress and track changes over time.
# 🧠 Mental Health Trends Using Social Media and Public Survey Data

This project investigates how **social media discourse (Reddit)** can be integrated with **public health survey data (BRFSS)** to monitor and predict mental health trends in near real-time.  
By applying **Natural Language Processing (NLP)**, **Machine Learning (ML)**, and **Topic Modeling**, the project bridges the gap between traditional epidemiological data and modern online behavioural insights.

---

## 📋 Overview

- Combined **Reddit discussions**, **CDC BRFSS survey data**, and **CLPsych shared task dataset** to detect emotional and thematic mental-health patterns.
- Applied **sentiment analysis**, **topic modeling**, and **supervised ML classifiers** (SVM, Random Forest, BERT) to identify posts related to mental health distress.
- Validated social-media-derived signals against BRFSS indicators to ensure **data reliability** and **real-world relevance**.
- Developed an **interactive dashboard** for visualizing mental health trends for policymakers and researchers.

---

## 🧠 Research Goals

1. Collect and preprocess diverse datasets (Reddit, BRFSS, CLPsych).  
2. Apply NLP for sentiment extraction and topic discovery.  
3. Train ML classifiers to detect mental-health conditions.  
4. Validate Reddit trends using BRFSS population-level data.  
5. Build visual dashboards for communication and policy insight.

---

## ⚙️ Methodology

### 🧹 Data Preprocessing
- Cleaned, tokenized, lemmatized, and normalized Reddit text.
- Removed duplicates, non-English posts, and handled dataset imbalance.
- Aggregated Reddit sentiment temporally for comparison with BRFSS survey cycles.

### 🔍 Exploratory Data Analysis
- Visualized post distributions, text length, and sentiment polarity.
- Observed strong asymmetry: **negative posts (distress)** vs **positive replies (peer support)**.

### 💬 Sentiment Analysis
- Used **VADER** and **TextBlob** to compute polarity scores (–1 to +1).  
- Found high negative sentiment during major events (e.g., COVID-19), confirming sensitivity to real-world stressors.

### 🧩 Topic Modeling
- Implemented **LDA**, **NMF**, and **BERTopic** to uncover major themes:
  - PTSD & Trauma  
  - Anxiety & Therapy  
  - Work & ADHD  
  - Family & Relationships  
  - General Emotional Distress  
- Evaluated coherence and diversity metrics to select the optimal model (LDA).

### 🤖 Machine Learning
- Trained supervised models on the CLPsych dataset:
  - **SVM** – baseline model  
  - **Random Forest** – robust ensemble classifier  
  - **BERT** – fine-tuned transformer model  
- **Performance:** Accuracy = 0.81 (classical models), up to **0.82 F1** with BERT.  
- Classified Reddit posts into multiple mental-health conditions (Depression, Anxiety, PTSD, etc.).

### 🔗 Integration with BRFSS
- Correlated Reddit sentiment with BRFSS depression indicators.
- Found strong positive correlation — Reddit often detected emotional spikes earlier than surveys.

### 📊 Visualization & Dashboard
- Built with **Plotly Dash** and **Streamlit** for interactive data exploration:
  - Sentiment trends over time
  - Topic heatmaps
  - Model performance charts
  - Correlation plots with survey data

---

## 📈 Key Results

| Model | Accuracy | F1-Score | Highlight |
|-------|-----------|----------|------------|
| SVM | 0.78 | 0.75 | Strong baseline |
| Random Forest | 0.81 | 0.80 | Best classical ML performance |
| BERT | 0.82 | 0.82 | Highest accuracy, deep contextual learning |

- Detected **early warning signals** of mental health shifts from Reddit data.  
- Identified **8 major emotional and behavioural topics** via LDA.  
- Demonstrated **cross-dataset validation** between Reddit (real-time) and BRFSS (survey).

---

## 🧰 Tools & Technologies

**Languages:** Python  
**Libraries:** Pandas · NumPy · Scikit-learn · TensorFlow · NLTK · SpaCy · Transformers · VADER · BERTopic · pyLDAvis  
**Visualization:** Plotly · Streamlit · Seaborn · Power BI  
**ML Models:** SVM · Random Forest · BERT  
**Other:** Git · Jupyter Notebooks

---

## 🧩 Key Skills

Python · NLP · Sentiment Analysis · Topic Modeling · Machine Learning · Data Integration · Dashboard Design · Streamlit · Power BI · EDA · Data Visualization · Statistical Analysis · BERT · Random Forest · Ethical AI

---

## 📜 Insights

- Reddit provides rapid, real-time insights into emotional discourse.  
- BRFSS offers validated, long-term population metrics.  
- Integration of both enhances **early detection** and **policy readiness**.  
- The framework demonstrates how **AI and NLP** can support **mental-health monitoring** ethically and at scale.

---

## 🖥️ Dashboard & Notebook Links
- [📓 Jupyter Notebook](#) <!-- -->
  
## 📬 Author

**Hema Priya Pandhiti**  
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile) · [GitHub](https://github.com/yourusername)

---

### ⭐ Citation
Pandhiti, HemaPriya. *Mental Health Trends using Social Media and Public Survey Data.* 
