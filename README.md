# NBA Free Agent Salary Predictor

**Note**:  *This is a very rudimentary iteration of what later became the more sophisticated [Hoops Hero](https://github.com/andreilevin/HoopsHero) project.  It was also my first foray into machine learning (in this case, linear regression).*  

### Project Presentation [Slides](https://github.com/andreilevin/Regression_project/blob/main/AndreiPresentation.pdf) | [Video](https://youtu.be/1BuwIjbGifg):

[![Watch the video:](https://raw.githubusercontent.com/andreilevin/Regression_project/main/youtube_screen.jpg)](https://youtu.be/1BuwIjbGifg)



## Summary

We can all go online to look up our favorite NBA player's current salary, but how do we tell if this salary matches up with his actual market value?  In other words, if this player suddenly became a free agent, how much would a team likely pay him compared to what he's making now?  To answer this question, I scraped the last 5 years of NBA free agent data and trained a linear regression model to predict the contract each free agent signed, based on their previous-season data.  Using this model, I was then able to predict a market value for current NBA players (including non- free agents) based on their season stats so far. 

## Tools

* Beautifulsoup for web scraping
* Pandas for data cleaning, filtering and aggregation
* Statsmodels and scikitlearn for regression modelling
* Matplotlib and Seaborn for plotting 