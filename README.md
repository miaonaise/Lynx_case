# Lynx Case
Assignment for Junior quantative analyst position at Lynx 

## How to run the code
The code is written in Google Colab, so the fail proof way is to download the repository and upload it into your local Google Drive. Don't forget to update the current working directory in Section 0: Intial stuff in that case. 

Otherwise, jupyter notebook is recommended for running the code. Remove the setting up Google Drive part, and install the packages that you need. 

Obs! Don't run the whole thing at once. It will guarantee fail somewhere because some cells are incomplete and unused. 

## How to read the code
There are three notebooks:
- Spiff.ipynb: the main notebook divided into 3 main sections
  - 0: Initial stuff
  - 1: Time Series Analysis
    - 1.1 [Distribution plots, Time Series Plots, Q-Q plots] : [logReturn, smoothed logReturn, scaled logReturn]
    - 1.2 Volatility
    - 1.3 Correlation Matrix
    - 1.4 ACF and PACF of the time series
    - 1.5 Clustering
  - 2: Interpolation
    - 2.1 (Abandoned) Bad Interpolation
    - 2.2 Good Interpolation
  - 3: Trading Strategy 
- functions.ipynb: module with supporting analysis functions
- plotting.ipynb: module with supporting plotting functions

P.S. Run section 0 and 1.1 for every other section to work, the rest are arbitrary. 

## Updates
To get the most up to date version of the code, you can directly access the code with this link:
