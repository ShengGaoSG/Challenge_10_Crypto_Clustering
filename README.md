# Challenge 10 Crypto Clustering

This is a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. I’ll combine my financial Python programming skills with the new unsupervised learning skills that I acquired in this module.


The CSV file contains price change data of cryptocurrencies in different periods.

The steps for this challenge are broken out into the following sections:

* Import the Data
* Prepare the Data
* Find the Best Value for k Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for k Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results

---

## Technologies

This was developed with Anaconda, in a development environment running Python 3.7.13, which includes Pandas, and in addition sklearn with Kmeans, PCA, StandardScaler.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  conda activate dev
  pip install -U scikit-learn
  conda install -c pyviz hvplot
```


---

## Contributors

Sheng Gao
sheng_gao@outlook.com

---

## License

Columbia Engineering FinTech Boot Camp
