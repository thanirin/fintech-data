# Fraud Detection: Enron Email Dataset

# Enron Email Dataset
**credit**: William W. Cohen, MLD, CMU, (2015), [source](https://www.cs.cmu.edu/~./enron/).  

**data**: [download data (csv file)](https://drive.google.com/open?id=180eEc7iVlGqx5cCHWMBzSFvwZ_EOhcR4)

### Data Description
The Enron dataset contains approximately 500,000 emails. It was obtained by the Federal Energy Regulatory Commission during its investigation of Enron's collapse.  

However, the CSV version was obtained on [Kaggle](https://www.kaggle.com/wcukierski/enron-email-dataset) due to the messy format of the original raw data.

#### Attribute Description

Attribute 1: File  
This represents which mail belongs to who and from which mail box.   

Attribute 2: Message  
This is the content or the message of the mail.  


### Additional Information
The email dataset has been corrected to fix the integrity problems. The following changes have bee done:
1) Every attachment is removed.
2) Some messages have been deleted as part of a redaction effort due to requests from affected employees.
3) Invalid email addresses were adjusted to the form of `user@enron.com`. 
4) When no recipient was specified, the email address will be set to `no_address@enron.com`.

### Example Activities
1) From [Kaggle](https://www.kaggle.com/wcukierski/enron-email-dataset/kernels) which has many different kernels provided
2) Cleaning data to be easier to use. [source](https://github.com/brianray/data.world-scripts/blob/master/enron_email_script.ipynb)