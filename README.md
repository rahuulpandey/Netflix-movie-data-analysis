# 📊 Netflix Data Analysis

## Executive Summary  

This project analyzes a dataset of **9,827 Netflix titles** with the aim of uncovering insights into movie trends, genres, popularity, and audience reception.  

---

## 🔹 Data Preparation  
- Dataset contained **9 columns** and was free from missing or duplicate values.  
- **Release_Date** was converted from string to **year** format for better trend analysis.  
- Non-essential columns like *Overview*, *Original Language*, and *Poster URL* were dropped.  
- **Genre** column was cleaned and split into categorical values.  
- **Vote Average** was categorized into four groups: *Popular, Average, Below Average, Not Popular*.  

---

## 🔹 Key Insights from Analysis  
1. **Release Trends:**  
   - Majority of movies were released post-2000, showing rapid growth in Netflix’s content library.  
   - Significant increase in production in the **2010s**.  

2. **Genre Distribution:**  
   - Top genres included *Drama*, *Comedy*, *Thriller*, and *Action*.  
   - Multi-genre movies were common, with combinations like *Drama + Romance* dominating.  

3. **Popularity & Ratings:**  
   - Outliers were observed in the **Popularity** column, with few titles disproportionately popular.  
   - Most movies fell under the *Average* and *Below Average* categories in **Vote Average**.  

4. **Language Trends:**  
   - Although English dominated, Netflix included significant contributions from non-English films, especially in **Spanish, Hindi, and Korean**.  

---

## 🔹 Visualizations & Charts  
- **Bar charts & histograms** highlighted genre frequency and release year distribution.  
- **Boxplots** were used to identify outliers in popularity.  
- **Pie/Donut charts** illustrated language contribution across the platform.  
- **Categorical plots** showed the relationship between genres and vote categories.  

---

## 🔹 Conclusion  
The analysis reveals that Netflix has **grown rapidly post-2000**, with an increasing shift toward **multi-genre and international films**. While a few movies dominate in popularity, the majority receive **average audience ratings**. This suggests Netflix’s strategy focuses on **diversity of content** rather than relying solely on blockbuster hits.  

---

## 📌 Technologies Used  
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn for data visualization  
- Jupyter Notebook for analysis  

---

## 🚀 How to Use  
1. Clone this repository.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook "netflix data analysis.ipynb"
   ```  

---

## 📈 Author  
Created by Rahul | BTech Data Science Student  
