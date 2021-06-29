# Stock-price-prediction
Stacked LSTM's and EDA of different stocks
# About the repo
The EDA.ipynb covers up these topics
- What was the change in price of the stock overtime?
- What was the moving average of the various stocks?
- What was the daily return of the stock on average?
- What was the correlation between different stocks closing prices?

<br/>
The prediction.ipynb covers <br/><br/>

- Implementation of stacked LSTM model
- Preprocessing using MIN-MAX scaler
- plotting the forecasting done by LSTM

# How to get the API key 
- You have to make an accout on [Tiingo](https://www.tiingo.com/)
- After creating click on API section on the left side
- There you will get your API key
- Glimpse of website<br/> ![image](https://user-images.githubusercontent.com/51751926/123874151-4f406580-d955-11eb-877b-12201dcfc840.png)

# Problems you might face
- Error while running the LSTM model - NotImplementedError <br/> ![image](https://user-images.githubusercontent.com/51751926/123874413-c4139f80-d955-11eb-9996-0bf62c36246a.png)
- To solve this just simply degrade the numpy version to 1.9.5
```
pip install numpy==1.9.5
```
- If you still face any issues [click here](https://stackoverflow.com/questions/66207609/notimplementederror-cannot-convert-a-symbolic-tensor-lstm-2-strided-slice0-t/66207610)

# Note 
- Don't use this for investing in stocks :wink:
- Just kidding hope you find something useful 
