# sample-datasets
### Diabetes dataset
This dataset is originally from national Institute of Diabetes and Digestive and Kidney Diseases.

**Objective:** 
To predict whether or not a patient has diabetes.
Content
It consists of variables number of pregnencies,BMI,insulin level,ageetc.,
It can be download from [link]("https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0101EN-SkillsNetwork/labs/Module%205/data/diabetes.csv"). we collected data from link and store in pandas data frame. we did data wrangling and descriptive analysis by finding null values correct data types & calculate count min,max values. we can plot pie chart to find how many patients has diabetes.AS we can see above,65.10% females are Diabetic and 34.90% are NonDiabetic.

### Extract Stock data
A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares."

if stock price increases, invester profits
if stock price decreases, invester incurr in losses
we use yfinance and python library
we will return data into pandas dataframe. we extract apple company share. we find apple stock max price. we create subplot of apple stock max price with open and high dates.we find apple dividents and plot it.
