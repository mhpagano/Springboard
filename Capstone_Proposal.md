### What is the problem you want to solve?

The aim of this project is to estimate the contract of an NBA player based on his statistics.  Many CBA minutiae come into play when determing a contract and salary for a player.  This project rather will likely not tackle all of these cases, but focus on estimating the yearly salary of a player (as a percentage of salary cap).


### Who is your client and why do they care about this problem? In other words, what will your client DO or DECIDE based on your analysis that they wouldn’t have otherwise?

The client for a project of this sort would be an NBA team.  Theoretically, these estimates could be used to determine how the market would value a potential free agent NBA player. Knowing the approximate market value of player would help teams determine what to offer a player and if they would be over or underpaying for said player.  Additionally, this could serve as a rough proxy for the overall quality of a player.  The higher the market the values a player, the better that player is, presumably.  A well done metric of this type would be a great insight for overall roster construction.


### What data are you going to use for this? How will you acquire this data?

I intend on using data from either basketball-reference.com or stats.nba.com (or both).  As near as I can tell, neither site provides APIs currently and would require some scraping.  This could be a potentially difficult undertaking.  I have found some exisiting github account that have already created methods to scrape these site which I could rely on if the scraping proves to be difficult or time consuming.


### In brief, outline your approach to solving this problem (knowing that this might change later).

First, I intend on gathering player season/career data for many NBA seasons.  From there I will perform analyses, likely regressions, to determine what attributes are most predicitve of higher salaries.  I hope to create a series of equations that will allow me to estimate a player's salary.  I could potentially expand this to see if the "better" teams are the ones that have more "market value" in their current roster construction.


### What are your deliverables? Typically, this would include code, along with a paper and/or a slide deck.

My deliverable would likely be a conglomeration of code snippets, equations, data visualizations all wrapped into a slide deck or paper interpretting all of the intermediate and final findings of the project.
