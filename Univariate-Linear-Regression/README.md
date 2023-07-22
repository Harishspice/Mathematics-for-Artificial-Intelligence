# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
# Implementation of Univariate Linear Regression
## Aim:
To implement univariate Linear Regression to fit a straight line using least squares.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the independent variable X and dependent variable Y.
2.	Calculate the mean of the X -values and the mean of the Y -values.
3.	Find the slope m of the line of best fit using the formula.
  ![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/297f8919-458e-4f04-9cc4-cbad8f3b3372)

4.	Compute the y -intercept of the line by using the formula:
![image](https://github.com/Harishspice/Mathematics-for-Artificial-Intelligence/assets/117935868/f07a15d0-0079-4dc5-add8-19d30a53e1f5)
5.	Use the slope m and the y -intercept to form the equation of the line.
6.	Obtain the straight line equation Y=mX+b and plot the scatterplot.
## Program
```
Developed By: Harish R
Register No: 22005828
import numpy as np
import matplotlib.pyplot as plt
x=np.array(eval(input()))
y=np.array(eval(input()))
xmean=np.mean(x)
ymean=np.mean(y)
num,den=0,0
for i in range(len(x)):
num+=(x[i]-xmean)*(y[i]-ymean)
den+=(x[i]-xmean)**2
m=num/den
c=ymean-m*xmean
print(m,c)
y_pred=m*x+c
print(y_pred)
plt.scatter(x,y)
plt.plot(x,y_pred, color="orange")
plt.show()





```
## Output
![Screenshot (69)](https://user-images.githubusercontent.com/117935868/215329889-da3df445-0a67-4fa5-b721-29df5bca1599.png)
![Screenshot (70)](https://user-images.githubusercontent.com/117935868/215329935-277bf83e-29df-4ef8-9fd7-f9aa5bf2100f.png)


## Result
Thus the univariate Linear Regression was implemented to fit a straight line using least squares.4.	Compute the y -intercept of the line by using the formula:
