# Machine Learning Regression Model- Dengue Prediction
A machine learning regression model trained using dengue datasets from Singapore to visualize the data and make accurate predictions.

- The dataset is obtained from a Singapore Government Agency Website website called [Data.gov](https://beta.data.gov.sg/), there you can find statistics regarding topics and real-time api and it's all open-sourced free forever, for commercial or personal use. The dataset I downloaded is called "Weekly Number of Dengue and Dengue Haemorrhagic Fever Cases" and can be found [HERE](https://beta.data.gov.sg/datasets/d_ac1eecf0886ff0bceefbc51556247015/view)
- I have also `web-scrapped` from various records to get a more comprehensive info of Weekly dengue infection records from sources such as the National Environmental Agency(NEA), also the mean temperature and rainfall values in Singapore from [WeatherSpark.com](https://weatherspark.com/y/114655/Average-Weather-in-Singapore-Year-Round).

## Purpose
The objective of this project is to visualize the data provided and utilize machine learning algorithms to train a model that could accurately predict future dengue outbreaks. The algorithm is able to predict that the incidence of dengue fever is likely to increase based on recent rainfall statistics, officials could use this model to take steps and mitigate the risks.

## Implementation
#### [Data-Preprocessing]
- The data from the 2 csv files are cleaned, trimed and logged as `new` datasets that is more suitable for the model, eg. 'New_Dengue_Cases.csv'
- Merge the 2 new files to create a final comprehensive dataset
  
#### [Statistical Analysis]
Measures the dataset using the below criterias:
- Mode, Median, Mean
- Measures of Spread
- Type of Distribution, Skewness and Kurtosis

#### [Data-Visualization]
Implement the **Seaborn** Library in order to display a graphical charts
- Histogram & Scatter Plot Each Year
- Pairplot
- Applying Simple Linear Regression

#### [Machine- Learning Implementation]
- Apply Logistic Regression
- Apply k - Nearest Neighbour
- Apply Decision Tree
