# Global-Video-Games-Sales

<b> Analysis of Global Video Games Sales</b>

In this project I explore the the sales of video games across the globe using different attributes of the games, such as genre, rating, and review score. The purpose of this project is to examine the factors that lead to a game having high sales, and to determine whether or not review scores or popularity matter more for the sales of a game.

### Tech Stack
- Matplotlib
- Pandas
- Python
- Plotly
- Seaborn
- Jupyter Notebook

# Summary
I chose to do this project because I like playing games and am interested in whether or not reviews really matter in determining the sales of a game. These days many games are sold as a pre-order package before the game is actually out so people buy games before they even know if they are good or not. So publishers get more sales for their games if they market the game harder rather than making the game better.

First, I took the top publishers because they are the ones that usually use the pre-order system the most. The top 3 selling publishers across the globe were Electronic Arts, Nintendo, and Activision.


![pyplot](https://github.com/DarrellShih/Video-Game-Sales/blob/master/images/index.png)

Then I made a heatmap of the correlations of the global sales of each publisher with user and critic metrics.

![plot](https://github.com/DarrellShih/Video-Game-Sales/blob/master/images/heat.png)

The correlations of the number of users is overall the highest than any of the other metrics. This finding supports my suspicion that the popularity or exposure the game has is much more impactful than scores of reviews from either critics or users. Because people buy games before they know how good they are the reviews don't matter as much as the number of people who simply knows the game exists. However, it was unexpected that for Electronic Arts and Nintendo, two of the top selling publishers, the difference between user count and score is not very large.

# Next Steps

I would like to look at each of the regions to see if this effect is the same. It would also be interesting to see if this correlation was the same over time.

# Datasets
https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

*Refer to this link to see the plotly plots:https://nbviewer.jupyter.org/github/DarrellShih/Video-Game-Sales/blob/master/VGSAles.ipynb
