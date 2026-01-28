# User Activity and Conversion Analysis

This project aims to analyze a platform’s user data (**profile information** and **product usage activities**) in order to:

- Identify which user groups are more active
- Determine which features increase **payment (conversion)** rates

---

## 📌 Project Objective

- Understand user behavior from a data-driven perspective
- Identify factors affecting activation and conversion rates
- Generate insights to support product and marketing strategies

---

## 📂 Datasets Used

Two main CSV files are used in this project:

1. **Dataset - Active User Activeness Data (1).csv**  
   - Contains users’ product and feature-level usage activities

2. **Dataset - User Profile Data (1).csv**  
   - Contains user profile information (device type, industry, payment status, etc.)

---

## 🔧 Data Preparation Steps

- Importing CSV files using Python
- Merging user profile and activity data via `user_id`
- Analyzing missing values (NaN)
- Treating users with no activity records as **users with zero product usage**
- Filling missing values with `0` to ensure analytical consistency

---

## 📊 Analyses Performed

### 1️⃣ Activation Rate Analysis

- Activation rates were calculated based on **device type** (Mobile vs. Desktop/Web)
- Results were visualized using charts

**Key Findings:**
- 📱 Mobile user activation rate: **8.4%**
- 💻 Desktop/Web user activation rate: **38.0%**
- Desktop users are approximately **4.5 times** more likely to activate than mobile users

---

### 2️⃣ Industry Analysis

- Distribution of users across different industries was examined
- For each industry:
  - Number of users
  - Payment (conversion) tendency

were analyzed.

**Key Insights:**
- Leading industries by user count:
  - Non-profit
  - Health Care
  - Education
- Industries with high payment rates:
  - Telecommunications
  - Insurance

---

### 3️⃣ Product Features and Conversion Analysis

- The impact of different product features (such as **forms**, **reports**, **AI agents**, etc.)
  on payment rates was compared
- Features that significantly increase the likelihood of conversion were identified

---

## 🧠 Technologies Used

- **Python 3**
- **Pandas** – Data manipulation and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** –
  - Machine learning models (Random Forest)
  - Model and evaluation metric infrastructure (prepared)

---

## 📈 Key Findings and Insights

- Device type plays a critical role in user activation
- Some industries have high user volume, while others offer stronger revenue potential
- Certain product features significantly increase conversion probability
- Proper handling of missing activity data improves the reliability of the analysis

---

## 🚀 Future Improvements

- Applying advanced machine learning models for activation and conversion prediction
- Time series analysis to observe user behavior trends over time
- A/B testing strategies to improve mobile user experience

---

## 👤 Note

This project is a sample study focused on understanding user behavior from a data analytics and business intelligence perspective and is open to further development.