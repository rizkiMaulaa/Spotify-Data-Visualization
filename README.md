# 🎵 Spotify Data Visualization

This project aims to perform **data visualization** of the Spotify dataset, calculate the churn rate, analyze the causes of churn, and determine development recommendations based on the analysis.

---

## 📂 Dataset

The dataset used comes from **Spotify Dataset 2025**. This dataset contains user information, including:
- user_id → Unique identifier for each user
- gender → User gender (Male/Female/Other)
- age → User age
- country → User location
- subscription_type → Type of Spotify subscription (Free, Premium, Family, Student)
- listening_time → Minutes spent listening per day
- songs_played_per_day → Number of songs played daily
- skip_rate → Percentage of songs skipped
- device_type → Device used (Mobile, Desktop, Web)
- ads_listened_per_week → Number of ads heard per week
- offline_listening → Offline listening minutes
- is_churned → Target variable (0 = Active, 1 = Churned)

---

## 🛠️ Tools & Libraries

This project uses the Python programming language with the following core libraries:
- `pandas` → data manipulation
- `numpy` → numerical calculations
- `matplotlib` → data visualization
- `seaborn` → statistical visualization
- `math` → supports plot layout calculations

---

## 📊 Analisis & Visualisasi

Several analyses performed in the notebook:
1. Churn percentage calculation.
2. Churn distribution visualization.
3. Visualization of the distribution of features: age, listening time, songs played per day, skip rate, ads listened per week, country, gender, subscription type, and offline listening.
4. Comparison of listening time with churn/non-churn.
5. Visualization of correlation between features using a correlation heatmap.
6. Visualization of churn distribution by gender.
7. Visualization of churn distribution by subscription type.
8. Visualization of churn distribution by device type.
9. Visualization of churn distribution in the 10 countries with the most users.

---

## 🚀 Conclusion

- This analysis revealed a churn rate of 25.89% among 8,000 users worldwide. This is significant and could impact the company's revenue from subscription features.
- Furthermore, user churn behavior is influenced by several factors, such as subscription type, which has a positive correlation (0.78) and offline listeners, which has a negative correlation (-0.68).
- The analysis revealed that family subscription users have the highest churn rate compared to other subscription types.
- Furthermore, mobile users are the device with the highest churn rate. Furthermore, based on country, Germany (DE), Pakistan (PK), and France (FR) have the highest churn rates.

---

## 🚀 Recommendation

Recommendations based on the conclusions above:
- Improve offline features to reduce churn.
- Evaluate Family Plan pricing and benefits.
- Focus retention strategies on mobile users (e.g., more user-friendly UX/ads).
- Adjust local strategies in countries with high churn.
