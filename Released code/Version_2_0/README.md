# air-quality-prediction

This project is a group coursework on the data mining module designed to predict air quality (PM2.5, PM10, and NO2 concentrations of the next 48 hours) in London.

The entire folder of 'London' can refer to the sharing google drive folder, which contains all of the processed data files. (https://drive.google.com/drive/folders/1ueRCwIpzqs520pXdmIw77c9leaLDkO4y?usp=sharing)

Release note: (Compared with version 1.0)

Update the preprocessing of negative value in the 1_preprocessing.ipynb (Yuefu)

Add 23 statistical features in the 2_feature_engineering.ipynb (Yuefu)

Add 4 features (PM2.5_10 etc.) in the 2_feature_engineering.ipynb (Yuefu)

Add station_index feature in the 2_feature_engineering.ipynb (Yuefu)

Remove 64 weather forecasting features in the 2_feature_engineering.ipynb (Yuefu)

Update generating function in the 3_generate_train_data.ipynb (Yuefu)

Remove 48 one-hot features in the 3_generate_train_data.ipynb (Yuefu)

Add 156 historical and/or forecasting features in the 3_generate_train_data.ipynb (Yuefu)

Add prediction id feature in the 3_generate_train_data.ipynb (Yuefu)

Update lightgbm_model error result (now updating) in the 4_lightgbm_model.ipynb (Yuefu)
