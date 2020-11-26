# Time series forecasting with LSTM

https://colab.research.google.com/github/Espenblo/TDT4173-Project/blob/main/Espen.ipynb#scrollTo=Go-10uXwVmf7

##Dataset
The project fetch data from Yahoo Finance. Each stock has a dataset that is fetched from Yahoo. The data contain date, high, low , ope, close and volume.

#How to run the project:
You folow the link on the top, you will be sent to google colab. 
Here are the code structured in cells. 
Each of the cell has and overhead of what the cell contains. The code is also commented.

- click on the link in top
- uncomment/ comment the stock you want tot predict.(Import Data From Yahoo and create dataframe for first stock) 
- in the tabbar there is a section called runtime. click in this and click run all. You will then run the single and combined model.

##How to save model:
Single
- Go to cell: Save models single models to google drive(optinal)
- then change name on the file if you want to save more models
- And make sure you save the ID that will be printed out under the cell

Combined
- go to cell: Save combined models(optional)
- Change the name on the files.
- And make sure you save the ID that will be printed out under the cell