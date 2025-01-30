# Beverage Price Prediction: Data-Driven Pricing Strategy for Energy Drinks


🚀 **Predict the optimal price range for energy drinks based on consumer behavior, demographics, and preferences!** This project helps businesses make data-driven pricing decisions using machine learning.

🔗 **Live Demo**: [Streamlit App](https://beverage-price-prediction-manideep.streamlit.app/)  
📂 **GitHub Repository**: [Beverage Price Prediction](https://github.com/manideepcheekoti/beverage_price_prediction)

---

## 📌 Overview
Businesses often struggle to price their products optimally. This project builds a **machine learning model** that predicts the best price range for energy drinks based on factors like **consumer habits, brand awareness, health concerns, and regional differences**.

**Key Features:**
✅ Analyzes purchasing behavior of 30,000 respondents  
✅ Explores demographics (age, gender, zone) & financial data (income levels)  
✅ Uses **XGBoost**, achieving **93% accuracy**  
✅ Deploys an interactive **Streamlit app** for easy predictions  
✅ Integrates **MLflow & DagsHub** for experiment tracking and reproducibility  

---

## 📊 Data & Preprocessing
The dataset consists of **30,000+ responses**, covering:
- 🏠 **Demographics**: Age, Gender, Location (Metro/Rural)
- 💰 **Financial**: Income Levels
- 🍹 **Consumption Patterns**: Frequency, Brand Awareness, Preferred Flavors
- 🎯 **Target Variable**: Preferred **Price Range** for Energy Drinks

🔹 **Data Cleaning Steps:**
- Removed **duplicates** & handled **missing values** (e.g., missing income = "Not Reported")
- Used **box plots** to detect and fix outliers in age
- Standardized **categorical variables** (e.g., spelling corrections, label encoding, one-hot encoding)

---

## 🛠️ Feature Engineering
To make the model smarter, I created **custom features:**
- **CF_AB Score** = Combines **Consumption Frequency & Brand Awareness** for better insights  
- **ZAS Score** = Measures affluence based on **Zone & Income Levels**  
- **BSI (Brand Switching Index)** = Predicts if a user is likely to switch brands  
- **Age Grouping** = Segmented into 18–25, 26–35, etc., for better trend detection  

---

## 🔍 Exploratory Data Analysis (EDA)
### **Key Insights from Data Analysis:**
📌 **Consumption Frequency Matters**: Frequent consumers (5–7 times/week) prefer **premium products**, while infrequent consumers prioritize **affordability**.  
📌 **Health-Conscious Buyers**: They avoid **low-end products** and favor **brands emphasizing health benefits**.  
📌 **Brand Awareness & Switching**: Young consumers (18–25) are **price-sensitive** and open to **trying new brands**, while older consumers (46–55) focus on **brand loyalty & quality**.  
📌 **Income & Region Impact**: High-income & **metro consumers** prefer premium drinks, while **rural consumers** seek affordability.  
📌 **Packaging Preferences**: People who prefer **premium packaging** tend to be **repeat buyers** of high-end products.  

📊 **Graphs Used in EDA:**
- **Box Plots**: Identified outliers in **age & income**  
- **Bar Charts**: Showed how **health-conscious consumers** prefer premium brands  
- **Correlation Heatmaps**: Revealed strong links between **consumption habits & pricing preference**  

---

## 🚀 Model Training & Performance
I trained multiple models and found **XGBoost** to be the best performer:
| Model                | Accuracy |
|----------------------|----------|
| Logistic Regression | 76%      |
| Random Forest       | 89%      |
| LightGBM           | 91%      |
| **XGBoost**         | **93%**  |

✅ **Final Model: XGBoost (93% Accuracy)**  
✅ **Train-Test Split: 75%-25%**  
✅ **Hyperparameter tuning for optimization**  

🔍 **Experiment Tracking:** Used **MLflow & DagsHub** for versioning, tracking, and managing model performance.

---

## 🌐 Deployment: Streamlit App
I built an **interactive web app** using **Streamlit** to make the model easy to use.

🔹 **How It Works:**
1️⃣ User inputs customer **demographics, income, and preferences**  
2️⃣ The model predicts the **optimal price range** for energy drinks  
3️⃣ Businesses can make **data-driven pricing decisions** instantly!  

🚀 **Try it Live:** [Streamlit App](https://beverage-price-prediction-manideep.streamlit.app/)

---

## 🔮 Future Enhancements
🔹 Add real-time pricing data from **market trends**  
🔹 Incorporate **customer reviews** for sentiment analysis  
🔹 Develop an **API** for seamless integration with business systems  

---

## 💡 My Opinion & Learnings
This project helped me:
✅ Improve my **feature engineering** skills by creating meaningful derived features  
✅ Gain hands-on experience in **MLflow & DagsHub** for tracking models  
✅ Deploy a **fully functional ML model** in a real-world setting  

🤔 **Final Thought:** Pricing decisions shouldn’t be a **guessing game**. Data-driven insights can help businesses **set optimal prices**, boost **sales**, and enhance **customer satisfaction**!

---

## 🤝 Connect with Me
📌 **GitHub**: [@manideepcheekoti](https://github.com/manideepcheekoti)  
📌 **LinkedIn**: [My LinkedIn](https://www.linkedin.com/in/manideep-cheekoti/) 

⭐ If you found this project helpful, consider **starring** the repo!

