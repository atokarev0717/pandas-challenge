# pandas-challenge
Data Analysis Using Pandas

# Heroes of Pymoli
Heroes of Pymoli is a fantasy game. The Data Set includes purchases information by player - [The Data Set Sample](./HeroesOfPymoli/Images/Data_Sample.png)
The analysis looks into the game's purchases data to discover trends that can be translated into business insights and opportunities.

## [Analysis Summary](./HeroesOfPymoli/Images/total_purchasing_analysis.png)
The script is written in Jupiter Notebook and it looks into the data by Gender and by Age. It identifies Top Spenders and Most Popular Items by purchase count and by purchase value. 

### Gender
Analysing gender data the script generates [demographic summary table](./HeroesOfPymoli/Images/demographic.png) and [purchases by gender table](./HeroesOfPymoli/Images/gender.png)
* Vast majority of all players are **males** (84%). The company should take a close look at the product and include additional features that will attract the **female** population. Additionally, marketing strategy should be revised to reach more of **female** population
*  2% of customers chose not to disclose gender. Addressing lack of **female** customers will also make the product more appealing to **Other / Non-Disclosed** gender population as the product will become more diversified in general
* An average **Female** spent more per item than a **Male**. Therefore, once again, attracting more of **Female** population will positively impact revenue
### Age
Analysing gender data the script generates [purchases by age table that looks at unique players only](./HeroesOfPymoli/Images/age_unique_players.png) and [purchases by age table that looks at all players including returning customers](./HeroesOfPymoli/Images/age_all_players.png)
* Top 3 (by number of players) age groups are: 20-24, 15-19, 25-29 years old, listed in descending order
* There is however representation of p;ayers of all ages from 7 to 45 years old. Therefore, the population, other than 15-29 years old, should not be ignored when new items and new features of the product are being developed. Keeping that in mind will keep the existing clients and will potentially attract new ones
### [Top Spenders](./HeroesOfPymoli/Images/top_spenders.png)
* 4 out 5 Top Spenders are **males**
* 5 purchases is the most number of purchases one player made. Items with additional features should be developed and  a reward program should be implemented to encourage players to spend more
### Most Popular Items
* [Top items by purchase count](./HeroesOfPymoli/Images/top_items_count.png) and by [top items by purchase value](./HeroesOfPymoli/Images/top_items_value.png) (combined) are: 'Final Critic', 'Oathbreaker, Last Hope of the Breaking Storm', 'Fiery Glass Crusader', 'Persuasion', 'Extraction, Quickblade Of Trembling Hands', 'Nirvana', 'Singed Scalpel'.
* Features of the items should be further analyzed to determine main reasons why these items are the most successful ones