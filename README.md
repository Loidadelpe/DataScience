# DataScience
Repository storing content engine recommendation project

# What movie should I watch tonight?

# A content recommendation engine with predictive analytics

Nowadays there is a high demand for content recommendation systems from users. This is also true for businesses because they drive higher engagement and retention rates and ultimately ROI levels. Recommendation engines provide tailored options creating personalized experiences for users and adding value to businesses and there are used not only for movies, but on multiple other products and services (e.g. Amazon, Spotify, Google, YouTube)

My hypothesis is that the more meaningful our recommendations the higher the user engagement and retention rates of our website.

Based on this, I have attempted to predict the next 20 movies a random user could watch tonight based on his/her taste or preferences with Machine Learning.

The success of this project looks like our recommendations being meaningful enough to be used on the website and with real users.

This is the final project of my Data Science course with General Assembly Melbourne and a first experiment with predictive modelling and Machine Learning techniques. For this project, I used my personal computer which meant limited computing resources so my choice of model needed to be resource economic.

Finally, I will point out that I have no previous industry knowledge of my data.


### How to get started?

Please refer to Movie, Ratings and Users data files to access MovieLens 1M raw data. MovieLens 1M is a popular data set for recommendation systems dated from 2000. The files contain data on approximately 6,000 users, 4,000 movies and 1 million anonymous ratings. 

My data includes incorrect entries, inconsistencies and missing values like duplicates, typos, etc. due to human error.

All demographic information is provided voluntarily by the users and is not checked for accuracy. Only users who have provided some demographic information are included in my data sets and their profiles might not be representative of total number of users.

For more information on data dictionary and the project design refer to the Problem statement and research design file located in this repository.

The next step I followed was acquiring the data which is documented under the Data manipulation previous to analysis file. 

When parsing my data, I implemented an exploratory analysis and verified the quality of my data. This step is documented under Descriptive analysis file. 

The file Predictive analysis contains detailed steps on how I mined and refined my data and built three different models with its corresponding optimisation approaches. 

Finally, I consolidated the findings of this project into a high level presentation to introduce the insights to a non technical audience. 

The presentation is called What movie should I watch tonight and it's also saved in this repository.

### The results

The third model explored provided meaningful movie recommendations for random users based on his/her preferences.

The outcome was tested on three randomly selected users and I was able to populate the top 20 movies that we could recommend for the three of them. I considered the recommendations meaninful enough to be used on a website. 

### Improvements

The fact that topics didn't seem meaningful enough to me when inmplementing the LDA model didn't mean that the model wasn't working properly so a prediction could have been performed to confirm the final outcome.

The SVD approach is limited to linear projections but Deep Learning and Neural Networks use linear and non-linear layers so they could be used for better predictions in the future.


### Contact infomation

Feel free to contact me at loida.delgado-perez@gmail.com or alternatively via LinkedIn at linkedin.com/in/loidadelgadoperez

If you would like to contribute or share this project you are welcome to do so. Thanks!
