🏨 GoIbibo Indian Hotels Analytics

A full-stack analytics capstone leveraging Indian hotel data to optimize pricing, amenities, and customer satisfaction, while identifying emerging markets across cities and brands.

📈 Key Outcomes

Pricing Levers: Quantified amenity premiums, landmark proximity effects, and city-level competitiveness.

Satisfaction Drivers: Rating regression and sentiment classification with explainable features.

Expansion Roadmap: City clustering by listing growth, price level, and rating trends.

/etl
 ├── csv_to_sql.py               # ETL loader
 └── preprocess.ipynb            # Amenities parsing, tiering, sentiment prep

/sql
 ├── schema.sql                  # Database schema (PostgreSQL)
 └── answers.sql                 # 10 business queries with CTEs

/dashboards
 ├── Power BI & Tableau files
 └── Screenshots

/ml
 ├── 01_rating_prediction.ipynb
 ├── 02_sentiment_classification.ipynb
 └── 03_emerging_location_clustering.ipynb

/docs
 ├── executive_summary.pptx
 └── data_dictionary.md


🧮 Advanced SQL Deliverables

Hotel Footprint & Tiering: Hotels per city, avg. price, and tier index

Amenity Impact: Price/star deltas by amenity flags

City Competitiveness: Top 5 cities by variance & amenity coverage

Sentiment vs Stars: Avg. sentiment by star rating band

Landmark Advantage: Price/rating lift for near-landmark hotels

Brand Ratings: Avg. rating and listing count by brand

Emerging Locations: Listing growth and rating differentials

📊 Dashboards (Power BI / Tableau)

Key Pages:

Market Overview: City heatmap, avg price/rating, tier distribution

Amenities & Pricing: Amenity frequency, price-by-amenity box plots

Competitive Landscape: Price/rating by city/brand

Review Sentiment: Sentiment histograms and scatter plots

Emerging Markets: Listing growth and rating gaps

Filters: City, Brand, Price Tier, Amenity Flags, Date

🤖 Machine Learning

Rating Prediction: RandomForest / XGBoost

Features: price tier, amenities, stars, brand, city, sentiment, landmark proximity

Metrics: RMSE, R², SHAP feature importances

Sentiment Classification: TF-IDF + Logistic Regression / Multinomial NB

Metrics: Accuracy, F1

Emerging Location Clustering: K-means on growth, price, and rating trends

Features scaled and evaluated via silhouette score

💼 Business Impact Highlights

Price Smarter: Quantify amenity premiums & landmark uplifts for upselling.

Win Reviews: Focus on features driving higher ratings & sentiment.

Expand Wisely: Identify fast-growing cities with positive rating trends.

🧾 Credits & References

Dataset structure inspired by publicly available GoIbibo hotel datasets.

CSV-to-SQL ETL adapted from open-source PostgreSQL loaders.

Tech Stack:
Python, PostgreSQL, Power BI, Tableau, Pandas, Scikit-learn, Matplotlib, Seaborn, TF-IDF, XGBoost, SHAP
