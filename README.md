# Food Delivery Data Analysis

This repository contains a Jupyter Notebook created using **Google Colab** for analyzing a food delivery dataset as part of an internship assignment.  
The notebook demonstrates data loading, integration, and analysis using multiple real-world data formats.

---

## 📂 Datasets Used

The analysis is performed using three different data sources:

- **orders.csv**  
  Transactional order data containing order details and order value.

- **users.json**  
  User master data containing the user city and membership type (Gold / Regular).

- **restaurants.sql**  
  Restaurant master data containing cuisine type and restaurant ratings.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- SQLite  
- Google Colab (Jupyter Notebook environment)

---

## 🔗 Data Integration Approach

- Orders data is merged with users' data using `user_id.`
- Orders data is merged with restaurant data using `restaurant_id.`
- **LEFT JOINs** are used to ensure all order records are retained

---

## 📊 Analysis Performed

The notebook includes the following analyses:

- Total and average order value calculations
- Gold vs Regular membership comparison
- City-wise revenue analysis
- Cuisine-wise performance analysis
- Rating-based revenue insights
- Quarterly revenue trends

---

## 📁 Repository Contents

- **food_delivery_data_analysis.ipynb**  
  Main Jupyter Notebook containing the complete end-to-end analysis

---

## ✅ Notes

- The repository is public for evaluation purposes
- The notebook runs top-to-bottom without errors
- All results are generated programmatically using Python

---

**Author:** Yashashvi Nandanwar  


**Author:** Yashashvi Nandanwar  
