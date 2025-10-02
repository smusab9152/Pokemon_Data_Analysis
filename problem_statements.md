# 🎯 Problem Statements – Pokémon Dataset Project

This document outlines the **data analysis** and **machine learning** problem statements explored in this project.  
The dataset contains Pokémon stats, types, generations, and legendary status, enabling both **descriptive analytics** and **predictive modeling**.
---
## 📊 Data Analysis (EDA)

1. **Pokémon Types Distribution**
   - Which Pokémon types (e.g., Water, Fire, Dragon) are the most common?
   - Which type combinations are rarest?

2. **Stat Comparisons**
   - Which type has the highest average Attack, Defense, or Speed?
   - Do dual-type Pokémon generally have better total stats than single-type Pokémon?

3. **Legendary Pokémon Analysis**
   - How do Legendary Pokémon differ in stats compared to non-Legendary?
   - Is the distribution of Legendary Pokémon even across Generations?

4. **Generational Insights**
   - Which Generation introduced the strongest Pokémon on average?
   - Are newer Generations more balanced than older ones?

5. **Correlation Studies**
   - Are Attack and Defense correlated?
   - Does Speed correlate with HP or Total stats?

6. **Outlier Detection**
   - Which Pokémon are statistical outliers in terms of Total or Speed?
   - Are there “glass cannon” Pokémon (very high Attack, very low Defense)?
---
## 🤖 Machine Learning

### 🟢 Classification
1. **Legendary Prediction**
   - **Problem**: Predict whether a Pokémon is Legendary or not.  
   - **Features**: Base stats, Type 1, Type 2, Generation.  
   - **Target**: Legendary (True/False).  
   - **Models**: Logistic Regression, Random Forest, Gradient Boosted Trees.  

2. **Primary Type Prediction**
   - **Problem**: Predict a Pokémon’s primary type based on its stats.  
   - **Features**: HP, Attack, Defense, Sp. Atk, Sp. Def, Speed, Total.  
   - **Target**: Type 1.  
   - **Models**: Multiclass Classification (Decision Tree, Random Forest, Neural Network).  
---
### 🔵 Clustering
3. **Pokémon Archetypes (Unsupervised Learning)**
   - **Problem**: Cluster Pokémon into groups based on their stats.  
   - **Features**: HP, Attack, Defense, Sp. Atk, Sp. Def, Speed.  
   - **Expected Clusters**: Tanks, Sweepers, Balanced, Glass Cannons, etc.  
   - **Models**: K-Means, Gaussian Mixture Models.  
---
### 🟡 Regression
4. **Predicting Total Stats**
   - **Problem**: Predict the **Total stat score** of a Pokémon based on individual stats.  
   - **Features**: HP, Attack, Defense, Sp. Atk, Sp. Def, Speed.  
   - **Target**: Total.  
   - **Models**: Linear Regression, Random Forest Regressor.  
---
### 🔴 Recommendation (Optional / Fun)
5. **Pokémon Team Builder**
   - **Problem**: Given a Pokémon (with stats + type), recommend **complementary Pokémon** to build a balanced team.  
   - **Approach**: Similarity search using clustering or cosine similarity.  

---

✅ These problem statements provide a **mix of descriptive analytics and predictive modeling**, making the project both **analytical** and **machine learning-driven**.  
This ensures the project is **portfolio-ready** and demonstrates skills in EDA, supervised ML, and unsupervised ML.
