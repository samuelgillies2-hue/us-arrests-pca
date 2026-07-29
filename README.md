## US Crime Rate Analysis — PCA & Clustering

An unsupervised machine learning project exploring relationships between violent 
crime rates and urbanization across all 50 US states, using the classic 
US Arrests dataset (1973).

### What this project does
- Performs correlation analysis on crime and urbanization variables
- Applies Principal Component Analysis (PCA) to reduce dimensionality
- Visualizes state groupings with a biplot of the first two principal components
- Compares K-means and hierarchical (Ward-linkage) clustering to segment states 
  into groups with similar crime/urbanization profiles

### Key findings
- The first two principal components explain ~87% of total variance
- PC1 captures "overall crime," PC2 captures "urbanization" — largely independent 
  dimensions
- K-means and hierarchical clustering agree on cluster assignment >80% of the time

### Tools
Python, Pandas, Scikit-learn (PCA, KMeans, AgglomerativeClustering), Matplotlib, 
Seaborn

### Files
- `unsupervised_task.ipynb` — full analysis notebook
- `UsArrests.csv` — dataset
