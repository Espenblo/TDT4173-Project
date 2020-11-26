# Time series forecasting with LSTM

https://colab.research.google.com/github/Espenblo/TDT4173-Project/blob/main/Project_TDT4173.ipynb

## Dataset
The project fetch data from Yahoo Finance. Each stock has a dataset that is fetched from Yahoo. The data contain date, high, low, open, close and volume.

# How to run the project:
You follow the link on the top, you will be sent to Google Colab. 
The code is structured in cells. 
Each of the cells has and overhead with what the cell contains. The code is also commented.

- Click on the link in top
- Uncomment/comment the stock you want to predict(Import Data From Yahoo and create dataframe for first stock). Notice that there is 4 places that has to be changed! Ctrl + F and and search for TODO for easier navigation.
- In the tabbar there is a section called Runtime. Click this and select "Run all". You will then run the single and combined model.

## How to save model:
Single
- Go to cell: Save models single models to google drive(optinal)
- Change name on the file
- Make sure you save the ID, it will be printed out under the cell

Combined
- Go to cell: Save combined models(optional)
- Change name on the file
- Make sure you save the ID, it will be printed out under the cell
