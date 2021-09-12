
# Retail-Chain-Analytics

<b> Analyzing data about a retail chain to predict weekly sales for the retail chain based on details of the sales orders </b>

# Data and Content

<br><b>Data can be downloaded from here: https://www.kaggle.com/manjeetsingh/retaildataset </b></br>
<b><br>1: Historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas.</b></br>
<b><br>2: File contains 3 files 1: Store Details, Sales Details and Features(data related more to stores and sales etc)</br>

### Task

<br><b>1: Combine each different of sales,stores and features into one whole data </b></br>
<br><b>2: Performed data cleaning by handling missing values, categorical features </b></br>
<br><b>3: Exploratory Data Analysis to understand data and each features by plotting visualizations like various plots </b></br>
<br><b>4: Decomposition of Time Series (Stationary and Non Stationary) using KPSS and ADF test </br></b>
<br><b>5: Performed baseline models like Moving Average, Weighted Moving AVerage, Exponential Moving Average and Exponential Smoothing and evaluated the results using metric</br></b>
<br><b>6: Performed ARIMA time series model to predict monthly sales for retail chain and evaluated its diagnostics </b></br>
<br><b>7: Performed LSTM Time series model to predict weekly sales for retail chain and evaluated the model </b></br>
<br><b>8: Built Random Forest and XgBoost Regressor Models with HyperParameter Tuning </br></b>

### Few Snapshots of the Analysis done

<br> ![image](https://user-images.githubusercontent.com/55294349/132814156-138c8e2a-a876-4ef2-80c9-42173b138ce9.png) </br>
<br><b> Sales in last few weeks are very high due to Christmas, Thanks Giving, New Year for year 2010, 2011 but not high for year 2012</br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814219-94965b59-34b9-40a8-b644-cd3d7b0fba87.png) </br>
<br><b> Stores 2,4,6,13,1420,27 and 28 have very high sales.Stores 3,5,33 and 44 have very low sales </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814691-c050a23c-f296-407b-8390-5dc49abae8bb.png)</br>
<br><b> Fuel price increases as the temperature increases when There is NO HOLIDAY.Fuel Price increases unevenly when there is HOLIDAY as temperature increases </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814756-7e3d98e2-0cc6-4bfb-bbaf-3f8facc56632.png)</br>
<br><b> As temperature increases Consumer Price Index also increases and lastly decreases for all 3 Type of stores </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814791-ca57865a-8a4d-48fd-986f-b889fb55f781.png)</br>
<br><b> Type A has most sales while Type C has less sales.Sales are high during summers </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814859-416214ad-579f-4044-b6fd-76c7031d00df.png)</br>
<br><b> It is evident that when there is Holiday the fuel prices are low.Type B fuel prices are high while Type A prices are low among all </br></b>

<br>![image](https://user-images.githubusercontent.com/55294349/132814910-3e7c32df-e5a3-474b-82e6-0dda12bce878.png)</br>
<br><b> For the year 2010 Fuel Price was low. Year 2011 the prices was very high spike with decreasing in between. For month of November and December 2012 the prices were very high compared to prices from previous years for same months.</br></b>
