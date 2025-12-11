## Artificial Intelligence-Aided Analysis of Hydrogen-Based Monoclinic Structures and Modeling of Structure-Property Relationships 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/AI-Scikit--Learn-orange)
![Materials Project](https://img.shields.io/badge/Data-Materials%20Project%20API-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

# For more istatistanbul.com

An advanced Machine Learning pipeline designed to predict the **Band Gap** energy of hydrogen-based monoclinic crystal structures. This project leverages data from **The Materials Project API** and utilizes machine learning techniques and ensemble learning techniques (best of XGBoost, Gradient Boosting, Linear Regression, Random Forest Resgression, Ridge Regression) to achieve high-accuracy predictions.

##  Key Features
* **Automated Data Mining:** Fetches real-time crystallographic data via MP API.
* **Smart Preprocessing:** Cleans and normalizes material properties for ML readiness.
* **Ensemble Modeling:** Benchmarks 6+ algorithms (Ridge, RF, R2, XGBoost, CatBoost) to find the best predictor.
* **Interactive Agent:** Includes a CLI-based inference engine for real-time predictions.

##  Tech Stack
* **Core:** Python, Pandas, NumPy
* **ML & Data:** Scikit-Learn, XGBoost, CatBoost
* **API:** MP-API (Materials Project)
* **Visualization:** Seaborn, Matplotlib

##  Project Structure
* `1_data_collection.ipynb`: API connection and raw data extraction.
* `2_pre_processing.ipynb`: Data cleaning, feature engineering, and visualization.
* `3_machine_learning_applications.ipynb`: Model training, hyperparameter tuning, and evaluation.
* `4_composition_based_feature_engineering.ipynb`: User interface for making predictions.

##  Usage
1.  Clone the repository.
2.  Install dependencies: `pip install mp-api pandas numpy scikit-learn xgboost catboost` (https://docs.python.org/3/library/index.html)
3.  Run the notebooks in order.
4.  Use the **Inference Agent** to predict properties of new materials.

##  License & Data Usage
* **Code:** Licensed under the MIT License. See [LICENSE](LICENSE) for details.
* **Data:** Material properties are retrieved via the [Materials Project API](https://materialsproject.org/). Usage of this data is subject to Materials Project's terms. Please cite: *A. Jain et al., APL Materials 1, 011002 (2013).*

---
*Developed by Göktuğ Usta for ML Methodes & Sedef Korkmaz for Data Acquisition - Electrical & Electronics Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/goktug-usta)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sedef-korkmaz-11a817252)