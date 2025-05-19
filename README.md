# Jobs-loss-prediction-and-Revenue-increase-forecasting-using-Arima
Job_loss % Due to Ai:

Data collection:
Data collected from kaggle.Dataset contains percentage value (%)of the AI_adoption rate,Job loss,Human-Ai collabration,Revenue
increase,Market share,Customer_trust,category of Country,Industry,Regulation_status,TOP-AI tools and Year.

Data Handle:
Pandas libarary to read the dataset,checking null values,describe to statistical report (Mean,Standard Deviation,Max,min,etc...)for each numerical value columns.

Data encoding:
Use pandas dummies to encoding the categorical columns like "Country","Industry","Regulation status","Ai tools".

Data split:
Data Features(All others) and Taget(job_loss %)

Algorithm:
Linear Regression and Random Forest Regression

Model save:
Model saved in pickel file for future prediction.

Result:
Random Forest had less R2 score (~ -1.17) and Mean square(~230) Error work well in this job_loss prediction. 

Power BI interactive deshboard for visual insights:
![ai_impact](https://github.com/user-attachments/assets/1adf1226-a0bd-4ebe-93e8-51c145fb8d5e)
[Autoregressive Integrated Moving Average]:

Industry revenue forecasting using Arima:
Stastsmodel of Arime for Revenue forecasting

Data:
same data to slicing year and Revenue columns.

Forecast:
ARIMA model to forecast for Revenue Increase% over the future years.
Arima work well on the more datapoints.
![revenue_forecast](https://github.com/user-attachments/assets/3332aa34-d9bb-416f-81f6-3104aa21d0f4)




