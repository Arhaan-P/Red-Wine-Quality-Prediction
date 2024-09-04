# Red Wine Quality Dataset Analysis

## Overview

This repository contains a dataset that captures various physicochemical properties and quality ratings for red wine samples. The dataset includes features such as fixed acidity, volatile acidity, citric acid, and more, which can be used to predict the quality of the wine. The wine quality is rated on a scale from 0 to 10, and each column in the dataset represents a different aspect of the wine's composition or its assessed quality.

## Dataset Description

The dataset consists of the following columns:

1. **Fixed Acidity (`fixed acidity`)**
   - **Description**: Non-volatile acids that do not evaporate easily.
   - **Units**: grams per liter (g/L)

2. **Volatile Acidity (`volatile acidity`)**
   - **Description**: Volatile acids that can evaporate and contribute to the wine's aroma and taste.
   - **Units**: grams per liter (g/L)

3. **Citric Acid (`citric acid`)**
   - **Description**: A weak organic acid that adds freshness and flavor to the wine.
   - **Units**: grams per liter (g/L)

4. **Residual Sugar (`residual sugar`)**
   - **Description**: The amount of sugar remaining after fermentation stops.
   - **Units**: grams per liter (g/L)

5. **Chlorides (`chlorides`)**
   - **Description**: Represents the amount of salt in the wine.
   - **Units**: grams per liter (g/L)

6. **Free Sulfur Dioxide (`free sulfur dioxide`)**
   - **Description**: The amount of SO₂ that is not bound and is available to act as an antimicrobial and antioxidant.
   - **Units**: milligrams per liter (mg/L)

7. **Total Sulfur Dioxide (`total sulfur dioxide`)**
   - **Description**: Includes both bound and free forms of SO₂.
   - **Units**: milligrams per liter (mg/L)

8. **Density (`density`)**
   - **Description**: Mass per unit volume of the wine, influenced by the amount of sugar and alcohol.
   - **Units**: grams per cubic centimeter (g/cm³)

9. **pH (`pH`)**
   - **Description**: Measures the acidity or alkalinity of the wine. Lower pH values indicate higher acidity.
   - **Units**: pH scale (dimensionless)

10. **Sulphates (`sulphates`)**
    - **Description**: Added to wine to prevent spoilage and oxidation.
    - **Units**: grams per liter (g/L)

11. **Alcohol (`alcohol`)**
    - **Description**: The alcohol content of the wine.
    - **Units**: percentage by volume (% vol)

12. **Quality (`quality`)**
    - **Description**: The quality score of the wine, typically based on sensory data (taste, aroma, etc.).
    - **Units**: score (integer scale from 0 to 10)

## Analysis Questions

This dataset can be analyzed to answer the following questions:

1. **Wine Quality Distribution**
   - What is the most frequently occurring wine quality?
   - What are the highest and lowest values in the quality column?

2. **Correlation Analysis**
   - How is `fixed acidity` correlated with the quality of the wine?
   - How does alcohol content affect wine quality?
   - What is the correlation between `free sulfur dioxide` content and wine quality?

3. **Average Residual Sugar**
   - What is the average `residual sugar` for the best quality wine and the lowest quality wine in the dataset?

4. **Effect of Volatile Acidity**
   - Does `volatile acidity` affect the quality of the wine samples in the dataset?

5. **Model Training and Evaluation**
   - Train a Decision Tree model and a Random Forest model separately to predict the quality of the wine samples.
   - Compare the accuracy scores of both models.

## Usage

To explore and analyze the dataset:

1. **Exploratory Data Analysis (EDA)**: Perform EDA to understand the distribution of each feature and their relationships with wine quality.
2. **Correlation Analysis**: Use correlation metrics to investigate relationships between different physicochemical properties and wine quality.
3. **Model Training**: Train Decision Tree and Random Forest models on the dataset and evaluate their performance.

## Conclusion

This dataset provides a rich set of features for predicting the quality of red wine. By performing thorough data analysis and training predictive models, you can gain insights into the factors that contribute to high-quality wine.

## License

This project is licensed under the MIT License.

---

Feel free to contribute to this repository by adding more analyses, improving the models, or enhancing the documentation.
