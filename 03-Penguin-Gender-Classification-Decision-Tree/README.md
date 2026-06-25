# Project 3: Penguin Gender Classification using Decision Trees

## Overview
This project implements a supervised machine learning workflow to predict the sex (male or female) of penguins based on physical culmen (bill) and flipper measurements from the Seaborn `penguins` dataset. The core objective is to handle multi-feature biological data and optimize a non-parametric classification algorithm.

## Key Features & Implementations
* **Data Encoding & Preprocessing:** Executed target and categorical feature mapping (transforming species like Adelie, Chinstrap, Gentoo, and islands into distinct numerical indices) using inplace dataframe replacements to prepare data for model compatibility.
* **Supervised Learning Pipeline:** Implemented and structured a **Decision Tree Classifier** to handle categorical and continuous biological measurements without dropping structural dataset components.
* **Performance Diagnostics:** Formulated classification evaluations to assess model accuracy and discrete prediction performance.

## Technologies Used
* **Language:** Python
* **Libraries:** Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib
* **Dataset:** Palmer Penguins Dataset
