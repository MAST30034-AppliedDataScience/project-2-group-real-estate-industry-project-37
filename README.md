# Generic Real Estate Consulting Project
Team Members：
1. Haozhou Du (1346881)
2. Xinyue Deng (1321845)
3. Yuzheng Wan (1346511)
4. Peiyan Chen (1317103)
5. Peilin Liu (1342891)

# Research Goal:

Our primary research goal is to answer the following questions:

 1. What are the most important internal and external features in predicting rental prices? 
 2. What are the top 10 suburbs with the highest predicted growth rate?
 3. What are the most liveable and affordable suburbs according to your chosen metrics?
### Setup

**Python 3 dependencies:**
- Pyspark
- Pandas, Numpy
- Seaborn, matplotlib
- Scikit-Learn
- Beautiful Soup
- statsmodels
- Google API Client Library
   
# Step 1 Data processing: 
1. See the `CrawlingDatasets.ipynb` file in the `notebooks` directory to get the information of the scraping data. 
2. See the `DataPreprocessing.ipynb` file in the `notebooks` directory to obtain the datasets after preprocessed.
3. See the `Domain 2024 Data` file in the `data` directory to get the raw data categorised into different regions. 
4. See the `Suburb rental prices data` file in the `data` directory to get the different rental price from each suburb. 

# Step 2 (Q1 External and Internal features):
1. See the `Question 1` file in the `plot` directory to get the correlation graphs for internal and external features.
2. See the `DataCorrelation.ipynb` file in the `notebooks` directory to obtain the outputs of correlation (each feature is outlined in the notebook). 

# Step 3 (Q2 Top 10 suburbs): 
1. See the `Question 2` file in the `plot` directory to get the growth rate graphs for the top 10 suburbs.
2. See the `Suburb growth visualisation.ipynb` file in the `notebooks` directory to get output of graphs for the top 10 suburbs. 
3. See the `Historical rental growth` file in the `notebooks` directory to obtain historical growth rates from each region and suburb. 
4. See the `Time series rental price` file in the `notebooks` directory to obtain future predictive growth rates from each region and suburb. 

# Step 4 (Q3 Livable and affordable):
1. See the `Question 3` file in the `plot` directory to scatter plots and model evaluation results graphs.
2. See the `question3 modified.ipynb` file in the `models` directory to livable and afforadable index outputs and model training results.
