# TitanicMLProject
This is my submission for the **Kaggle** ML project using Titanic Dataset.

**Background:** Titanic was a British passenger liner that sank in the North Atlantic Ocean on 15 April 1912, after striking an iceberg during her maiden voyage from Southampton to New York City. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, making the sinking the deadliest peacetime sinking of a superliner or cruise ship to date. 
<BR></BR>
**Problem:** We are provided the data on passengers of Titanic such as age, Sex, Ticket Class, etc. and the goal is to predict if a passenger survived the disaster based on these metrics. 
<BR></BR>
**Approach:** We use a few *Imputation* techniques (explored *KNN-Regressions, Lasso, Mean, Mode*) to ensure there is no missing data first. Then a few different Machine Learning models such **Support Vector Machines**, **Logistic Regression**, and **Random Forest** are scoped for performance. Finally, the best model, which turns out to be *Logistic regression* is used for predictions on the *Test* data. This was submitted to Kaggle as well. Although it is possible to fine tune the predictions to the level of near perfect prediction, it is not the purpose of this ***Notebook***, and overfitting is not the practice I follow or advise, as generalized models are better in the long run. 
<HR></HR>
**Datasets:** Available in **titanic** folder in the root directory
<ul>
<li>**Train:** *.\titanic\train.csv*</li>
<li>**Test:** *.\titanic\test.csv*</li>
</ul>
<BR></BR>
The response variable **Survived** is not available in the **Test** dataset.

<table style="display: inline-block" "text-align: left">
  <tr>
    <th>Variable</th>
    <th>Definition</th> 
    <th>Values</th>
  </tr>
  <tr>
    <td>survival</td>
    <td>survival</td>
    <td>0 = No, 1 = Yes</td>
  </tr>
  <tr>
    <td>pclass</td>
    <td>Ticket class</td>
    <td>1 = 1st, 2 = 2nd, 3 = 3rd</td>
  </tr>
  <tr>
    <td>sex</td>
    <td>Sex</td>
    <td>male, female</td>
  </tr>
  <tr>
    <td>Age</td>
    <td>Age in years</td>
    <td>Numeric Range</td>
  </tr>
  <tr>
    <td>sibsp</td>
    <td># of siblings / spouses aboard the Titanic</td>
   <td>Numeric Range</td>
  </tr>
  <tr>
    <td>parch</td>
    <td># of parents / children aboard the Titanic</td>
    <td>Numeric Range</td>
  </tr>
  <tr>
    <td>ticket</td>
    <td>Ticket number</td>
    <td>Alphanumeric Values - Distinct</td>
  </tr>
  <tr>
    <td>fare</td>
    <td>Passenger fare</td>
    <td>Numeric Range</td>
  </tr>
  <tr>
    <td>cabin</td>
    <td>Cabin number</td>
   <td>Alphanumeric Values</td>
  </tr>
  <tr>
    <td>embarked</td>
    <td>Port of Embarkation</td>
    <td>C = Cherbourg, Q = Queenstown, S = Southampton</td>
  </tr>
</table>



</ul>

<HR></HR>

*Data Source: Kaggle.com*
