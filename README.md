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
- Pyspark
- Pandas, Numpy
- Seaborn, matplotlib
- Scikit-Learn
- Beautiful Soup
- statsmodels
- Google API Client Library
   
### Project Workflow

#### Step 1: Data Processing
- **Crawling Data**: Refer to `CrawlingDatasets.ipynb` in the `notebooks` directory for information on data scraping.
- **Preprocessing Data**: Check `DataPreprocessing.ipynb` in the `notebooks` directory for preprocessed datasets.
- **Raw Data**: See the `Domain 2024 Data` file in the `data` directory for raw data categorized by different regions.
- **Suburb Rental Prices**: Access the `Suburb rental prices data` file in the `data` directory for rental prices from each suburb.

#### Step 2: Identifying Internal and External Features (Q1)
- **Correlation Graphs**: View the `Question 1` file in the `plot` directory for correlation graphs of internal and external features.
- **Data Correlation Output**: Check `DataCorrelation.ipynb` in the `notebooks` directory for the correlation outputs, outlining each feature.

#### Step 3: Top 10 Suburbs with Highest Growth Rate (Q2)
- **Growth Rate Graphs**: See the `Question 2` file in the `plot` directory for growth rate graphs of the top 10 suburbs.
- **Graph Output**: Refer to `Suburb growth visualisation.ipynb` in the `notebooks` directory for graphical outputs of the top 10 suburbs.
- **Historical Growth Rates**: Find detailed historical growth rates in the `Historical rental growth` file in the `notebooks` directory.
- **Future Predictive Growth**: Access the `Time series rental price` file in the `notebooks` directory for future predictive growth rates.

#### Step 4: Identifying Liveable and Affordable Suburbs (Q3)
- **Scatter Plots and Model Evaluation**: Check the `Question 3` file in the `plot` directory for scatter plots and model evaluation result graphs.
- **Livable and Affordable Index Outputs**: Refer to `question3 modified.ipynb` in the `models` directory for index outputs and model training results.

### Conclusion and Acknowledgements

Through this project, we conducted a preliminary analysis of the key factors influencing rental prices in Victoria, predicted future growth potential, and evaluated livability and affordability. Our research provides some initial insights into the real estate market in Victoria, assisting stakeholders in making more informed decisions.

However, we also acknowledge certain limitations in this project, such as the time span of the data and the completeness of the data sources, which may affect the accuracy of the results. In future research, we plan to improve data acquisition and processing methods to enhance the depth and reliability of our analysis.

Lastly, we appreciate the support and guidance provided by our tutor throughout the project.
