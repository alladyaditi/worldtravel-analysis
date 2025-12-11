Here is a **professional, polished, and portfolio-ready README.md** for your **World Travel Analysis** project.
You can copy and paste it directly into your `README.md` file in your project folder.

---

# 🌍 **World Travel Analysis**

### **Affordable vs. Luxury Destinations — A Data-Driven Comparison**

This project analyzes worldwide travel data to identify the **most affordable destinations** for budget-conscious travelers and the **most luxurious travel locations** for those seeking high-end experiences. By comparing cities across multiple travel attributes—including **culture**, **cuisine**, **nature**, **adventure**, and more—this analysis highlights which regions provide the best value and which offer premium, upscale experiences.

---

## 📁 **Project Structure**

```
worldtravel-analysis/
│
├── data/
│   └── Worldwide Travel Cities Dataset (Ratings and Climate).csv
│
├── notebooks/
│   └── world_travel_analysis.ipynb
│
├── visuals/
│   ├── piecharts_budget_levels.png
│   ├── rankings_top_cities.png
│   └── attribute_barplots.png
│
├── reports/
│   └── world_travel_analysis.html
│
└── README.md
```

---

## 🧠 **Objective**

This project aims to:

* Compare **budget**, **mid-range**, and **luxury** travel destinations
* Identify which attributes (culture, cuisine, nature, etc.) influence each budget level
* Rank global cities by a **travel quality score**
* Highlight the best destinations for budget travel
* Highlight the top luxury travel cities
* Produce visual insights using Python (and optionally Tableau)

---

## 🧹 **Data Overview**

The dataset includes **560 cities**, with attributes such as:

* **City, Country, Region**
* **Latitude & Longitude**
* **Monthly Climate**
* **Ideal Visit Duration**
* **Budget Level (budget, mid-range, luxury)**
* **Travel ratings:**

  * Culture
  * Adventure
  * Nature
  * Beaches
  * Nightlife
  * Cuisine
  * Wellness
  * Urban Experience
  * Seclusion

There are **no missing values**, making the dataset ready for immediate analysis.

---

## 📊 **Methods & Analysis**

### ✔ 1. **Exploratory Data Analysis (EDA)**

* Distribution of travel attributes
* Average scores by budget level
* Attribute comparison across regions

### ✔ 2. **Pie Charts for Each Budget Category**

Pie charts visualize how culture, cuisine, nature, and other attributes shape:

* Budget destinations
* Mid-range destinations
* Luxury destinations

### ✔ 3. **Travel Score Calculation**

A combined metric was created:

```
travel_score = mean(culture, adventure, nature, cuisine, wellness, nightlife, beaches, urban, seclusion)
```

Cities are ranked globally and within each budget level.

### ✔ 4. **Ranking Analysis**

* Top budget-friendly cities
* Top luxury cities
* Best overall destinations

---

## ⭐ **Key Findings**

### 🟢 **Best Budget Destinations**

* **Thailand**
* **Colombia**
* **Philippines**

Many cities in these countries offer exceptional value, with strong scores in
**culture, cuisine, and nature**.

### 🔵 **Best Luxury Destinations**

* **Canada**
* **United States**
* **Australia**

Cities in Oceania—especially **Hawaii** and major Australian cities—offer diverse, high-quality travel experiences with strong scores across the same key attributes.

---

## 🧾 **Conclusion**

Budget destinations provide excellent cultural and natural experiences at lower costs, making them ideal for travelers on a budget.
Luxury destinations offer elevated travel quality—especially in culture, cuisine, and nature—often paired with premium and diverse experiences.

---

## 📈 **Visualizations**

Visuals created in Python include:

* Pie charts for each budget level
* Bar charts comparing attribute averages
* Rankings of cities by travel score

(Place PNG images in the `visuals/` folder and embed them here if desired.)

---

## 🛠️ **Technologies Used**

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook
* Tableau (optional for dashboard visualizations)
* Git & GitHub

---

## 🚀 **Future Improvements**

* Build a **Travel Recommendation System**
* Add **interactive maps** of destinations
* Integrate **climate suitability scoring**
* Enhance travel scores with weighting preferences
* Create a **Tableau Dashboard** for public viewing

---

## 👩‍💻 Author

**Aditi Allady**
Data Science & Analytics Portfolio
GitHub: github.com/alladyaditi

