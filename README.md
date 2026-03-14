This project analyzes the relationship between cryptocurrency trader performance and overall market sentiment using the Fear & Greed Index.
By combining historical trading data with market sentiment data, we identify patterns that show how traders behave under different emotional market conditions such as Fear, Greed, and Extreme Fear.
The goal of this analysis is to understand:
How trader profitability changes with market sentiment
Whether traders perform better in fearful markets or greedy markets
Behavioral patterns in trading activity
📂 Project Structure
```
trader-behavior-insights
│
├── data
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
├── analysis.ipynb
│
├── trader_sentiment_analysis.csv
│
└── README.md
```
Datasets Used
1️.Trader Historical Data
Contains detailed information about individual trades executed by crypto traders.
2️.Fear & Greed Index Dataset
Represents overall cryptocurrency market sentiment.

Data Processing Workflow
The analysis follows these steps:
1️. Load both datasets using Pandas
2️. Convert timestamps into standard date format
3️. Extract date from trade timestamps
4️.  Merge trader data with market sentiment data
5️. Perform analysis on Closed PnL grouped by sentiment


Observation
Traders tend to generate higher profits during Extreme Greed market conditions
Neutral and Extreme Fear markets show lower profitability
Market psychology appears to significantly influence trading performance

Technologies Used
Python
Pandas
Jupyter Notebook
Data Analysis

How to Run This Project
1️.Clone the Repository
git clone https://github.com/Sanjana5523/trader-behavior-insights.git
2️.Install Required Libraries
pip install pandas
3️.Open the Notebook
jupyter notebook analysis.ipynb
Run the notebook to reproduce the analysis.
