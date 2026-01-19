<<<<<<< HEAD
# US Road Accident Severity Analysis & Prediction
An end-to-end Machine Learning pipeline to analyze and predict accident severity using a massive dataset of 7.7 million records.

## 📌 Project Overview
This project focuses on identifying the key factors contributing to road accident severity across the United States. By leveraging a multi-gigabyte dataset, the model predicts the impact of an accident on traffic (Severity levels 1-4) based on environmental, temporal, and geospatial features.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Decision Tree, Logistic Regression, Naive Bayes)
* **Visualization:** Matplotlib, Seaborn
* **Geospatial Processing:** KMeans Clustering for coordinate analysis

## 🚀 Key Engineering Highlights
* **High-Volume Data Handling:** Processed and cleaned a dataset of **7.7 million records**, implementing strategic sampling of 1.2M rows for balanced training.
* **Advanced Feature Engineering:**
    * **Geospatial:** Converted Latitude/Longitude to 3D Cartesian coordinates and applied **KMeans Clustering** to identify high-risk accident zones.
    * **Temporal:** Implemented sine/cosine transformations for cyclical features (Hour, Month) to preserve seasonal patterns.
    * **High-Cardinality Encoding:** Managed thousands of unique cities and streets using frequency encoding.
* **Performance:** Achieved **~85% Test Accuracy** using a Decision Tree Classifier, significantly outperforming the linear baseline.

## 📊 Results & Insights
* **Infrastructural Impact:** Proximity to traffic signals and junctions showed a high correlation with severity levels.
* **Model Comparison:** While Logistic Regression provided a baseline of 77%, the Decision Tree model captured the non-linear complexities of accident data more effectively.

---
=======
# Airbnb Price Prediction & Market Insights

A statistical analysis and machine learning project to identify the primary drivers of rental pricing and provide actionable recommendations for hosts.

## 📌 Project Overview
The objective of this project is to analyze Airbnb listing data to understand which factors most significantly influence rental prices. By identifying these drivers, the project provides data-backed strategies for hosts to optimize their revenue and for the platform to improve user satisfaction.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Statsmodels (Linear Regression), Scikit-Learn (Machine Learning), Matplotlib, Seaborn (Visualization).
* **Statistical Techniques:** Log-scale transformations, Univariate and Bivariate analysis, Multiple Linear Regression.

## 🚀 Key Engineering & Analytical Highlights
* **Data Transformation:** Implemented **Log-scale transformations** on rental prices to address data skewness, ensuring the reliability of the statistical models.
* **Feature Analysis:** Quantified the impact of property features (capacity, bedrooms, bathrooms) and host policies (cancellation, booking type) on market value.
* **Predictive Modeling:** Developed a regression model that identifies key areas for revenue optimization.

## 📊 Results & Business Insights
* **Strongest Price Drivers:** Identified that property capacity and specific room types (Entire Home/Apartment) are the most significant predictors of higher rental costs.
* **Policy Impact:** Discovered that "Strict" cancellation policies and "Instant Bookable" settings generally lead to higher price points.
* **Strategic Recommendations:** * **For Hosts:** Maximize guest capacity and prioritize maintaining high review scores for premium pricing.
    * **For Platforms:** Promote "Instant Bookable" and highly-rated properties to enhance both host revenue and guest satisfaction.

## 💡 Key Learnings
* Mastered the application of statistical transformations to handle non-normal data distributions.
* Gained experience in translating complex model outputs into clear, actionable business recommendations for stakeholders.
* Refined the end-to-end data science workflow from exploratory analysis to model interpretation
>>>>>>> 4a2cd2d52007eda01cabb29333ad79dbc832012b
