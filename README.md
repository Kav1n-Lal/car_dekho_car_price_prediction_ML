# car_dekho_car_price_prediction_ML
- I have uploaded the ORIGINAL datasets, which is in a COMPLEX UNSTRUCTURED json_string format not suitable for ML.
- Also the IPYNB notebooks in which I used various data manipulation and transformation techniques to build a more STRUCTURED and CLEANED datasets suitable for ML.
- I have uploaded the ipynb notebooks today(13/2/2024) where I have built the ML models for five cities-**bangalore_ML_23features.ipynb**, **chennai_ML_23features.ipynb**, **hyderabad_ML_23features.ipynb**, **jaipur_ML_23features.ipynb**, **kolkata_ML_23features.ipynb**.Got good results!!!
- - - ## Regression R2 and RMSE score Table
|    Car_Details_dataset    |    Model                    |  Train(R2-score)   |  Train(RMSE)      | Test(R2-score)     |  Test(RMSE)       |
| :-------------------      | :--------------------       | -----------------  |-----------------: | -----------------  |-----------------: |
|Bangalore                 | Linear Regression           |      0.8716         |0.01943             | 0.8433              |0.02210              |
|Bangalore                    |HistGradientBoostingRegressor|0.9980               |0.0023           | 0.9299              |0.01477             |
|Chennai                 | Linear Regression           |      0.8906         |0.0033             | 0.9005              |0.0029              |
|Chennai                   |HistGradientBoostingRegressor|0.9989               |0.0003          | 0.9488              |0.0021             |
|Hyderabad                 | Linear Regression           |      0.865         |0.0001             | 0.838              |0.0001              |
|Hyderabad                    |HistGradientBoostingRegressor|0.9987               |1.30e-05           | 0.9256              |9.50e-05             |
|Jaipur                 | Linear Regression           |      0.7722         |4.98e-11             | 0.7509              |5.32e-11              |
|Jaipur                    |HistGradientBoostingRegressor|0.9827               |1.37e-11           | 0.9045              |3.29e-11             |
|Kolkata                 | Linear Regression           |      0.8174         |8.99e-14             | 0.7998              |9.47e-14              |
|Kolkata                    |HistGradientBoostingRegressor|0.9977               |1.00e-14           | 0.9081              |6.42e-14             |
|Delhi                 | Linear Regression           |      0.7043         |0.1292             | 0.7313              |0.1305             |
|Delhi                    |HistGradientBoostingRegressor|0.9264               |0.0644           | 0.8032              |0.1117            |
- I have uploaded the ipynb notebook for DELHI CARS named **delhi_ML_29features.ipynb** today(15/2/2024) in which I have built the ML model.
- From 248 features ,through various analysis and tests I used **29 features** to predict the 'price' of the cars from DELHI.
- For other 5 CITIES I used only **23 features**. By using only 23 features to predict the price of DELHI cars, did not give good results.So I used 29 features.
- ### Hope the overall project results are good!!!
