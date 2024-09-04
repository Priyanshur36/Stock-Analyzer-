1) This Python model uses live data of stocks listed in NSE or BSE during market hours. 
2) It incorporates several indicators, moving averages (such as RSI, MACD, 50MA, 100MA, 200MA) and Volume to enhance accuracy. 
3) Currently, the latency rate is approximately 60 stocks per minute.

Install the Equity.csv file into the same directory where your Python is installed

So the code can extract data of NSE from this CSV file


Things to be added more in code:-
1) Currently this code scans particular companies one by one we'll be adding the feature of multithreading soon to it
2) Frontend needed for user interaction 
3) Flask too will be used for HTTP request 
