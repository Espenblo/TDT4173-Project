# Time series forecasting with LSTM

https://colab.research.google.com/github/Espenblo/TDT4173-Project/blob/main/Project_TDT4173.ipynb 

## Dataset

The project fetch data from Yahoo Finance. Each stock has a dataset that is fetched from Yahoo. The data contain date, high, low , open, close and volume.

# How to run the project:
Follow the link on the top, and you will be sent to Google Colab.
The code structured in cells.
Each of the cell has and overhead of what the cell contains. The code is also commented.

- Click on the link in top
- Uncomment/ comment the stock you want to predict.(Import Data From Yahoo and create dataframe for first stock). Notice that there is 4 places that has to be changed! Ctrl + F/ Cmd+F and and search for TODO for easier navigation.
- In the menu-bar there is a section called runtime. click in this and click run all. You will then run the single and combined model.

## How to save model:
### Single
- Go to cell: Save models single models to google drive(optional)
- Change name on the file
- Make sure you save the ID that will be printed out under the cell

### Combined
- Go to cell: Save combined models(optional)
- Change the name on the file
- Make sure you save the ID that will be printed out under the cell

## Files in this repo
The main code are in the link, here you can runn all the code.That is the same as the file TDT4173_project.ipynb
In the file single_model.ipynb is the same code just only for one stock.

