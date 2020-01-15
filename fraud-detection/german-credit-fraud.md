# German Credit Fraud
**credit**: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [source](https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29). Irvine, CA: University of California, School of Information and Computer Science. 

**data**: [download data (csv file)](https://raw.githubusercontent.com/thanirin/fintech-data/master/fraud-detection/data/credit_fraud.csv)   

### Data Description

**Number of Instances**: 1000  
**Number of attributes**: 20 (7 numerical, 13 categorical)

#### Attribute Description
Attribute 1: (qualitative) Status of existing checking account   
There are 4 values:
1) <0
2) 0<=x<200
3) \>=200
4) no checking

Attribute 2: (numerical) Duration in Months  
example: 24 months

Attribute 3: (qualitative) Credit History  
There are 5 values:
1) "no credit/all paid" - no credits taken or all credits are paid back duly
2) "all paid" - all credits at this bank are paid back duly
3) "existing paid" - existing credits are paid back duly till now
4) "delayed previously" - delay in paying off in the past
5) "critical/other existing credit" - critical account or other credits existing (not at this bank)

Attribute 4: (qualitative) Purpose
There are 11 categories:  
1) 'new car'
2) 'used car'
3) furniture/equipment
4) radio/tv
5) 'domestic appliance'
6) repairs
7) education
8) vacation
9) retraining
10) business
11) other

Attribute 5: (numerical) Credit amount  

Attribute 6: (qualitative) Savings account / bonds  
There are 5 values:  
1) <100
2) 100<=X<500
3) 500<=X<1000
4) \>=1000
5) no known savings

Attribute 7: (qualitative) Present employment since  
There are 5 categories:  
1) unemployed - currently employed
2) <1 - employed less than a year
3) 1<=X<4 - employed more than 1 year, but less than 4 years
4) 4<=X<7 - employed more than 4 years, but less than 7 years
5) \>=7 - employed more than 7 years

Attribute 8: (numerical) Installment rate in percentage of disposable income  
There are 4 values: 1, 2, 3, and 4

Attribute 9: (qualitative) Personal status and sex  
There are 5 categories:  
1) male div/sep - male: divorced or separated
2) female div/dep/mar - female: divorced, separated, or married
3) male single - male: single
4) male mar/wid - male: married or widowed
5) female single - female: single

Attribute 10: (qualitative) Other debtors / guarantors  
There are 3 categories:  
1) none
2) co applicant
3) guarantor

Attribute 11: (numerical) Present residence since  
There are 4 values: 1, 2, 3, and 4

Attribute 12: (qualitative) Property  
There are 4 categories:  
1) real estate
2) life insurance - building society savings agreement / life insurance
3) car - car or other, not in attribute 6
4) no known property

Attribute 13: (numerical) cc_age in months  
example: 24 months

Attribute 14: (qualitative) Other installment plans  
There are 3 categories:  
1) bank
2) stores
3) none

Attribute 15: (qualitative) Housing  
There are 3 categories
1) rent
2) own
3) for free

Attribute 16: (numerical) Number of existing credits at this bank  
There are 4 values: 1, 2, 3, and 4

Attribute 17: (qualitative) Job  
There are 4 types:
1) unemp/unskilled non res - unemployed or unskilled non-resident
2) unskilled resident - unskilled resident
3) skilled - skilled employee or official
4) high qualif/self emp/mgmt - management, self-employed, highly qualified employee or official

Attribute 18: (numerical) Number of people being liable to provide maintenance for  
There are 2 values: 1 or 2

Attribute 19: (qualitative) Telephone  
There are 2 categories: 
1) none
2) yes - registered under the customer's name

Attribute 20: (qualitative) foreign worker  
There are 2 categories:  
1) yes
2) no

#### Class
This is the defined result of each credit. There are 2 classes; *good* and *bad*. 

### Additional Information

It is advisable to use **cost matrix** for the reason that it is *worse* to classify a customer as good when they are bad than it is to classify a customer as bad when hey are good. 

##### The cost matrix that can be used with this dataset (see below)

<table>
  <tr>
    <td colspan=2></td>
    <th colspan=2>Predicted Value</th>
  </tr>
  <tr>
    <th colspan=2></th>
    <th>Good</th>
    <th>Bad</th>
  </tr>
  <tr>
    <th rowspan=2>Actual<br>Value</th>
    <th>Good</th>
    <td>0</td>
    <td>1</td>
  </tr>
  </tr>
    <tr>
    <th>Bad</th>
    <td>5</td>
    <td>0</td>
  </tr>
</table>

The **rows** represent the actual classification.  
The **columns** represent the predicted classification. 
