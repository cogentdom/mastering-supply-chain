# Simplifying supply chains 

### Forecast and Demand Planning
- Lead time  
- Bull wip
- Price discretion
- Shelf Life
- Estimate revenue/expenses
- Sales effects Per sku cause by shortages
- Promotion Planning
- Target weeks stock
- Ship History
- Build material - tolling
- Vendor managed inventory


### Inventory Optimization
- Inference Product Relationships
- Identify items frequently purchased together 
  - When doing a sale on one item what other items are likely to be purchased
  - How should shelves be arranged in accordance to these joint occurrences
  - How will a shortage/surplus affect net sales
- Items effected from missing input materials of related good
- Find true hierarchical nodes (item categories)
- Leverage data generation
- Replenishment and Distribution
- Manufacturing and Capacity
- 

### Lokad SC
- Equispace time series
- Vendor managed inventor
- Stochastic gradient decent + Automatic Differentiation = Differential Programming
- If mis-predict demand must be prepared to liquidate unsold items
- DL solves curse of dimensionality
- DL uses surrogate functions: cross entropy over MSE
- 

### Addressing complexity in data
- Stationarity
- Standardize
- Normalize
- Seasonality
- Trend
- Non linear
- Auto/Serial correlation
- Auto Regressive
- Decomposition
- Dynamic Time Warpping
- Stochastic
- Multi Target
- Multi Horizon
- Multi Variate
- Multiple Time Series
- External Time Series
- Heterogeneity
- Hierarchical / Panel / Tabular
- Aggregation / Disaggregation of Nodes
- Predictions at various aggregation levels
- Prediction with various price bands
- Prediction Intervals
- Interpretable Multi-head Attention
- Multi-head Attention includes seasonality analysis
- Multi-head Attention includes calculation of "persistent temporal patterns"
- Temporal/Sequential + time invariant features
- Inflating dimensionality leads to more trivial solution for gradient decent
- Scaling from monthly aggregates to daily aggregates increases dimensionality but not complexity
- Even deterministic problems have been solved using excludively stochastic or statistical methods
  - Better to be approximately correct than completely wrong


# Models
- ARIMA - SARIMAX
- VAR model - co-integration (VARIMA)
- Random Forest
- RNN
- LSTM
- Bidirectional LSTM
- CNN-LSTM
- ConvLSTM
- TCN & TFT

# Libraries
- numpy
- pandas
- matplotlib
- seaborn
- statsmodels
- sci-kit learn
- tensorflow
- pytorch

# Infrastructure
- Sagemaker
  - AWS (EC2, VPC, Jupyter server)
- Jupyter Notebook
- Jupyter Book
- Github
-

# Notes
- Transfer Learning
- Stream Learning
- Weighted Linear Regression
- Radial Basis Function
- Can rolling mean/std be inverse transformed
- Exponential Smoothing (Holt Winters)
- Batch size, sequence length, embedding dimension
- RNN: vanishing gradient problem
- EDA
  - Extract important values
  - Identify outliers, missing values, human error
  - Understand relationships:
    - Correlation:   num v num
    - Chi^2:         cat v cat
    - ANOVA(t-test): num v cat
    - Outliers:      z-score(+-3)
- Statistical Analysis:
  - Identify distributions (mean, std)
  - hypothsis testing (support belief)
  - identify relationships
- Psychometric Principles & Theory
  - reliability
  - validity
  - standardisation
  - freedom from bias
- Tabular Data: what is it and why bad for DL
- The Great Supply Chain Disruption
- 

# Learnings
- Sparse -> Trivial for DL
- 
