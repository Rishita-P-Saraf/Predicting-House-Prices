# 🏠 Predicting House Prices using Linear Regression and KNN Regressor

This project aims to predict house prices using two supervised machine learning algorithms: **Linear Regression** and **K-Nearest Neighbors (KNN) Regressor**. The models are trained on structured house pricing data, and evaluated based on performance metrics. The workflow includes data preprocessing, visualization, model training, evaluation, and saving the best model.

---

## 📌 Objectives

- Understand key factors affecting house prices.
- Perform data preprocessing and outlier detection.
- Train two regression models: Linear Regression and KNN Regressor.
- Visualize insights using boxplots.
- Save the trained model for reuse.

---
## Dataset
The California Housing dataset contains:

8 numerical features describing different aspects of California districts, such as:

- MedInc - Median income in the district

- HouseAge - Average age of houses in the district

- AveRooms - Average number of rooms per household

- AveBedrms - Average number of bedrooms per household

- Population - Population of the district

- AveOccup - Average number of people per household

- Latitude - Latitude of the district

- Longitude - Longitude of the district

- A target variable (MedHouseVal) representing the median house value in $100,000s.
---
## 🧠 Machine Learning Models

- **Linear Regression**  
  A basic regression technique used for predicting continuous variables.

- **K-Nearest Neighbors Regressor (KNN)**  
  A non-parametric model that predicts values based on the average of its nearest neighbors.

---

## 📁 Project Structure

```plaintext
Predicting House Prices - Linear Regression and KNN Regressor/
│
├── Predicting house prices -Linear Regression.ipynb      # Linear Regression notebook
├── Predicting house prices - KNN Regressor.ipynb         # KNN Regressor notebook
├── model.pkl                                             # Saved regression model
├── BoxPlot.png                                           # General boxplot visualization
├── BoxPlot_TrainData.png                                 # Boxplot for training data
├── BoxPlot_TestData.png                                  # Boxplot for testing data
├── .ipynb_checkpoints/                                   # Jupyter notebook backups
```
---
## 📊 Visualizations
- BoxPlot.png: Outlier detection across the full dataset.
- BoxPlot_TrainData.png: Outliers in the training subset.
- BoxPlot_TestData.png: Outliers in the testing subset.

---

## 🧪 Evaluation Metrics
Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

These metrics help compare the performance of the models and determine the best fit.
---
## 💾 Model Deployment
Trained models are saved as .pkl files using joblib, allowing reuse without retraining.
---
## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.
---
## 🙌 Acknowledgments
- Project developed for learning purposes using open datasets.
- Libraries used: scikit-learn, pandas, numpy, matplotlib, seaborn.

---
## 🚀 Author
Your Name Here
Feel free to connect with me on GitHub or LinkedIn.


Let me know if you'd like me to create a matching `LICENSE` file or help format the notebooks as well!
