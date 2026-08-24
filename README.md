https://github.com/user-attachments/assets/90743629-edae-4e6d-8a7c-147da1cb6af6

# 🌱 HealSync — Smart Agricultural Prediction & Advisory System

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=240&section=header&text=🌱%20HealSync&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Powered%20Agricultural%20Intelligence&descAlignY=64&descSize=19"/>
</p>

<p align="center">
  <strong>Predict. Protect. Recommend. Grow. 🌾</strong>
</p>

<p align="center">
  An intelligent agricultural advisory system that combines Machine Learning,
  data analysis and rule-based recommendations to help make smarter farming decisions.
</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Flask-Web%20App-000000?style=for-the-badge&logo=flask&logoColor=white"/>

<img src="https://img.shields.io/badge/Machine%20Learning-scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>

<img src="https://img.shields.io/badge/Agriculture-AI-4CAF50?style=for-the-badge"/>

</p>

<p align="center">

<img src="https://img.shields.io/badge/Random%20Forest-Powered-2E7D32?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Linear%20Regression-Analytics-1565C0?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Rule%20Based-Fertilizer%20Advice-8BC34A?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"/>

</p>

---

# 🌾 What is HealSync?

**HealSync** is an AI-powered **Agricultural Prediction and Advisory System** designed to help farmers and agricultural decision-makers make more informed decisions using data.

The system combines:

> 🤖 **Machine Learning** + 📊 **Data Analysis** + 🌱 **Agricultural Rules** + 🌦️ **Weather Intelligence**

to provide insights across multiple aspects of farming.

Instead of looking at crop yield, disease risk, fertilizer requirements and weather patterns separately, HealSync brings these capabilities together into **one interactive web platform**.

---

# 💡 The Idea Behind HealSync

```text
                         🌱 HEALSYNC
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
       📊 DATA             🤖 ML MODELS       🌾 FARMING
          │                   │                   │
          └───────────────────┼───────────────────┘
                              │
                              ▼
                    🧠 SMART ANALYSIS
                              │
                              ▼
                    💡 ACTIONABLE ADVICE
                              │
                              ▼
                         🌾 BETTER
                         DECISIONS
```

### The goal is simple:

> **Turn agricultural data into practical insights.**

---

# 🚀 Core Features

<table>
<tr>

<td align="center" width="25%">

## 🌾

### Crop Yield Prediction

Predict expected crop yield using environmental and agricultural factors.

</td>

<td align="center" width="25%">

## 🦠

### Disease Risk

Assess potential crop disease risk based on environmental conditions.

</td>

<td align="center" width="25%">

## 🧪

### Fertilizer Advice

Generate NPK fertilizer recommendations based on crop and farming conditions.

</td>

<td align="center" width="25%">

## 🌦️

### Weather Prediction

Analyze historical weather data and predict future rainfall patterns.

</td>

</tr>
</table>

---

# 🌱 1. Crop Yield Prediction

The yield prediction module estimates crop yield using environmental and agricultural factors.

### 🔍 Inputs Include

* 🌧️ Rainfall
* 🌡️ Temperature
* 🧪 Pesticide usage
* 🌾 Crop-related information

### 🤖 Model

**Random Forest Regressor**

```text
🌧️ Rainfall
      +
🌡️ Temperature
      +
🧪 Pesticide Usage
      │
      ▼
🌲 Random Forest Regressor
      │
      ▼
🌾 Predicted Crop Yield
```

---

# 🦠 2. Disease Risk Assessment

The disease prediction module evaluates the possibility of crop disease based on environmental conditions.

### 🔍 Factors Considered

```text
🌧️ Rainfall
🌡️ Temperature
🧪 Pesticide Usage
        │
        ▼
🤖 Random Forest Classifier
        │
        ▼
🦠 Disease Risk Assessment
```

The system uses a trained **Random Forest Classifier** along with preprocessing components such as a scaler and encoder.

---

# 🧪 3. Fertilizer Recommendation

HealSync also provides **rule-based fertilizer recommendations**.

Instead of relying entirely on a machine-learning model, this module uses agricultural rules to determine suitable NPK recommendations.

### 🌾 Recommendation Factors

* 🌱 Crop
* 🌧️ Rainfall
* 🪨 Soil type
* 🌿 Growth stage
* 🧪 Nitrogen
* 🧪 Phosphorus
* 🧪 Potassium

```text
🌱 CROP
  +
🌧️ RAINFALL
  +
🪨 SOIL
  +
🌿 GROWTH STAGE
        │
        ▼
🧠 AGRICULTURAL RULES
        │
        ▼
🧪 NPK RECOMMENDATION
```

> The application also contains a rule-based fallback when the expected fertilizer model is unavailable.

---

# 🌦️ 4. Weather Pattern Analysis

The weather module analyzes historical rainfall data and predicts future rainfall patterns.

### 🤖 Model

**Linear Regression**

```text
📊 Historical Weather Data
          │
          ▼
    🔎 Data Analysis
          │
          ▼
   📈 Linear Regression
          │
          ▼
🌧️ Future Rainfall Prediction
          │
          ▼
💡 Weather Advice
```

This can help provide a basic indication of expected rainfall patterns for a given year.

---

# 🧠 One Platform. Four Intelligent Modules.

<table>
<tr>
<th>Module</th>
<th>Technology</th>
<th>Output</th>
</tr>

<tr>
<td>🌾 Yield Prediction</td>
<td>Random Forest Regressor</td>
<td>Predicted Crop Yield</td>
</tr>

<tr>
<td>🦠 Disease Prediction</td>
<td>Random Forest Classifier</td>
<td>Disease Risk</td>
</tr>

<tr>
<td>🧪 Fertilizer Recommendation</td>
<td>Rule-Based System</td>
<td>NPK Recommendation</td>
</tr>

<tr>
<td>🌦️ Weather Prediction</td>
<td>Linear Regression</td>
<td>Rainfall Prediction</td>
</tr>

</table>

---

# 🏗️ HealSync Architecture

```text
                     👨‍🌾 FARMER / USER
                            │
                            ▼
                  🌐 HEALSYNC WEB APP
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
        🌾 YIELD         🦠 DISEASE     🧪 FERTILIZER
        PREDICTION       ASSESSMENT     RECOMMENDATION
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                     🌦️ WEATHER
                     PREDICTION
                            │
                            ▼
                    🐍 FLASK BACKEND
                            │
            ┌───────────────┼───────────────┐
            │               │               │
            ▼               ▼               ▼
        🤖 ML MODELS    🧠 RULES        📊 DATA
            │               │               │
            └───────────────┼───────────────┘
                            ▼
                     💡 SMART INSIGHTS
```

---

# 🔄 Complete ML Pipeline

```text
📂 RAW AGRICULTURAL DATA
          │
          ▼
      🔎 EDA
          │
          ▼
    🧹 DATA CLEANING
          │
          ▼
   📊 PREPROCESSING
          │
          ▼
     🧪 FEATURE
     ENGINEERING
          │
          ▼
     🤖 MODEL TRAINING
          │
          ▼
     📈 MODEL EVALUATION
          │
          ▼
      💾 MODEL SAVING
          │
          ▼
       🐍 FLASK
          │
          ▼
       🌐 WEB APP
          │
          ▼
     👨‍🌾 USER INSIGHTS
```

---

# 🧰 Technology Stack

<p align="center">

|            Layer            | Technology       |
| :-------------------------: | ---------------- |
| 🐍 **Programming Language** | Python           |
|        🌐 **Backend**       | Flask            |
|   🤖 **Machine Learning**   | Scikit-learn     |
|   💾 **Model Persistence**  | Joblib / Pickle  |
|    📊 **Data Processing**   | Pandas           |
|  🔢 **Numerical Computing** | NumPy            |
|     📈 **Visualization**    | Matplotlib       |
|     🎨 **Visualization**    | Seaborn          |
|       💻 **Frontend**       | HTML5            |
|        🎨 **Styling**       | CSS3             |
|   ⚡ **Client-side Logic**   | JavaScript       |
|   📓 **Model Development**  | Jupyter Notebook |

</p>

---

# 📊 Data Sources

HealSync works with multiple agricultural datasets:

```text
📂 dataset/
│
├── 🧪 pesticides.csv
│
├── 🌧️ rainfall.csv
│
├── 🌡️ temp.csv
│
├── 🌾 yield_df.csv
│
└── 🌱 yield.csv
```

These datasets provide the foundation for the project's prediction and analysis modules.

---

# 🧠 Model Layer

The trained models and preprocessing components are stored separately inside the `models` directory.

```text
models/
│
├── 🦠 disease_encoder.pkl
│
├── 🤖 disease_prediction_model.pkl
│
├── 📏 disease_scaler.pkl
│
├── 🧪 fertilizer_recommender.pkl
│
├── 🌦️ weather_model.pkl
│
├── 🌾 yield_prediction_model.pkl
│
├── 📏 yield_scaler.pkl
│
├── 🐍 prediction_models.py
│
└── 📄 __init__.py
```

This separation keeps the application logic and trained models organized and makes it easier to update individual prediction components.

---

# 📁 Project Structure

```text
HealSync/
│
├── 📄 app.py
│   └── Main Flask application
│
├── 📂 dataset/
│   ├── pesticides.csv
│   ├── rainfall.csv
│   ├── temp.csv
│   ├── yield_df.csv
│   └── yield.csv
│
├── 📂 models/
│   ├── disease_encoder.pkl
│   ├── disease_prediction_model.pkl
│   ├── disease_scaler.pkl
│   ├── fertilizer_recommender.pkl
│   ├── prediction_models.py
│   ├── weather_model.pkl
│   ├── yield_prediction_model.pkl
│   └── yield_scaler.pkl
│
├── 📂 static/
│   ├── 📂 css/
│   │   └── style.css
│   │
│   └── 📂 js/
│       ├── charts.js
│       └── main.js
│
├── 📂 templates/
│   ├── about.html
│   ├── base.html
│   ├── disease_prediction.html
│   ├── fertilizer_recommendation.html
│   ├── index.html
│   ├── weather_prediction.html
│   └── yield_prediction.html
│
├── 📓 training.ipynb
│   └── Data analysis & model training
│
└── 📦 requirements.txt
```

---

# ⚡ Getting Started

## 1️⃣ Clone The Repository

```bash
git clone https://github.com/keshavkapill/healsync.git
```

```bash
cd healsync
```

---

## 2️⃣ Create A Virtual Environment

### 🪟 Windows

```bash
python -m venv venv
```

Activate it:

```bash
.\venv\Scripts\activate
```

### 🐧 macOS / Linux

```bash
python3 -m venv venv
```

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🤖 Train The Models

The trained models are already included in the `models/` directory.

If you want to retrain or understand the complete machine-learning pipeline, open:

```bash
jupyter notebook training.ipynb
```

Then execute the notebook cells sequentially.

```text
📓 Jupyter Notebook
       │
       ▼
📊 Load Data
       │
       ▼
🧹 Preprocess
       │
       ▼
🤖 Train Models
       │
       ▼
📈 Evaluate
       │
       ▼
💾 Save Models
```

---

# ▶️ Run HealSync

Start the Flask application:

```bash
python app.py
```

The application will typically be available at:

```text
http://127.0.0.1:5000/
```

Open the URL in your browser and start exploring HealSync.

---

# 🌐 Application Modules

Once the application is running, you can access:

<table>
<tr>
<th>Route</th>
<th>Purpose</th>
</tr>

<tr>
<td>🏠 <code>/</code></td>
<td>HealSync Home</td>
</tr>

<tr>
<td>ℹ️ <code>/about</code></td>
<td>Project Information</td>
</tr>

<tr>
<td>🌾 <code>/yield-prediction</code></td>
<td>Crop Yield Prediction</td>
</tr>

<tr>
<td>🦠 <code>/disease-prediction</code></td>
<td>Disease Risk Assessment</td>
</tr>

<tr>
<td>🧪 <code>/fertilizer-recommendation</code></td>
<td>NPK Fertilizer Recommendation</td>
</tr>

<tr>
<td>🌦️ <code>/weather-prediction</code></td>
<td>Rainfall Prediction</td>
</tr>

</table>

---

# 🔌 API Endpoints

HealSync also exposes API endpoints for programmatic access.

```text
POST /api/predict-yield
```

🌾 Predict crop yield.

```text
POST /api/predict-disease
```

🦠 Assess disease risk.

```text
POST /api/recommend-fertilizer
```

🧪 Generate fertilizer recommendations.

```text
POST /api/predict-weather
```

🌦️ Predict future rainfall.

For the exact request payload and response structure, refer to `app.py`.

---

# 📡 API Architecture

```text
             🌐 CLIENT
                │
                ▼
          📡 HTTP REQUEST
                │
                ▼
          🐍 FLASK API
                │
        ┌───────┼────────┐
        │       │        │
        ▼       ▼        ▼
      🌾 ML    🦠 ML    🧪 RULES
        │       │        │
        └───────┼────────┘
                │
                ▼
          📊 PREDICTION
                │
                ▼
         📡 JSON RESPONSE
```

---

# 📈 Visualization

HealSync includes JavaScript-based chart functionality through:

```text
static/js/charts.js
```

and application interaction through:

```text
static/js/main.js
```

This allows prediction results and agricultural insights to be presented through an interactive web interface.

---

# 🎯 What Problem Does HealSync Solve?

Traditional agricultural decision-making can involve uncertainty around:

```text
🌾 Expected Crop Yield
        +
🦠 Disease Risk
        +
🧪 Fertilizer Requirements
        +
🌦️ Weather Conditions
        ↓
❓ Difficult Decisions
```

HealSync attempts to bring these factors together:

```text
🌾 Yield Prediction
        +
🦠 Disease Assessment
        +
🧪 Fertilizer Recommendation
        +
🌦️ Weather Analysis
        ↓
🧠 DATA-DRIVEN INSIGHTS
        ↓
🌱 SMARTER AGRICULTURAL DECISIONS
```

---

# 💡 Why This Project Is Interesting

HealSync combines **three different approaches to intelligent systems**:

<table>
<tr>

<td align="center" width="33%">

### 🤖 Machine Learning

Used where patterns in historical data can be learned.

</td>

<td align="center" width="33%">

### 🧠 Rule-Based Intelligence

Used for domain-specific fertilizer recommendations.

</td>

<td align="center" width="33%">

### 📊 Data Analytics

Used to understand agricultural and weather patterns.

</td>

</tr>
</table>

This hybrid approach makes the system more flexible than relying exclusively on a single machine-learning model.

---

# 🌍 Potential Applications

<table>
<tr>

<td align="center">

🌾<br> <b>Farmers</b><br> <sub>Support farming decisions</sub>

</td>

<td align="center">

🏢<br> <b>Agricultural Organizations</b><br> <sub>Analyze agricultural trends</sub>

</td>

<td align="center">

🔬<br> <b>Researchers</b><br> <sub>Experiment with ML models</sub>

</td>

<td align="center">

🎓<br> <b>Students</b><br> <sub>Learn applied ML</sub>

</td>

</tr>
</table>

---

# 🧠 What I Learned

Building HealSync provided practical experience with:

* 🐍 Python
* 🌐 Flask application development
* 🤖 Machine learning
* 🌲 Random Forest
* 📈 Linear Regression
* 📊 Data preprocessing
* 🧹 Data cleaning
* 🧪 Feature preparation
* 💾 Model serialization
* 📡 REST APIs
* 🎨 HTML/CSS/JavaScript
* 📈 Data visualization
* 📓 Jupyter Notebook
* 🌾 Applying ML to agricultural problems

---

# 🔮 Future Roadmap

```text
🚀 HEALSYNC ROADMAP

├── 🌦️ Real-Time Weather API Integration
│
├── 🗺️ Location-Based Agricultural Insights
│
├── 📱 Mobile-Friendly Progressive Web App
│
├── 🤖 Advanced ML Models
│
├── 🌾 More Crop-Specific Models
│
├── 🦠 Image-Based Plant Disease Detection
│
├── 🧪 Soil Nutrient Prediction
│
├── 💧 Smart Irrigation Recommendations
│
├── 📊 Farmer Analytics Dashboard
│
├── 🌐 Multilingual Farmer Interface
│
└── 📱 Mobile Application
```

---

# ⚠️ Important Note

HealSync is an **educational and experimental agricultural decision-support project**.

Its predictions and recommendations should not be treated as guaranteed agricultural outcomes.

Actual crop yield, disease occurrence, fertilizer requirements and weather conditions depend on many real-world factors that may not be represented in the available datasets.

Farmers should combine model outputs with **local agricultural expertise, soil testing, weather services and professional agricultural advice** before making significant decisions.

---

# 🤝 Contributing

Contributions are welcome!

Want to improve HealSync?

```text
🍴 FORK
   ↓
🌿 CREATE BRANCH
   ↓
🧑‍💻 MAKE CHANGES
   ↓
🧪 TEST
   ↓
💾 COMMIT
   ↓
🚀 PUSH
   ↓
🔀 PULL REQUEST
```

You can contribute by:

* 🐛 Fixing bugs
* 💡 Suggesting features
* 🤖 Improving ML models
* 📊 Improving data analysis
* 🎨 Improving UI
* 🌾 Adding agricultural datasets
* 🌦️ Adding real-time weather functionality

---

# ⭐ Support The Project

If you found HealSync interesting or useful:

<p align="center">

⭐ **Star the repository**

🍴 **Fork the project**

🐛 **Report issues**

💡 **Suggest improvements**

🤝 **Contribute**

</p>

<p align="center">

<a href="https://github.com/keshavkapill/healsync">

<img src="https://img.shields.io/badge/⭐%20STAR%20HEALSYNC-181717?style=for-the-badge&logo=github&logoColor=white"/>

</a>

</p>

---

# 👨‍💻 Built By

<p align="center">

<a href="https://github.com/KeshavKapill">

<img src="https://github.com/keshavkapill.png" width="120" height="120" alt="Keshav Kapil"/>

</a>

</p>

<h2 align="center">Keshav Kapil</h2>

<p align="center">

💻 Full-Stack Developer   •   🤖 ML Enthusiast   •   ☁️ Cloud Learner

</p>

<p align="center">

<a href="https://github.com/KeshavKapill">
<img src="https://img.shields.io/badge/GitHub-KeshavKapill-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

  

<a href="https://www.linkedin.com/in/keshavkapil15/">
<img src="https://img.shields.io/badge/LinkedIn-Keshav%20Kapil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

# 📊 GitHub Activity

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=keshavkapill&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" width="48%"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=keshavkapill&theme=transparent&hide_border=true" width="48%"/>

</p>

---

# 💬 Let's Connect

<p align="center">

Interested in **AI • Machine Learning • Agriculture Technology • Full-Stack Development • Cloud**?

<br><br>

### 🤝 Let's connect and build something impactful.

</p>

<p align="center">

<a href="https://github.com/KeshavKapill">
<img src="https://img.shields.io/badge/🐙%20GITHUB-Follow%20Me-181717?style=for-the-badge&logo=github"/>
</a>

 

<a href="https://www.linkedin.com/in/keshavkapil15/">
<img src="https://img.shields.io/badge/💼%20LINKEDIN-Connect%20With%20Me-0A66C2?style=for-the-badge&logo=linkedin"/>
</a>

</p>

---

<p align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=150&section=footer"/>

</p>

<p align="center">

### 🌱 Data → 🤖 Intelligence → 🌾 Better Agriculture

<br>

<sub>© 2026 Keshav Kapil • HealSync</sub>

</p>
