# sample-datasets
### Diabetes dataset
This dataset is originally from national Institute of Diabetes and Digestive and Kidney Diseases.

**Objective:** 
To predict whether or not a patient has diabetes.
Content
It consists of variables number of pregnencies,BMI,insulin level,ageetc.,
It can be download from **[link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0101EN-SkillsNetwork/labs/Module%205/data/diabetes.csv)**. we collected data from link and store in pandas data frame. we did data wrangling and descriptive analysis by finding null values correct data types & calculate count min,max values. we can plot pie chart to find how many patients has diabetes.AS we can see above,65.10% females are Diabetic and 34.90% are NonDiabetic.

### Extract Stock data
A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares."

if stock price increases, invester profits
if stock price decreases, invester incurr in losses
we use yfinance and python library
we will return data into pandas dataframe. we extract apple company share. we find apple stock max price. we create subplot of apple stock max price with open and high dates.we find apple dividents and plot it.

#### House Sales in King County, USA
Import dataset from **[link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/kc_house_data_NaN.csv)**. and stored in pandas data frame. we did data exploration by checking number of columns , data types of each column.we did descriptive analysis. we did data wrangling by checking and dropping null columns and replace with mean and finf descriptive analysis.Exploratory data analysis done by calculating value counts. we create boxplot for houses with waterfront view.we create regplot for houses having sqft positively or negatively correlated with price.we find feature which is correlated with price. we created **Linear regression** model to predict price using sqft feature and find r^2 . predict price using list of reatures.create pipeline object to predict price using featured list.Model evaluation and refinement can be done by calculating cross val score,train test split.create ridge regression object and find r2.Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, set the regularisation parameter to 0.1, and calculate the R^2 utilising the test data provided.

### Airline Dataset
we will be using **[airline dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/airline_data.csv)**. from Data asset exchange.
**Airline Reporting Carrier On-Time Performance Dataset**
The Reporting Carrier On-Time Performance Dataset contains information on approximately 200 million domestic US flights reported to the United States Bureau of Transportation Statistics. The dataset contains basic information about each flight (such as date, time, departure airport, arrival airport) and, if applicable, the amount of time the flight was delayed and information about the reason for the delay. This dataset can be used to predict the likelihood of a flight arriving on time.
Read airline data into pandas dataframe.we ramdomly consider 500 data points for further analysis.
**plotly.graph_objects**
Review scatter plot creation
*Theme: How departure time changes with respect to airport distance
To do - Create line plot
Theme: Extract average monthly delay time and see how it changes over the year
**plotly.express**
Review bar chart creation
*Theme: Extract number of flights from a specific airline that goes to a destination
To do - Create bubble chart
*Theme: Get number of flights as per reporting airline
To do - Create histogram
*Theme: Get distribution of arrival delay
Review pie chart
*Theme: Proportion of distance group by month (month indicated by numbers)
To do - Create sunburst chart
*Theme: Hierarchical view in othe order of month and destination state holding value of number of flights
