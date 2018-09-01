# Global-Video-Games-Sales

<b> Analysis of Global Video Games Sales</b>

In this project I explore the the sales of video games across the globe using different attributes of the games, such as genre, rating, and review score. The purpose of this project is to examine the factors that lead to a game having high sales, and to determine whether or not publishers try to influence critics' review scores.

### Tech Stack
- Matplotlib
- Pandas
- Python
- Plotly
- Seaborn
- Jupyter Notebook

# Summary
I chose to do this project because I like playing games and am interested in whether or not publishers pay for a higher score in a critic's review of their game. I have heard rumors and claims that reviewers get money from publishers and in return they are obligated to give their game a good review. 

First, I took the top publishers because they are the ones with the money to pay off reviewers and critics. The top 3 selling publishers across the globe were Electronic Arts, Nintendo, and Activision.


![pyplot](https://github.com/DarrellShih/Video-Game-Sales/blob/master/images/index.png)

Then I made a barchart showing the correlations of users scores and critic scores for each major publisher.

![plot](https://github.com/DarrellShih/Video-Game-Sales/blob/master/images/correlation.png)

The correlation for Sega was the heightest and for Activision it was the lowest. This might suggest that Activision pays for positive reviews of their games to help sell it. But it also suggests that not all publishers practice this. Sega, Nintendo, and Ubisoft all have very high correlations between user scores and critic scores. So it maybe that it is not an industry wide practice and just something that a few publishers do to try to boost their sales. 

![plot](https://github.com/DarrellShih/Video-Game-Sales/blob/master/images/scatter.png)

I also made a scatter plot of the publishers with the highest and lowest correlations. The two publishers reveal very different plots. Sega's plot has a clean and tight pattern with most points where user scores and critic scores are similar. Activision's plot is much more spread out with many points where there is large differences between critics and users scores. From this we can see that Activision specifically has many games where there is a major disagreement with users and critics. I think this suggests that Activision is trying to influence critic reviews.  

# Next Steps

I would like to look at each of the regions to see if this effect is the same. It would also be interesting to see if this correlation was the same over time.

# Datasets
https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings

*Refer to this link to see the plotly plots:https://nbviewer.jupyter.org/github/DarrellShih/Video-Game-Sales/blob/master/VGSAles.ipynb
