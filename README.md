# 📈 Gold Price Prediction using LSTM
![Gold Price Prediction](image.jpg)

## 🌐 Overview
Gold is a volatile asset, and its price prediction remains crucial for various financial strategies and investments. This project embarks on harnessing the power of LSTM (Long Short Term Memory) to predict gold prices. We utilize daily gold price data from January 2013 to December 2022. Training our model on the data spanning from the beginning of 2013 to the end of 2021, we then venture to predict prices for the year 2022. Accompanied by enlightening visualizations and analytical insights, we achieve an impressive accuracy using the Root Mean Squared Error (RMSE) as an evaluation metric.

## 🎯 Objectives
- **Exploring and Preprocessing Data**: Analyzing the data and readying it for training and testing phases.
- **Model Building**: Employing LSTM (Long Short Term Memory) to predict the gold price.
- **Prediction and Analysis**: Forecasting gold prices for the year 2022 and analyzing the model's performance.

## 📊 Dataset
This dataset offers a detailed look into gold price trends from 2013 to 2022. Each row pertains to a specific date, and they're all organized in chronological order.

<div align="center">
<table style="width:100%">
<thead>
<tr>
<th style="text-align:center; font-weight: bold; font-size:20px">Variable Name</th>
<th style="text-align:center; font-weight: bold; font-size:20px">Description</th>
</tr>
</thead>
<tbody>
<tr><td><b><center>Date</center></b></td><td>The specific date for the gold price record</td></tr>
<tr><td><b><center>Price</center></b></td><td>The closing price of gold for the specific day in dollars (Target variable)</td></tr>
<tr><td><b><center>Open</center></b></td><td>The price of gold at market opening for the specified date in dollars</td></tr>
<tr><td><b><center>High</center></b></td><td>The highest price of gold recorded on that specific day in dollars</td></tr>
<tr><td><b><center>Low</center></b></td><td>The lowest price of gold recorded on that specific day in dollars</td></tr>
<tr><td><b><center>Vol.</center></b></td><td>The volume of gold traded on that specific day</td></tr>
<tr><td><b><center>Change %</center></b></td><td>The percentage change in the gold price compared to the previous day</td></tr>
</tbody>
</table>
</div>

Access the dataset on Kaggle [here](https://www.kaggle.com/datasets/farzadnekouei/gold-price-10-years-20132023).

## 📁 File Descriptions
- 📓 **`Gold_Price_Prediction_LSTM.ipynb`**: Jupyter notebook containing all stages of data exploration, preprocessing, modeling, prediction, and analysis.
- 📄 **`Gold_Price_2013-2023.csv`**: CSV file containing the entire dataset.

## 🚀 How to Execute
1. Clone this repository to your local machine.
2. Launch the `Gold_Price_Prediction_LSTM.ipynb` notebook in Jupyter.
3. Execute all cells in the notebook.

## 🔗 Additional Resources
- **Kaggle Notebook**: Interested in a Kaggle environment? Check out the notebook [here](https://www.kaggle.com/code/farzadnekouei/gold-price-prediction-lstm-96-accuracy).
- **LinkedIn**: [Farzad Nekouei's Profile](https://www.linkedin.com/in/farzad-nekouei-7535aa53/)

