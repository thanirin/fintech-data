# Credit Card Fraud
**credit**: Andrea Dal Pozzolo. Université Libre de Bruxelles. [Adaptive Machine Learning for
Credit Card Fraud Detection](https://di.ulb.ac.be/map/adalpozz/pdf/Dalpozzolo2015PhD.pdf). 2015.  

**data**: [download data (csv file)](https://drive.google.com/file/d/1_0dwvuTBA8Dm-zRme86oyYeaw2PhFBFO/view?usp=sharing)

### Data Description
**Number of Instances**: 285,299  
**Number of Attributes**: 31 (numerical)

For confidentiality reason, the meaning of most variables is not revealed and the features have been transformed by means of principal components. The cardholder identifier is also not available so each transaction can be considered independent from the others.

#### Attribute Description

Attribute 1: Time  
This denotes the seconds elapsed between each transaction and the first transaction in the dataset.  

Attribute 2: Amount  
This is the transaction amount which can be used for example-dependent cost-sensitive learning.  

\** *The remaining attributes are unidentifiable for confidentiality reason.* \**

#### Class  
There are 2 classes; 0 and 1, with 1 being fraud and 0 otherwise.

The dataset is highly unbalanced; frauds only represent 0.172% of all transactions.

### Additional Information

### Example Activities

can be found more on the [paper](https://di.ulb.ac.be/map/adalpozz/pdf/Dalpozzolo2015PhD.pdf)
