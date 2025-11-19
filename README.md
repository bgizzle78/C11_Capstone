# 🌍 Global Happiness – NewForce - Cohort 11 Capstone Project

## 📋 Table of Contents
1. 🎯 Motivation  
2. ❓ Questions  
3. 🔧 Acquiring & Normalizing the Data  
4. ⚠️ Problems & Challenges  
5. 🛠️ Technologies Used  
6. 📚 Sources  

---

## 🎯 Motivation
Happiness is not only a personal concern but also a societal one, influencing productivity, stability, and overall quality of life. Governments and organizations increasingly use happiness measures as part of their decision-making frameworks. By analyzing Global Happiness data, this project seeks to better understand which factors most strongly influence happiness and how these vary across countries and regions. This topic is engaging because it blends economics, sociology, and psychology into measurable data-driven insights.

---

## ❓ Questions

### **Primary Question**
**💡 What are the key drivers of national happiness, and how do they differ across countries?**

### Supporting Questions
- 💰 How does wealth relate to happiness?  
- 📉 When does money stop increasing well-being?  
- 🏥📚 How do health and education compare to GDP?  
- 🌟 What combination of factors creates the happiest countries?  
- 📈 What would happen if low-happiness countries improved key indicators?

---

## 🔧 Acquiring & Normalizing the Data

### 📦 Data Sources
I combined:
- 🌈 World Happiness Report (Country happiness scores and rankings)
- 🌐 World Bank Indicators (GDP, health expenditure, education expenditure)  
- 🗺️ World Bank Country Metadata (regions, income groups, ISO codes)

### 🧹 Cleaning & Normalization Steps
- Standardized WHR columns across years  
- Cleaned and aligned country names and ISO codes  
- Filtered World Bank metrics to relevant indicators  
- Pivoted World Bank data from long ➜ wide format  
- Removed aggregate/invalid regions  
- Synced years and merged everything into a single dataset  

---

## ⚠️ Problems & Challenges
- Country name mismatches 🏳️  
- Messy World Bank indicators requiring heavy reshaping 🔄  
- Sparse or inconsistent years 📉  
- WHR column inconsistencies 🧩  

---

## 🛠️ Technologies Used
- 🐍 Python (Pandas, NumPy, Plotly/Matplotlib/Seaborn, SKLearn)    
- 🖼️ PowerPoint for presentation design  
- 🔄 Git/GitHub for version control  

---

## 📚 Sources
- 🌍 World Happiness Report  
- 🌐 World Bank Data (World Development Indicators + Country Metadata)
