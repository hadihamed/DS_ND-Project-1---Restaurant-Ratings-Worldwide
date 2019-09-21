# DS_ND-Project-1---Restaurant-Ratings-Worldwide

This project takes a look at Zomato restaurant review for ~9,500 restaurants around the world. It is being completed
for the Udacity Data Scientist Nanodegree. I chose this dataset because restaurants are interesting to analyze from a
science vs art perspective, in asking how much of a restaurants success can be predicted by the basic fundamentals of
the place. I am particularly interested in what makes certain restaurants successful while others wither away, and what
amount of that success could be easily predicted from an outside perspective (i.e. just given the basic variables, such as
country, cuisine type, and pricing).

The dataset comes from Kaggle, and was uploaded by Shruti Mehta. It can be accessed here:
https://www.kaggle.com/shrutimehta/zomato-restaurants-data

Project Files:
Zomato_project.ipynb - Jupyter Notebook of analysis
zomato.csv - raw data downloaded from kaggle

Libraries:
matplotlib - Used for graphing and displaying graphs within the notebook
scikit-learn - Used for data processing and machine learning models
numpy - Array management and data processing
pandas - Data organization and processing
statsmodels - Tool used to run linear regressions with p-value reporting
seaborn - data visualization and graphing tool

Summary:
Overall there was a very normal distribution of restaurant ratings, averaging near 3.5 out of 5. Prices, country,
and cuisine type were all significant variables in predicting restaurant ratings. However, the variables in the dataset
do not seem to be sufficient in creating a highly accurate predictions. Intuitively, there is much more to a restaurant
experience than the price, type of cuisine, and the country in which it is located. There are trends accross these
variables though that suggest the variables are to some degree significant. Price seems to be the highest predictor of
ratings, as it is most significant in multiple feature importance methods and has the strongest positive correlation.
Restaurants in India have an innate disadvantage from a ratings perspective, but answering why is not plausible with the
given dataset. The analysis suggests that there is more depth to restaurant ratings than the relationship between
price, cuisine, and country. A follow-up analysis might seek to include variables regarding speed of service, quality
of service, and quality of the atmostphere/environment.

