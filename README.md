# linear_regression
I am enthusiastic about the Python&amp; Machine learning programming language. I have explained the code I found at¨https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html¨ here.

#### Linear regression helps us estimate values we don't know the formula for; this estimation is based on feature values.
#### Linear regression is vastly used for business and economic problems; a simple example can be price calculation based on the weight of items.

In the following, we fit a linear regression model for the abovementioned problem.

    Weight = [[2],[2.5],[3.5],[4],[6],[10]]
    Price = [10,15,17,20,25,30]
    from sklearn.linear_model import LinearRegression
    reg = LinearRegression().fit(Weight,Price)

I employed the linear regression method of the scikit learn library to calculate a linear regression model and find out how precise 
is that

    print(reg.score(Weight,Price))
now I want to predict the price with my model, I assume the weight is fifty

    reg.predict([[50]])
