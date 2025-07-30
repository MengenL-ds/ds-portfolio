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

- Predicting and Optimizing Pricing Strategies for New York AirBnB Rental Properties
Developed a workflow to predict and optimize pricing strategies for New York AirBnb rental properties using differnt machine learning models. It provides optimal selling price for new listings in the best interest of rental owners.

- Unsupervised Learning

Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn, SHAP, lightgbm.

### Time-Series Forecasting

- Forecasting Avocado Prices and Sales Trends in US Markets
Analyzed historical avocado sales data from multiple US markets to identify key trends and patterns. Applied time-series forecasting techniques to predict future prices and sales volumes, providing actionable insights for avocado producers, retailers, customers.

_Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib_

### Recommender Systems

- Competition by H&M to develop product recommendation based on data from previous transactions, as well as from customer and product meta data.

_Libraries used: Scikit-learn, Pandas, Numpy, Matplotlib, Seaborn_

### Mini Projects

- 

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
