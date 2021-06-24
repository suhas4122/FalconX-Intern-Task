# FalconX-Intern-Task
This python notebooks contains code as a part of the task for application for **FalconX Quant Analyst Intern.**   
It has the following tasks:
- Getting data of trades of UNI/WETH pair from Uniswap v2 API.  
- Modifying the data to make Timestamp, Side (Buy or Sell), Base currency quantity traded, Quote currency quantity traded, Volume in USD, Liquidity in pool, Pool ID columns.  
- Making various plots from the data to derive certain conclusions (mentioned in the ipynb file).  

## Dependencies 
Before running the file you should have some dependencies installed.  
To install them run:  
> pip install -r requirements.txt  
## Running the file 
Just open the file and run each cell one by one to see the results.  

**NOTE** : I was only able to extract data of last 1000 trades due to limitations of the API. All the analysis has been done on those 1000 data points.
