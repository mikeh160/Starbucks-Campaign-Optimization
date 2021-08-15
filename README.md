# Starbucks Campaign Optimization

In this project, the objective is to perform an A/B testing for the starbucks promotional campaign and help determine clients that would bring optimal results for the company

## Table of Contents
1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [Instructions](#instructions)
4. [Results](#results)
5. [Licensing, Authors & Acknowledgments](#licensing)

## Project Motivation<a name="motivation"></a>

The project is offered by Udacity. The objective is to perform an A/B testing for the starbucks promotional campaign on the evaluation metrics that have already been identified by the starbucks marketing team. These evaluation metrics are set to be **Incremental Response Rate(IRR)** and **Net Incremental Revenue (NIR)**. Tests for significance will be performed to identify whether the promotion had any effect on the purchasing habit of consumers. Moreover, ML algorithms will be used to better identify the clients that would help in success of the promotional camapaign. 


<img src="https://render.githubusercontent.com/render/math?math=IRR=\frac{purch_{treat}}{cust_{treat}} - \frac{purch_{ctrl}}{cust_{ctrl}}">



<img src="https://render.githubusercontent.com/render/math?math=NIR = (10\cdot purch_{treat} - 0.15 \cdot cust_{treat}) - 10 \cdot purch_{ctrl}">

## File Description<a name="files"></a>

These are the files in the project.

```
1. training.csv                -file containing the dataset for training the ML algorithm
2. Test.csv                    -file containing further data for testing and making prediction
3. Starbucks.ipynb             -jupyter file containing all the analysis along with code and explanations
4. test_results.py             -file written in python to verify the results obtained through ML prediction

```

## Instructions<a name="instructions"></a>

In order to run the project place the files in the same directory. There aren't any special libraries needed to run this project. The standard ones needed are Pandas, numpy, scipy and sklearn

## Results<a name="results"></a>

Tests for significance are performed (**i.e. using Null Hypothesis and Alternative Hypothesis**) and it is found that while the population in control group and experimental group do not have any significant difference, promotional campaign did result in a positive "significant" increase for the IRR i.e. a significant chunk of customers did end up buying the product/service under the promotional campaign. However, using the same population groups, the revenue collected did not result in any "significant" increase for starbucks. i.e. the NIR metric. Therefore, machine learning algorithm is applied to find a better segment of clients. The algorithm provides a better segment of customers which helped make the revnue collected i.e. NIR metric positive.

## Licensing, Authors & Acknowledgments<a name="licensing"></a>

Incredibly grateful to the team at Udacity as well as Starbucks for providing the data. 
