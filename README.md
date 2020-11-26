# Time series forecasting with LSTM

Main combined colab: https://colab.research.google.com/github/Espenblo/TDT4173-Project/blob/main/Project_TDT4173.ipynb  
Single colab: https://colab.research.google.com/github/Espenblo/TDT4173-Project/blob/main/Single_Model.ipynb
## Dataset

The project fetch data from Yahoo Finance. Each stock has a dataset that is fetched from Yahoo. The data contains the following features: date, high price, low price, open price, close price and volume.

# How to run the project:
Follow the link on the top, and you will be sent to Google Colab. You can either select the "Main combined colab" where you have the ability to train a model  on multiple stocks, or you can select the "Single colab" where you only can train on a single stock.
The code is structured in cells.
Each of the cells has an overhead describing what the cell does. The code is also commented for further elaboration.

- Click on the link in the top
- In the first cell: uncomment/comment the stock you want to predict (it will import data from Yahoo and create a dataframe for the selected stock). Notice that four cells has to be changed - these are the lines determining what stocks to fetch. Each line is marked with a "TODO" comment. Use Ctrl + F/ Cmd+F and search for "TODO" for easier navigation.
- In the menu-bar there is a section called runtime. Click on it and select run all. You will then run the entire colab file.

## How to save a model:

### For the main combined colab
- Go to the cell named: "Save combined models(optional)"
- Change the name on the file to a fitting name for your model
- Make sure you save the ID that will be printed out under the cell. It is needed for when you load the model. You can load models in the last cell named "Load models".

### For the single colab
- Go to the cell named: "Save models single models to google drive(optional)"
- Change the name on the file to a fitting name for your model
- Make sure you save the ID that will be printed out under the cell. It is needed for when you load the model. You can load models in the last cell named "Load models".

## Files in this repo
The colab files are appended to this repo. The "TDT4173_project.ipynb" file corresponds to the "Main combined colab", and the "single_model.ipynb" corresponds to the "Single colab".

