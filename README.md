# metacritic_scraper 

I scraped critic scores from Metacritic to answer the following questions:

* **Do metacritic scores correlate with sales?**
    * Should a videogame publisher/developer pay attention to critic reviews?
   
* **Which critic's scores correlate best with sales?**
    *  Specifically, which critics should a videogame publisher/developer pay attention to?
 
## [🕷️Scraper.ipynb (Python)](scraper/my_scrape.ipynb)
   [Metacritic_Steam_2021.csv](scraper/Metacritic_Steam_2021.csv)
## [📈Analysis.ipynb (Python and R)](analysis/analysis.ipynb)
   [Analyzed.csv](analysis/analyzed.csv)

## Findings:
These critics scores ([analyzed.csv](analysis/analyzed.csv)) are positively and significantly correlated with the total number of Steam reviews the game received, our proxy for sales. The data seems to indicate that these critics know what makes a game sell (except *Game Revolution*, which is sigificantly negatively correlatated, do the opposite of what they say).
<br>
<br>

**Best Critic**: Top tier, and also better than Gamestar  
 * *Player 2*

**Top Tier**: These critic's correlations are significantly greater than the bottom tier.
* *Game Rant, Player 2, Meristation, Hardcore Gamer, IGN Italia, Jeuzvideo.com.*

**Medium Tier**: These critic's correlations are not significantly different than the others in the table.
* *Game Critics, Millenium, Evereye.it, Riot Pixels, CD-ACtion, Worth Playing, Impulsegamer, IGN, Ragequit.gr, Mccftech, Gamer Escape, meta_score, COGconnected, Softpedia, New Game Network, SpazioGames, TheGamer, PC Games, Multiplayer.it, GamingTrend, GameStar*(\*signficantly worse than Player 2)

**Bottom Tier**: These critic's correlations are significantly less than the top tier.
* *PC Invasion, Hey Poor Player, Shacknews, TheSixthAxis, The Game Machine, Noisy Pixel, Eurogamer Italy, Checkpoint Gaming, Game Revolution*
