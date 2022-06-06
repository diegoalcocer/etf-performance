# Fintech | ETF Performance Analysis

An exchange-traded fund (**ETF**) is a type of pooled investment security which means that you invest in a basket of assets. You don’t spend time researching individual stocks or companies or take the risk of investing in a single stock. ETFs offer more diversification.

In this project, I built a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a fintech **ETF**.

Using SQL statements I will access, filter and order the data from the database, to later transform it into dataframes. These dataframes will be used to calculate values such as the **annualized returns** for the portfolio. 

---

## Technologies

This analysis is implemented on the web-based interactive computer platform [Jupyter Notebook](https://jupyter.org/)

📚 This project uses the following libraries to analyze and plot the data:

* Pandas
* Pathlib
* matplotlib
* NumPy
* Python
* SQL (Sqlite)
* Voila

---

## Usage

Clone the project from this repository to start using it.

📂 For this project, I will be analyzing a fintech ETF that consists of four stocks:
* GOST
* GS
* PYPL
* SQ 

Each stock has its own table in the **etf.db** database

📅 The data is in the date range: **2016-12-16** to **2020-12-04**

📚 This project uses the Voilà library to deploy the Jupyter notebook as a web application. 

Here is an example of how the application looks like when deployed using the **Voilà** library:

![](voila.gif)