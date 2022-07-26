# Final Project: Weather Prediction
In this project, we would conduct an entire process of data problem from collect data to visualize and predict the weather of new sample.

## Project Planning
You could access our project planing by click to the [Project_Planing](https://github.com/stark4079/Weather_Prediction/blob/main/Teamwork.pdf).

## Environment
Project is created with:
* min_ds-env: last updated on Sep 11, 2021
* imbalanced-learn version: 1.7.1
* scikit-learn version: 0.24.2
	
## Setup
Activate the **min_ds-env** environment before launching to Jupyter Notebook. Install the requirements before runing the **Final_Project.ipynb**

```
pip install -U imbalanced-learn
```
## Collecting Data
In this section, we would introduce how to crawl data from api provided by Ambee.
- Collect data in the first 13 days of each month on 3 time intervals including 7-9 AM, 11-13 PM, 16-18 PM.
- Input API query including longtitude, latitude, and key api.
- Due to the limit number of API calls each day (500 times/day), we couldn't crawl of all day in each months.

## Imbalance Data
In this section, we would introduce some techniques to solve the imbalance problem about collected data.
- Collect more data.
- Under-sampling.
- Over-sampling.

## Build Model
We conducted the experiments on 2 models:
- Multi-layer Perception.
- Support Vector Machine.

## Results

1. MLP model result on origin data
    - Train loss value: 8.64
    - Alpha value: 10
    - Test loss value: 10.94
2. MLP model result on supplement data
    - Train loss value: 12.72
    - Alpha value: 0.1
    - Test loss value: 14.5
3. SVM model result on origin data
    - Train loss value: 13.43
    - Kernel: Poly
    - Test loss value: 13.02

## About Us
Our project includes two contributors:
- Tran Xuan Loc - 18127131 - 18127131@student.hcmus.edu.vn
- Thai Hoang Huy - 18127109 - 18127109@student.hcmus.edu.vn
