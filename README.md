# 🍴 Restaurant Recommendation System  

## 📌 Project Overview  
This project builds a **Restaurant Recommendation System** that suggests dining options based on user preferences such as cuisine, price range, and ratings. With the growing demand for personalized dining experiences on food delivery and review platforms, this system demonstrates how **data preprocessing, feature engineering, and content-based filtering** can be combined to provide relevant and user-friendly recommendations.  

The approach follows these steps:  
1. **Preprocessing Dataset** – Cleaning missing values, handling duplicates, encoding categorical variables, and preparing restaurant attributes for recommendation.  
2. **Defining Criteria** – Using features like cuisine type, price range, and aggregate rating to align recommendations with user expectations.  
3. **Content-Based Filtering** – Matching restaurants to users by comparing restaurant attributes with user-input preferences.  
4. **Testing Recommendations** – Providing sample user queries and evaluating the quality of the recommended restaurants.  

This ensures the system delivers accurate, meaningful, and tailored suggestions to users.  

---

## ⚙️ Features Implemented  
- Data cleaning (handling missing values, duplicates, type conversions).  
- Creation of **price categories** (Budget, Moderate, Expensive, Luxury).  
- Grouping of **cuisines by continent/region** (Asian, Indian, Middle Eastern, European, American, African, Other).  
- Interactive **user input system** (choose cuisine group, specific cuisines, budget, and minimum rating).  
- Content-based recommendation using **text similarity** on restaurant attributes.  
- Final recommendations displayed in a **tabular format** with similarity score.  

---

## 🗂️ File Structure  
```
📂 Restaurant-Recommendation
 ┣ 📜 dataset.csv            # Input dataset
 ┣ 📜 recommendation.py      # Main code for preprocessing + recommendation
 ┣ 📜 README.md              # Project documentation
 ┗ 📜 requirements.txt       # Dependencies (pandas, numpy, scikit-learn, tabulate)
```

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/restaurant-recommendation.git
   cd restaurant-recommendation
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the program  
   ```bash
   python recommendation.py
   ```
4. Follow the interactive prompts to select cuisines, budget, and rating.  

---

## 📊 Sample Output  
```
===== Your Preferences and Suggested Restaurants =====
+------------------+-------------------+----------+----------------+----------------+-------------------+
| Chosen Group     | Selected Cuisines | Budget   | Minimum Rating | Restaurant     | Similarity Score  |
+------------------+-------------------+----------+----------------+----------------+-------------------+
| Indian           | North Indian      | Moderate | 4.0            | Delhi Zaika    | 0.912             |
| Indian           | North Indian      | Moderate | 4.0            | Spice Hub      | 0.876             |
```

---

## 📌 Conclusion  
This project demonstrates the use of **content-based recommendation systems** in the food industry. By preprocessing data, classifying cuisines, and applying similarity measures, the system effectively recommends restaurants tailored to user preferences.  
