# data-visualization-in-python

# Ford GoBike Data Set Analysis
## by Chinedu Uzorue


## Dataset

> This dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 183,412 rows and 16 columns. Of the 16 columns, 9 are numerical (int64 and float64 types), 7 are non-numerical (object type). It is worthy of note that some variables have the wrong data types such as the start_time and end_time, which are object types instead of datetime types


## Summary of Findings

> My major findings include:
- My variable of interest "Trip duration" has a unimodal distribution, with most of the trips lasting between 0 and 1500 seconds

- There is a strong correlation between members of the male gender, especially those between 20 and 40 years of age and trip duration. There is a scanty correlation between members of "other" gender and the trip duration

- There is a somewhat weak correlation between the age of a member and the trip duration, although most of the members with high trip duration are in the 20 to 40 years old age group. There was also an interesting relationship observed between trip duration and member user type. Members with "Customer" member type go on rides for longer duration than members that are "Subscribers". Lastly, I observed that female members have a higher trip duration than males and "other" gender

- I continued my investigation of trip duration, along with age against some categorical variables in this section. From the multivariate exploration, I can confirm that there is a positive relationship between member gender and trip duration, as well as member age and trip duration. In using a scatterplot to check for the relationship between trip durattion, age, and member gender, I had to reduce the sample size so as to prevent overplotting as the dataset was quite large.



## Key Insights for Presentation

> For the sake of presentation, I trimmed down the number of visualizations to reflect the following key insights are:
- I start with by presenting the distribution of my variable of interest "trip duration (seconds),
- Next, I check for which gender category have the highest trip duration among the 3 genders
- I also confirmed the member types with  have the longest trip duration of the week
- Lastly, I did some feature engineering to see what age group have the most trip duration


### References
> I used the following links to get an idea of what to do for my visualizations:

https://github.com/manishjanky/analyse-ford-gobike-dataset/blob/master/data_exploration.ipynb

https://notebooks.githubusercontent.com/view/ipynb?browser=chrome&color_mode=auto&commit=5b6c668e5a6e2fd851d263546964f8878bfe310b&device=unknown&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6469726b6b6164696a6b2f466f72642d476f42696b652d446174612d4578706c6f726174696f6e2d616e642d436f6d6d756e69636174696f6e2d6f662d696e7369676874732f356236633636386535613665326664383531643236333534363936346638383738626665333130622f315f6578706c6f726174696f6e5f476f42696b65735f62795f4469726b4b6164696a6b312e302e6970796e62&logged_in=false&nwo=dirkkadijk%2FFord-GoBike-Data-Exploration-and-Communication-of-insights&path=1_exploration_GoBikes_by_DirkKadijk1.0.ipynb&platform=android&repository_id=275154494&repository_type=Repository&version=98

https://github.com/adipurnamk/Ford-GoBike-System-Data/blob/master/exploration_fordgobike_2017.ipynb

https://deepnote.com/@dain-russell/bike-exploration-328b5ba1-25e4-4a35-aaad-e70146c9e182

https://www.kaggle.com/code/amrdawoud/ford-gobike-system-data-analysis

https://www.kaggle.com/code/chirag02/ford-gobike-data-analysis
