# CryptoClustering
In this challenge, I used my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

📊 Crypto Clustering with K-Means & PCA

This project applies unsupervised machine learning techniques to analyze and cluster cryptocurrencies based on their 24-hour and 7-day price changes. Using K-Means and PCA, the project identifies natural groupings in the data and evaluates the impact of dimensionality reduction on clustering results.

🚀 Technologies Used

Python (Jupyter Notebook)
pandas, scikit-learn, hvPlot
StandardScaler, KMeans, PCA

🔍 Project Goals

Normalize crypto market data using StandardScaler
Determine optimal clusters (k) using the Elbow Method
Visualize clusters based on price movements
Apply Principal Component Analysis (PCA) to reduce dimensionality
Compare clustering performance with and without PCA

📈 Final Outputs

Interactive Elbow Curve Plots (Original & PCA Data)
Clustering Scatter Plots (Original & PCA Reduced)
Insightful analysis on the effect of using fewer features

✅ Key Findings

Optimal number of clusters: k = 3
PCA preserved 100% of the variance using just 2 components
Clustering with PCA provided slightly cleaner visual groupings with less noise
Dimensionality reduction did not negatively impact clustering performance

🧠 Lessons Learned

Unsupervised learning is powerful for exploring unknown patterns
PCA can simplify complex datasets without major information loss
Visualizing results is essential for interpreting model outcomes

💡 Built by Haley Armenta during my machine learning coursework
Code help from ChatGPT to help me understand why some of my lines were erroring out.
