# Inside-AirBNB-Dataset

Notebook reference: Sentiments_Network_Forecast.ipynb consists of Sentiment Analysis, Network Analysis and Time Series Forecast. 

Scope of Work:

Use Air BnB dataset to explore customer sentiments based on reviews, and assess business success via network analysis. Then, apply time series forecasting to estimate average price and availability of Air BnB rentals in Seattle, New York and San Francisco area. 

Notebook Workflow: 

This combined notebook contains 3 sub-sections:
1.	Part A- Customer Sentiment Analysis
2.	Part B- Network Analysis
3.	Part C- Time Series Forecasting

To run the entire notebook, please download the data from the link below, or directly from the notebook (beginning of each sub-section) and check the system requirements to download dependencies, to see the results you would like to explore. 

Dataset & System Requirements:

•	Public Source: [Inside Air BnB](http://insideairbnb.com/get-the-data.html)

•	To run the notebook, please refer to google drive links below:

  i. 	[Part A and Part B](https://drive.google.com/drive/u/2/folders/1D5s0HkqLNU3fCHMxfM132sB5qbDyMZuQ)
  
  ii.	[Part C](https://drive.google.com/drive/u/2/folders/1A-t_QZN-S3QrUiv5M7rFEGi9xhpW4Nx3) (uses output from Part A and Part B stored in pickle file format) 
  
•	System Requirements: [requirement.txt](https://drive.google.com/file/d/1rItfLCTA5942t_YIjbAnCwec8yQPnGbz/view)

Example from the Notebook: 

For instance, in Part B- Network Analysis, you can pass input parameters to Python function build_network() as specified in the notebook to plot network graphs between the neighborhoods and listing brokers. Using the same function, you will also be able to build network graphs on price, availability, customer sentiments to gain insights. Furthermore, if you would like to filter out popular and unpopular nodes by centrality measures, you can use another function plot_centrality_measure() by specifying network graph you would like to explore. 
Throughout the notebook, you will see markdown prompts to help you navigate through each function as well as provide you a summary of each sub-section titled as “observations” for your quick review. 
Also, to keep track of run time progress of functions and plots, we have used ‘tqdm’ and ‘%%time’ for your reference. 

Potential Scope of Future Study includes: 

1. Use predictions from regression model as an input to build a time series forecast. Evaluate, if it further optimizes results by incorporating feature importance from regression model in time series results, and by how much? 
2. Run statistical analysis to test if Air BnB's incentive programs (customer discounts, service improvements, referral incentives) will result in increased revenue potential for the business, and by how much over the next year?

If you have any questions, please feel free to contact us.  
