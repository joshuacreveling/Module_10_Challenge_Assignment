# Module 10 Challenge - Crypto Clustering

---

## Description

In this Jupyter Lab Notebook, we combine financial Python programming skills with our new unsupervised learning skills.  

In this assignment we compare Crypto clusters by utlizing two techniques: 
1.  Cluster cryptocurrencies with K-means using original data
2.  Cluster cryptocurrencies with K-means using the PCA data 

After performing the two clustering technqiques, we use visualization tools to compare the results from each. 

The sections of this notebook are as follows: 

* Import the Data (provided in the starter code)
* Prepare the Data (provided in the starter code)
* Find the Best Value for `k` Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for `k` Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results

---

## Technologies

This project leverages JupyterLab Version 3.0.14 in association with Anaconda distribution and the Conda package manager.  The following packages are also used: 

* [pandas](https://github.com/pandas-dev/pandas) - Data analysis toolkit for Python.

* [hvPlot](https://github.com/holoviz/hvplot) - A high-level plotting API for the PyData ecosystem built on HoloViews.

* [sklearn.cluster](https://scikit-learn.org/stable/modules/clustering.html) - Clustering algorithm

* [sklearn.decomposition](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) - Principal component analysis (PCA)

* [sklearn.preporcessing](https://scikit-learn.org/stable/modules/preprocessing.html) - Standardization, or mean removal and variance scaling

---

## Installation Guide

Before running the application, install Python modules Pandas, hvPlot, SQLAlchemy and Voila:

```python

  conda install pandas

  conda install -c pyviz hvplot

  pip install -U scikit-learn
```
---

## Contributors

Joshua Creveling

Email: josh.creveling22@gmail.com

GitHub: https://github.com/joshuacreveling

LinkedIn: https://www.linkedin.com/in/joshua-creveling/

*Starter template provided by Trilogy Education Services*

---

## License

MIT
