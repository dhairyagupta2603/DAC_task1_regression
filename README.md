**20BRS1077**
# Problem Statement 
Can you use your regression skills to predict the age of a possum, its head length, whether it is male or female? This classic practice regression dataset comes originally from the DAAG R package (datasets used in examples and exercises in the book Maindonald, J.H. and Braun, W.J. (2003, 2007, 2010) "Data Analysis and Graphics Using R"). This dataset is also used in the OpenIntro Statistics book chapter 8 Introduction to linear regression.
<br>
The possum data frame consists of nine morphometric measurements on each of 104 mountain brushtail possums, trapped at seven sites from Southern Victoria to central Queensland.

## Dataset

The dataset used is the [Possum Regression](https://www.kaggle.com/abrambeyer/openintro-possum) from Kaggle. 
<br>
The class labels are:
<br>
**1. Case:** Observation number
<br>
**2. Site:** The site number where the possum was trapped
<br>
**3. Pop:** Population, either Vic (Victoria) or other (New South Wales or Queensland)
<br>
**4. Sex:** either m (male) or f (female)
<br>
**5. Age:** Age of possum
<br>
**6. Hdlngth:** Head length
<br>
**7. Skullw:** Skull width in mm
<br>
**8. Totlngth:** Total length in cm
<br>
**9. Tail:** Tail length in cm
<br>
**10. Footlgth:** Foot length
<br>
**11. earconch:** ear conch length
<br>
**12. Eye:** Distance from medial canthus to lateral canthus of right eye
<br>
**13. Chest:** Chest girth in cm
<br>
**14. Belly:** Belly girth in cm

**Target Variables: -**
<br>
<ul>
    <li>Can we use total length to predict a possum's head length?</li>
    <li>Which possum body dimensions are most correlated with age and sex?</li>
    <li>Can we classify a possum's sex by its body dimensions and location?</li>
    <li>Can we predict a possum's trapping location from its body dimensions?</li>
</ul>

## Models Used
### 1. Linear regression
 Linear Regression is the supervised Machine Learning model in which the model finds the best fit linear line between the independent and dependent variable i.e it finds the linear relationship between the dependent and independent variable.
 This regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression.
The typical equation of a line is y = mx + a, where m is the slope, x is independent variable and y is dependent variable that we are interested in predicting

### 2. Support Vector Regression
Support Vector Machine can also be used as a regression method, maintaining all the main features that characterize the algorithm (maximal margin). The Support Vector Regression (SVR) uses the same principles as the SVM for classification, with only a few minor differences. First of all, because output is a real number it becomes very difficult to predict the information at hand, which has infinite possibilities
Assuming that the equation of the hyperplane is as follows:

Y = wx+b (equation of hyperplane)
Then the equations of decision boundary become:

wx+b= +a

wx+b= -a

Thus, any hyperplane that satisfies our SVR should satisfy:

-a < Y- wx+b < +a 

Our main aim here is to decide a decision boundary at ‘a’ distance from the original hyperplane such that data points closest to the hyperplane or the support vectors are within that boundary line.

## Future Work
Testing with more regression algorithms and using stocks data of other companies to deduce their dependence. 
Also consider using date-time data to do a time-series analysis.
