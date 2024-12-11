Meta Stock Analysis 
Overview
This project focuses on analyzing the stock performance of META (formerly Facebook) to uncover insights about its market behavior, assess its risk-return profile, and predict future stock prices. With META's pivotal transition to a metaverse-focused company and its significant impact on investor sentiment, this analysis delves into how external events and market conditions shape stock performance. By leveraging data analytics, machine learning, and advanced financial metrics, the project aims to provide actionable insights for investors and a framework for evaluating stock data efficiently. The integration of data storage techniques ensures scalability and reproducibility, making the project versatile for financial data management and analysis.

Problem Statement
The financial market is highly dynamic, with stock performance influenced by a mix of external factors, market conditions, and historical trends. META’s rebranding announcement on October 28, 2021, serves as a case study for understanding how major events affect stock prices and trading activity. While historical data provides valuable context, it is challenging to quantify the risks and returns associated with specific market conditions (e.g., bull and bear markets) or predict future stock prices with high accuracy. Existing predictive models often lack integration with data management systems, limiting their practical application. This project addresses these gaps by combining stock data analysis, predictive modeling, and database integration to derive comprehensive insights and improve the accessibility of financial data.

Objectives
Event-Based Analysis: Investigate the impact of META's name change announcement by analyzing stock performance and trading volume around the event.
Risk-Return Analysis: Assess annualized return and risk (standard deviation) for META stock during the overall period, bull markets, and bear markets, providing insights into the risk-return trade-off under varying market conditions.
Predictive Modeling: Develop and evaluate a predictive model using lagged stock price features to forecast future closing prices with high accuracy.
Data Integration: Store stock data in an SQLite database for efficient querying and ensure reproducibility of analysis through structured data management.

Dataset
The dataset for this project, "META.csv," contains historical stock data for META from 2018 to 2024. Key features include:
Date: The trading day.
Open, High, Low, Close, Adj Close: Stock price data capturing the range of prices during the trading session and adjusted for splits or dividends.
Volume: The number of shares traded during the session.

Project Structure
META.csv: Input data file
jrp_329(1).ipynb: Main Jupyter Notebook for data loading, preprocessing, modeling, and evaluation
README.md: Project documentation (this file)
Setup Instructions
1. Running the Notebook on Codebench
Log in to Codebench and navigate to the Jupyter Notebook interface.
Upload the following files to your workspace:
jrp_329(1).ipynb
META.csv
Open final_project.ipynb in the Jupyter Notebook interface.
2. Installing Required Libraries
All necessary libraries are included in the notebook's import statements. If any dependencies are missing, install them directly in a Jupyter Notebook cell using pip commands. Use the following command to install required dependencies:

!pip install pandas numpy scikit-learn matplotlib seaborn psycopg2-binary
3. Running the Notebook
Execute the cells in final_project.ipynb step-by-step:
Run final_project.ipynb to:

Load and preprocess the dataset
Perform exploratory data analysis (EDA)
Train classification and regression models
Evaluate model performance and visualize results


