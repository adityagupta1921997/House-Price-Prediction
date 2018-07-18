# House-Price-Prediction
#### (Predict house price dependent on certain features using regression algorithm)

How to predict house prices just by having some data based on certain features, ever wondered?
Let's create a project that will do that for us.

First we have to take same dataset that has housing features and depending on that price for that house.
So, we are taking "Boston Housing Dataset", this dataset concerns housing values in Boston suburbs.

The target is medv: median value of owner-occupied homes in terms of thousands of dollars ($1000s).

Features:

1.crim: per-capita crime rate by town.

2.zn: proportion of residential land zoned for lots over 25,000 sq.ft.

3.indus: proportion of non-retail business acres per town.

4.chas: Charles River dummy variable (=1 if tract bounds river; 0 otherwise)

5.nox: nitric oxides concentration (parts per 10 million)

6.rm: average number of rooms per dwelling.

7.age: proportion of owner-occupied units built prior to 1940.

8.dis: weighted distances to five Boston employment centres.

9.rad: index of accessibility to radial highways.

10.tax: full-value property-tax rate per $10,000.

11.ptratio: pupil-teacher ratio by town.

12.b: 1000(Bk-0.63)^2 where Bk is the proportion of black people by town.

13.lsat: percent lower status of the population.

14.medv: median value of owner-occupied homes in terms of thousands of dollars ($1000s).

So,we have data ready,let's dig into the code now...

First notice the correlation among these features since later it will be important to extract the features that largely affects the
price of the house.

![boston1](https://user-images.githubusercontent.com/30611434/42888701-6b1ef568-8ac6-11e8-9efa-819af746f492.png)

Okay, now I will use some regression methods of "Machine Learning" to analyse the dataset and improve the accuracy of the model.

## 1. Linear Regression

![boston3](https://user-images.githubusercontent.com/30611434/42889202-78a9ad6c-8ac7-11e8-8786-3034dfdeec80.png)

## 2. Robust Regression

![boston2](https://user-images.githubusercontent.com/30611434/42889064-26a2e8f8-8ac7-11e8-8906-3084680c3bf4.png)

See "Multiple Regression inside the code section".

In the second part, you can watch out validation and learning curve.

![boston4](https://user-images.githubusercontent.com/30611434/42892543-b33c2024-8acf-11e8-9bc5-443e8808fe17.png)

![boston5](https://user-images.githubusercontent.com/30611434/42892551-b6f5c490-8acf-11e8-87e7-250d55ae97a4.png)

* We have some Non Linear Realtionships too...

Using Decision Tree:

![boston6](https://user-images.githubusercontent.com/30611434/42892814-607859ba-8ad0-11e8-8d71-2ddbebf70fc6.png)

And atlast but not the least ,check out Polynomial Regression....

![boston7](https://user-images.githubusercontent.com/30611434/42892931-a7c5fa7a-8ad0-11e8-92b9-1a679598fd6c.png)

So,that's all...Do Any change you feel will be appropriate and will give good results.

### Thanku... Have a nice day!! 
