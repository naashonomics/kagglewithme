# kagglewithme

#linear Regressions

"""
from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn import metrics

X=list['columns']

y=value_to_preidct

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=<* of datatest to be used for testing>, random_state=<0-1000>)

lm = LinearRegression()

lm.fit(X_train,y_train)

lm.coef_

X_train.colums

predictions=lm.predict(X_test)

plt.scratter(y_test,predictions)

print('MAE:', metrics.mean_absolute_error(y_test, predictions))

print('MSE:', metrics.mean_squared_error(y_test, predictions))

print('RMSE:', np.sqrt(metrics.mean_squared_error(y_test, predictions)))

coeffecients = pd.DataFrame(lm.coef_,X.columns)

coeffecients.columns = ['Coeffecient']

coeffecients

print('MAE:', metrics.mean_absolute_error(y_test, predictions))

print('MSE:', metrics.mean_squared_error(y_test, predictions))

print('RMSE:', np.sqrt(metrics.mean_squared_error(y_test, predictions)))

print('variance_score:',metrics.explained_variance_score(y_test, predictions))

"""


[2017] Personalized Medicine: Redefining Cancer Treatment: Predict the effect of Genetic Variants to enable Personalized Medicine => 

Kaggle problem link: https://www.kaggle.com/c/msk-redefining-cancer-treatment

My Solution: https://github.com/naashonomics/kagglewithme/blob/master/Medical%20treatment.ipynb 


