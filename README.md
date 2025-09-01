# Data Science Portfolio

A collection of data science projects developed through academic coursework, self-directed learning, and personal exploration. Content is presented in various formats, including Jupyter notebooks (.ipynb), R scripts (.R), and R Markdown files (.Rmd).

## How to Run Jupyter Notebooks Locally

**Before you begin:**  
Please familiarize yourself with [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) and how to install it on your system.  
It's also helpful to understand, [here](https://medium.com/@pinareceaktan/what-is-this-virtual-environments-in-python-and-why-anyone-ever-needs-them-7e3e682f9d2) is a fun article to help you get familiarized.

### 1. Create the Conda Environment and Install Dependencies

Use the provided [environment.yml](./environment.yml) to create the environment. Replace `<env name here>` with your desired environment name:

```bash
conda env create -f environment.yml --name <env name here>
```

*Note: If the link to the environment file is not functional, please find it in the root of the repository, download it, and install it manually.*

### 2. Activate the Conda Environment

```bash
conda activate <env name here>
```

### 3. Clone This Repository

Clone the repository to your desired location using:

```bash
git clone <repository-url>
```

### 4. Run the Notebooks

Navigate to the cloned directory in your terminal.

- You can run notebooks using **VS Code**, **Google Colab**, or
- Start **Jupyter Lab** locally by typing:

```bash
jupyter lab
```

Then select the "Python 3" kernel and run the notebook.

## Contents

### Machine Learning

- Predicting and Optimizing Pricing Strategies for Bristol, UK Airbnb Rentals
Developed a machine learning workflow to predict and optimize rental prices for Bristol Airbnb listings. Built and compared multiple models (Linear Regression, Random Forest, Gradient Boosting, LightGBM) to recommend optimal pricing strategies for new listings, supporting hosts in maximizing revenue. Applied feature importance analysis with SHAP and exploratory data visualization to extract actionable market insights. Developed a Flask-based web app that allows users to input listing details and receive real-time price recommendations. The app wraps a fully reproducible pipeline with preprocessing, a trained model (final_model.pkl), and a saved preprocessing transformer (preprocessing_pipeline.pkl) to ensure consistent predictions. An example payload (payload.json) helps users test the API easily.

Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn, SHAP, lightgbm, Flask.

- Maternal Health Risk Prediction
Built a full reproducible pipeline in R to classify maternal health risk levels (low, medium, high) using physiological data such as blood pressure, blood sugar, and body temperature. Implemented Random Forest and multinomial logistic regression models, with Random Forest achieving 81% accuracy (vs. 58% logistic regression and 40% baseline). Deployed a Dockerized environment with Makefile automation to ensure reproducibility and transparency. Key predictors identified included body temperature (2.29× odds of high risk per unit increase) and blood sugar (2.13× odds)

_Libraries/Tools: R, Random Forest, Docker, Makefile, RStudio, ggplot2, ggcorrplot, vip,..._

### Time-Series Forecasting

- Forecasting Restaurant Visitor Demand with Machine Learning and Statistical Models
Developed time-series forecasting models to predict daily restaurant visitor demand using historical reservation and weather data. Implemented ARIMA/SARIMAX models alongside machine learning methods (Random Forest, Gradient Boosting) and compared their performance. Applied feature engineering on temporal and external variables to improve accuracy and validated results with time-series cross-validation to avoid data leakage.

_Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib, statsmodels (ARIMA, SARIMAX)_

### Mini Projects

- Recipe Name Clustering
This project explores unsupervised learning by clustering recipe names from Kaggle’s Food.com dataset. The dataset contains over 180K recipes and 700K reviews. We focus only on the recipes (RAW_recipes.csv) and cluster them based on their textual descriptions

_ Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib, Umap-learn, word_cloud, yellowbrick_

## Software Engineering Projects

- Aircraft Maintenance Tracking Log

Developed a program for the RAF or airforces around the world to track several aircraft operations from maintenance to crew and mission assignments.

- Restaurant Point of Sale (POS)

An intuitive POS system for a local restaurant business to optimize their day-to-day operations from ordering food to table assignment. 

_Currently in use, deployed locally on restaurant's system (PC)_

- Dining Course Management System

A system that allows improved coordination of priority food and drink orders between the different stations in the kitchen, bar and the waiters.

_Currently in use, deployed locally on restaurant's system (Android & PC)_

---

Thank you for taking your time to visit my portfolio, if you would like to have a chat about my work, or work opportunities, please don't hesitate to reach out to me at my [Email](mailto:mengen.liu.ds@gmail.com)

If you liked what you saw, want to have a chat with me about the portfolio, work opportunities, or collaboration, shoot an email at mengen.liu.ds@gmail.com.
