Dashboard link: https://public.tableau.com/shared/4JNPMQS7S?:display_count=n&:origin=viz_share_link

Introduction: Steam is a video game distribution service primarily for the PC platform originally released in 2003 by Valve Corporation. It is currently the largest such platform for PC games, and it is well-known for its semi-annual sales in the summer, winter, and fall. This dashboard aims to dissect Steam's pricing by tracking the prices of 2000 games from April 2019 to August 2020 and providing insights into discount distribution.

Data/operation abstraction design: The data for this dashboard was collected from two sources: a dataset pulled from the SteamDB API and used for a paper on player traffic (https://data.mendeley.com/datasets/ycy3sy3vj2/1) and a dataset of publisher information from VGInsights (https://vginsights.com/publishers-database). The data from the former source was cleaned and summarized using Python; this was then pulled into Alteryx along with the second dataset to join app/price data to publisher data.

Future work: The historical prices were pulled for a period of 16 months. While there is no publicly available record of historical Steam prices, current prices are freely available on SteamDB. By continuing to pull current data for a longer period of time, better insights can be made into discount trends at the annual level.
