# RetailPulse Analytics: Behavioral Segmentation Pipeline

## 📌 Project Overview
An end-to-end data analytics pipeline designed to decode consumer shopping patterns and optimize revenue strategies. This project moves from raw transactional data (3,900+ records) to a high-level Power BI dashboard, focusing on demographic segmentation and promotional ROI.

## 🚀 Key Features
- **Advanced Preprocessing:** Automated data cleaning using Python, featuring category-specific median imputation to handle missing ratings.
- **Feature Engineering:** Implemented Quantile-based binning (`pd.qcut`) for demographic balancing and engineered a numerical "Loyalty Frequency Index."
- **Multi-DB Integration:** Built a scalable ingestion engine using SQLAlchemy for MySQL, and MS SQL Server.
- **Relational SQL Analytics:** Developed complex queries to segment customers into 'New', 'Returning', and 'Loyal' tiers.
- **BI Insights:** Interactive Power BI dashboard identifying that Express Shipping users spend 12% more than standard users.

## 🛠️ Tech Stack
- **Languages:** Python (Pandas, SQLAlchemy, Scipy), SQL
- **Database:**  MySQL
- **Visualization:** Power BI, Seaborn
- **Documentation:** Jupyter Notebook

## 📊 Business Recommendations
- **Subscription Expansion:** Subscribers drive 45% of revenue; recommended a 10% shift in marketing spend toward subscription conversion.
- **Logistics Optimization:** High-spend users prefer Express Shipping; recommended a "Premium Shipping Tier" to increase retention.
- **Targeted Marketing:** Focus on the "Young Adult" segment ($62K revenue contribution) for upcoming seasonal campaigns.
