# Facebook Ads
This project provides a complete, end-to-end case study using publicly available Facebook ad campaign data. It is designed to showcase real-world data science workflows in the advertising industry, from exploratory analysis to statistical testing and machine learning.
## 📁 Project Structure

**Notebook**: `full_facebook_ad_project.ipynb`

Sections:

1. **Exploratory Data Analysis (EDA)**  
   - Visualize click-through rates (CTR), impressions, and campaign spend
   - Analyze performance by demographics (gender, age)
   - Spot trends and outliers

2. **A/B Testing Simulation**  
   - Simulate two ad variants (A/B)
   - Calculate CTR for each group
   - Perform statistical significance testing using a Z-test for proportions

3. **Click Prediction Model (TensorFlow)**  
   - Build a binary classifier to predict if a user clicks an ad
   - Use deep learning with TensorFlow/Keras
   - Evaluate model using classification metrics and ROC-AUC

---

## 📊 Dataset

Facebook ad campaign performance data (CSV). Typical fields include:
- Age
- Gender
- Impressions
- Clicks
- Spend
