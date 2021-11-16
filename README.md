# Genre_Twitter_Analysis

The final porject for DS 710 - Programming for Data Science included an open ended analysis fo Twitter data using the Twitter API.

I chose to evaluate the popularity of musical genres based on their perceived popularity on Twitter.  Popularity is determined in two ways. First, by overall tweet count then by the number of exclamation marks used within those tweets.

Tweets were collected using the REST API through Python. The program grabbed (up to 5000) tweets that were categorized into genres.

Two methods were used (in R Studio) in order to evaluate the relationship between tweet count and exclamation mark count by genre.
First, I evaluated the potential for a linear relationship between both variables. The variables were plotted against one another in a scatterplot (Figure 3), and a summary of the linear model was created.
Secondly, the variables (Tweet Count & Exclamation Count) were compared in a Chi Squared Test of Independence.
