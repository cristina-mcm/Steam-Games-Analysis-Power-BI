# Steam Games Market Analysis | Power BI

## Project Overview

For this project I considered a scenario where a game developer is considering releasing a new title on Steam and wants to better understand the market before making decisions about game type, pricing, monetization, and positioning. This Power BI report combines information from multiple sources to explore Steam game sales, genres, pricing, player modes, publisher classes, player activity, and estimated revenue trends.

## Dashboard

There are 6 pages in Power BI:

Page 1 - Market Research
<img width="1572" height="884" alt="image" src="https://github.com/user-attachments/assets/f57a87a2-3779-4c19-8f5e-1bb9420dfbb5" />
Page 2 - Number of DLC vs Copies Sold
<img width="1571" height="882" alt="image" src="https://github.com/user-attachments/assets/3d257b4f-8490-4300-8c65-6d705ece1d4f" />
Page 3 - Top 20 games released in the past 1,3,5 years
<img width="1573" height="880" alt="image" src="https://github.com/user-attachments/assets/0dd27dac-d782-4d48-bf92-34950ec0e8fc" />
Page 4 - Top 50 Best Selling Games - Paid
<img width="953" height="379" alt="image" src="https://github.com/user-attachments/assets/67c3967b-e772-44e8-86dd-614c55ccdbc2" />
Page 5 - Top 50 Best Selling Games - Free to Play
<img width="1186" height="373" alt="image" src="https://github.com/user-attachments/assets/12be925f-c07a-43ad-9de1-dc2be28f8184" />
Page 6 - Top 50 All-time Peak
<img width="1019" height="371" alt="image" src="https://github.com/user-attachments/assets/1083a0ce-5e6a-447f-8407-d991cdb93b87" />

## Questions Explored

1. Which Steam games have achieved the highest estimated sales?
2. Which genres are most common on the platform?
3. How do single-player and multiplayer games compare in typical sales?
4. How does game price relate to estimated copies sold?
5. How do free-to-play and paid games differ in revenue performance?
6. How does publisher class affect game performance?
7. Which games have reached the highest all-time concurrent player peaks?
8. Does the number of DLC influence the number of copies sold?

## Key Dashboard Insights
- A small number of titles dominate Steam performance. Counter-Strike 2, Dota 2, and PUBG: BATTLEGROUNDS repeatedly appear among the leaders in estimated sales, revenue, and concurrent players.
- Indie games dominate the catalog, but not necessarily the highest-revenue segment. AAA and AA titles are disproportionately represented among the strongest commercial performers.
- Games offering both single-player and multiplayer modes have the highest median estimated copies sold in the dataset.
- Games priced between $40 and $59.99 show the highest median estimated copies sold, although current prices and Steam discounts limit how strongly this relationship can be interpreted.
- Free-to-play games are prominent among the highest estimated revenue performers, particularly titles supported by long-term engagement, microtransactions, and large multiplayer communities.
- Action, Adventure, and RPG are especially prominent among major-publisher titles, while Indie and Casual dominate the overall number of releases.
- DLC quantity does not show a clear relationship with estimated copies sold.
- The strongest pattern is not one single feature, but a combination of multiplayer engagement, continued content or monetization, strong community activity, and sustained visibility.

## Report

The analysis shows that a relatively small group of games dominates Steam in estimated copies sold, player activity, and revenue. In this dataset, Counter-Strike 2 has the highest estimated number of copies/downloads, while Dota 2 and PUBG: BATTLEGROUNDS also appear consistently among the strongest-performing titles. Steam's historical relationship with Valve games provides useful context for this result. Counter-Strike has been closely connected to Steam since the platform's early development, which helped the franchise build a very large and long-established player community.

Genre patterns change depending on which part of the market is examined. Across the complete dataset, Indie is the most common genre, followed by Casual, Action, Adventure, and Simulation. However, among games released before 2013, Action becomes the most common genre. When the analysis is restricted to AAA games, Action, Adventure, and RPG are the leading genres. This suggests that the overall genre distribution is heavily influenced by the large number of newer indie releases and should not be interpreted as a direct measure of consumer demand.

Player mode also appears to be an important characteristic. Games that offer both single-player and multiplayer experiences have the highest median estimated copies sold, followed by multiplayer-only and then single-player-only games. The dataset itself does not establish that adding multiplayer causes higher sales, but one possible explanation is that multiplayer and cooperative features broaden the ways players can experience a game and allow them to play with friends, partners, or online communities. An example that supports this interpretation from a game-development perspective is Subnautica. The original game was primarily designed as a single-player experience, while multiplayer functionality became an important feature planned for Subnautica 2, including during its Early Access development. This may reflect a broader shift toward accommodating players who want to experience games socially rather than exclusively alone.

Pricing shows another interesting pattern. Using the median rather than the average reduces the effect of unusually successful blockbuster titles. Games currently priced between $40 and $59.99 have the highest median estimated copies sold, followed by games priced between $20 and $39.99. This relationship should be interpreted cautiously because the dataset contains current listed prices rather than historical launch prices. Steam also runs frequent sales, and games in these price ranges can sometimes receive substantial discounts, meaning the listed price may differ considerably from what many customers actually paid.

The revenue analysis highlights the importance of the free-to-play business model. Several of the strongest estimated revenue performers are free-to-play games, including Dota 2, Counter-Strike 2, Apex Legends, Warframe, and PUBG: BATTLEGROUNDS. Some of these titles originally used a paid model before later transitioning to free-to-play. Their revenue is generated largely through continued engagement and optional purchases rather than through an initial purchase price. One possible explanation for the strength of this model is the psychology of smaller optional purchases. A player who would hesitate to spend a large amount upfront may be comfortable spending approximately $5 on a weapon skin, cosmetic item, or other in-game purchase. In multiplayer games, these purchases may also have a social component: players can personalize their characters, equipment, or appearance and use those choices to express themselves within the game community. This is an interpretation based on familiarity with the gaming market rather than a causal relationship demonstrated by the dataset.

Competitive gaming may reinforce this effect. Several titles that repeatedly appear among the strongest performers—such as Counter-Strike 2, Dota 2, PUBG: BATTLEGROUNDS, and Apex Legends—also have established competitive or esports communities. Professional tournaments can offer very large prize pools; for example, major Counter-Strike 2 tournaments can reach approximately $1 million to $2 million in prize money. Competitive visibility may help maintain player interest, attract new players, and encourage continued spending. Again, the dashboard cannot establish that esports participation causes higher revenue, but the overlap between highly successful games and competitive gaming is notable.

Publisher class also appears to matter when examining estimated copies sold. AAA publishers account for many of the largest sales figures in the dataset. When AAA titles are excluded, AA publishers generally form the next strongest group, with several games reaching estimated sales in the tens of millions of copies. Indie games are far more numerous overall, but only a relatively small number reach comparable sales levels. This illustrates an important difference between market presence and commercial scale: indie games represent a large portion of Steam's catalog, while exceptionally high sales are concentrated among a much smaller number of titles. The analysis did not reveal a clear relationship between the number of DLCs and estimated copies sold. Games with large DLC catalogs are not consistently the highest-selling games, suggesting that simply offering more downloadable content is not, by itself, a reliable indicator of stronger sales.

Overall, the dashboard suggests that many of Steam's strongest-performing games combine several characteristics: multiplayer or cooperative gameplay, long-term player engagement, strong communities, recognizable genres such as Action, and monetization opportunities beyond the original purchase. Free-to-play multiplayer games with optional purchases are particularly prominent among the highest-revenue titles. Based on both the dashboard and broader knowledge of the gaming market, one possible interpretation is that a successful long-term model may involve giving players a low barrier to entry while creating reasons to remain engaged and spend smaller amounts over time. Multiplayer interaction, personalization, competitive play, and ongoing content can all contribute to that ecosystem. However, these observations should not be interpreted as a guaranteed formula for success. The analysis does not include unsuccessful games using the same strategies in enough detail to establish causation, and factors such as game quality, marketing, community management, development resources, timing, and long-term support are also likely to have substantial effects.

## Tools & Skills

- Power BI
- Power Query
- DAX
- Data modeling
- Data transformation
- Data visualization
- Dashboard design
- Data integration
- Market analysis

## Data Sources

- The report combines information from several sources, including:
- Steam Games Dataset: Daily Updates – Kaggle
- Gamalytic – Estimated copies sold and additional game-level information
- Steam / Valve – Annual Best of Steam information
- SteamDB – Selected historical concurrent-player information
- Additional publicly available reports and industry sources used to estimate historical Steam game revenue

## Limitations

- Sales and revenue figures are estimates rather than official Valve financial data.
- Some historical revenue estimates were compiled from different sources and currencies and converted to USD.
- Current listed prices may differ from launch prices or historical sale prices.
- Genre and tag classifications can overlap because a game may belong to multiple categories.
