# Machine Learning Application in Finance: Predicting Forex direction using Neural Networks

Capstone Project for the Advanced Data Analytics Class @ HEC Lausanne

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
## Description of the project
This repository contains code for a project that predicts forex price movements using machine learning techniques.
The project explores various neural network models trained on different datasets, including technical and macroeconomic indicators.
The goal is to assess the effectiveness of these models in forecasting the direction of forex prices, considering the inherent challenges of non-stationarity in forex markets.

## Structure of the project
- **data-prep.ipynb:** This notebook contains all the code used to import raw data and transform it into the various final datasets used in the forex price prediction project. It includes data preprocessing steps such as cleaning, feature engineering, and dataset splitting. The notebook serves as a comprehensive guide to the data preparation process undertaken before model training and evaluation.

- **hyper-parameters.ipynb:** This notebook finds the optimal hyper-parameters for the nine different models used in the forex price prediction project. It includes the processes of hyper-parameter tuning and model selection processes to ensure each model's best possible performance.

- **eurusd-predictions.ipynb:** This notebook contains the code for predicting the EUR/USD currency pair using the trained models. It includes the prediction process, evaluation metrics, and analysis of the results to assess the models' performance in predicting the direction of EUR/USD price movements.

- **models-checkpoints folder** This folder contains the trained models saved as `.h5` files. These models can be imported and used for making predictions on new data.
## Screenshots
![image](https://github.com/mdorentin/ADAproject/assets/72168825/aa05ef68-6ca8-4e2d-b15c-c76498fa61c0)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/a5fe6d50-12c4-438c-83e1-05f219fad2cf)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/883639d6-17bf-4dbd-912c-68412b7e2807)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/728e3270-d335-4112-a83a-526a64d930c4)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/d0eed4a9-257e-407a-8263-71ec9fe15e42)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/b88a9d56-d3d5-4a59-aaa3-53d72bb49c31)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/05d07eb7-ad27-4836-a630-f092ccb4b27d)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/07a657ed-ee7a-437c-b2a0-ef30c42c0b5c)

![image](https://github.com/mdorentin/ADAproject/assets/72168825/4d04c194-ef92-4491-959e-cf3d9d73686f)

## Disclaimer
This project is for educational and research purposes only. The models and techniques used in this project are intended to explore the potential of machine learning for forex price prediction. Predicting financial markets is inherently uncertain and involves significant risk. The results and models presented in this repository should not be considered as financial advice or relied upon for making trading decisions. Always conduct your own research and consult with a professional financial advisor before making any investment decisions. The authors of this project are not responsible for any financial losses or damages resulting from the use of the information or models provided in this repository.






