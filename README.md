# Group.Project.1


As a group we set out to see the impact of the pandemic on movies and movie theatres. As we went looking for data sets that contained this information we quickly learned that there was no one comprehensive data set on the topic. 

So, Riley pulled a huge file of movie data by date using an api from https://developer.themoviedb.org/reference/search-movie. He cleaned the data and compiled a data frame that included: movie titles, year realeased and revenues. From this data frame he created multiple charts to show revenue by month and year. In addition, he utilized: https://www.reddit.com/r/learnpython/comments/a698qx/using_the_imdb_api_to_download_2018_film_data_and/ to gain insight in the api and how best to pull the information we were looking for. 

Jose focused on stock price data that he pulled from https://finance.yahoo.com/. He also gathered coronavirus data from https://ourworldindata.org/explorers/coronavirus-data-explorer. This particular csv file was too large to push to our repository. He created multiple charts for publicly traded movie and movie theatre companies. 

Erica pulled data regarding streaming services from https://www.kaggle.com/datasets/mauryansshivam/netflix-ott-revenue-and-subscribers. In addition she shared the website: https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.istockphoto.com%2Fphotos%2Fwatching-movie&psig=AOvVaw2FnppBlQ-z7I2ZxVkp3lQP&ust=1700272268887000&source=images&cd=vfe&ved=0CBIQjRxqFwoTCJiQ2fn1yYIDFQAAAAAdAAAAABAE which is were we took our stock photos for our presentation. She created multiple charts that showed Netflix's revenues and membership numbers over the same period of time that we were looking at. 

Our Summary is that we were able to show by time series analysis that movie revenues and movie stock prices were falling as covid numbers increased and streaming service revenues and memberships increased. We were surprised to see that movie revenue has lagged behind the 2018 and 2019 pre-pandemic totals. 

Netflix's Membership Journey: Pre- and Post-Pandemic
Before the pandemic, Netflix was already a streaming giant, proudly boasting a 
robust membership of over 148 million in the second quarter of 2019. The platform 
had successfully established itself as a household name, offering a diverse array of 
content. Fast forward to the aftermath of the pandemic, and Netflix isn't just holding
its ground; it's thriving, with a staggering 232 million of us hooked on its movies as 
of the second quarter of this year.
The surge in membership is not the only remarkable feat—Netflix's revenue has also
experienced a substantial lift. Pre-pandemic, Netflix's revenue stood at $4.5 billion 
in the second quarter of 2019. Remaining resilient, Netflix's total revenue has nearly
doubled, reaching $8.2 billion as of the second quarter of this year.
As the world strives to return to normalcy, Netflix is here to stay, and we're all in for 
the ride. It's not just about the numbers; it's about adaptation, entertainment, and 
becoming a global comfort zone. 
=======

### File Locations from Riley 
Full code is in main, I then broke it down into film_data and film_analysis. film_data contains the api call and the output of a csv file which is then analyzed in film_analysis. Both the csv from film_data and the charts from flim_analysis are found in output_data

##Refrences
*https://www.reddit.com/r/learnpython/comments/a698qx/using_the_imdb_api_to_download_2018_film_data_and/
*https://developer.themoviedb.org/reference/search-movie

