# PROG 25211: AI and Machine Learning - Python
This repository contains a collection of practical exercises and laboratory work completed during the **PROG 25211** course at Sheridan College. The projects focus on exploring essential Data Analysis, Supervised Learning, Unsupervised Learning, and basic Model Deployment workflows using Python.

## 📂 Repository Structure & Project Breakdown

The repository is organized into distinct project folders based on the course curriculum:

### 1. 🚕 [01-Taxi-Data-Analysis-Visualization](./01-Taxi-Data-Analysis-Visualization)
* **Goal:** Basic exploratory data analysis and data plotting.
* **Core Tasks:** Inspected the Seaborn `taxis` dataset using Pandas, checked for data structures, and created line graphs, histograms, and box plots to see data trends.

### 2. 🫀 [02-Heart-Disease-Logistic-Regression](./02-Heart-Disease-Logistic-Regression)
* **Goal:** Binary classification using clinical measurements.
* **Core Tasks:** Cleaned and evaluated features from the Framingham heart disease dataset and trained a baseline **Logistic Regression** model using Scikit-Learn.

### 3. 🐧 [03-Penguin-Gender-Classification-Decision-Tree](./03-Penguin-Gender-Classification-Decision-Tree)
* **Goal:** Building and tracking rule-based classification models.
* **Core Tasks:** Encoded categorical features (like species and islands) from the `penguins` dataset and trained a **Decision Tree Classifier** to determine penguin sex.

### 4. 💎 [04-Diamond-Carat-Classification-KNN](./04-Diamond-Carat-Classification-KNN)
* **Goal:** Multi-class classification and hyperparameter testing.
* **Core Tasks:** Structured continuous carat values into distinct categorical ranges, trained a **K-Nearest Neighbors (KNN)** model, and ran error-rate tests to find the best $K$ value.

### 5. 💬 [05-Yelp-Reviews-NLP-Naive-Bayes](./05-Yelp-Reviews-NLP-Naive-Bayes)
* **Goal:** Basic Text Classification and Natural Language Processing (NLP).
* **Core Tasks:** Used `CountVectorizer` to convert Yelp review text into numbers, applied a **Multinomial Naïve Bayes** model to check text sentiments, and exported the pipeline using `pickle`.

### 6. 🌐 [06-Diamond-Classifier-Flask-API](./06-Diamond-Classifier-Flask-API)
* **Goal:** Learning model integration via a local web server.
* **Core Tasks:** Built a simple backend using **Flask** that opens local GET and POST endpoints, accepts dynamic JSON payloads, and returns real-time model predictions.

### 7. 🪻 [07-Iris-Data-KMeans-Clustering](./07-Iris-Data-KMeans-Clustering)
* **Goal:** Fundamental Unsupervised Learning and Clustering.
* **Core Tasks:** Ran the WCSS Elbow Method to discover the ideal number of groups ($K=3$) for the Iris dataset and evaluated cluster labels using a confusion matrix.

### 8. 🌿 [08-Hierarchical-Clustering-Dendrogram](./08-Hierarchical-Clustering-Dendrogram)
* **Goal:** Visualizing data hierarchies.
* **Core Tasks:** Built agglomerative linkage matrices using SciPy and created a **Dendrogram** plot to visually analyze similarity clusters.

---

## 🛠️ Tools & Libraries Used
* **Languages:** Python
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, SciPy
* **Visualization:** Matplotlib, Seaborn
* **Model Deployment:** Flask, Pickle
