# Best Home Regions
This project is a part of the ADS-505 Applied Data Mining course in the Applied Data Science Program at the University of San Diego.

**Project Status: [Completed]**

## Installation
    To use this project, clone the repository on your device using the command below:
        
        git clone git@github.com:clairebentzen/best_home_regions.git

## Project Objective
Investing in real estate properties is a known method for generating wealth and passive income. Making well-informed decisions is based on how profitable a property might be. To determine profitability, factors such as mortgage rates, rent ratios, and location are used. CKM Real Estate LLC is interested in determining what areas of the United States provide the best opportunities for investments. In addition to geographical regions of best investment, when CKM Real Estate is presented with a list of new potential properties they are interested in knowing which properties are the best investments. Using unsupervised and supervised models, this project aims to seek the best regions and identify the best investments.

### Project Contributors
Claire Bentzen - https://github.com/clairebentzen

Jiaqi He - 

Sultan Mahmud Rahat - https://github.com/smahmudrahat

### Methods Used
- Data Mining
- Regression Modeling
- Data Manipulation
- Data Visualization
- Programming
- Clustering
- Unsupervised Learning
- Supervised Learning

### Technologies
- Python

## Project Description
The dataset that is used for this project was aggregated data from Zillow. It consists of over fourteen thousand records and 168 variables. Using Python as the programming language, the team performed exploratory data analysis, data preprocessing, and evaluated several different models, including unsupervised and supervised models. The models included multiple linear regression, random forest regression, gradient boost regression, and CNN-LSTM. The models were first assessed by analyzing the r-squared score, then were further evaluated using MSE, MPE, MAPE, ME, and RMSE to determine the best performing model to accurately predict the New_Composite_Score for properties. The optimal method was selected with the intentions of using it in the deployment stage to predict New_Composite_Scores for new lists of properties.

## License
MIT License

Copyright (c) 2023 Claire Bentzen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
