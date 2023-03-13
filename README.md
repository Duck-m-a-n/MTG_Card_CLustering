__Magic the Gathering Card Clustering__

`Introduction`

This project is a clustering analysis of Magic the Gathering cards using their attributes. The project contains two CSV files - cards.csv and legalities.csv. The cards.csv file contains information about each Magic the Gathering card, including its name, mana cost, type, text, power, toughness, rarity, and other attributes. The legalities.csv file contains information about the legality of each card in various Magic the Gathering formats, including the Commander format.

CSV Files
cards.csv
The cards.csv file contains information about each Magic the Gathering card, including its name, mana cost, type, text, power, toughness, rarity, and other attributes. The following columns are included in the file:

name

- convertedManaCost
- colors
- type
- text
- power
- toughness
- rarity
- format
- keywords
- edhrecRank
- subtypes
- edhrecSaltiness
- legalities.csv

The legalities.csv file contains information about the legality of each card in various Magic the Gathering formats, including the Commander format. The following columns are included in the file:

- name
- format
- legality
- Clusters
The cards in the cards.csv file have been clustered into four clusters based on their attributes. The clusters and their characteristics are as follows:

- Cluster 0 - "Mid-Cost Creatures / Low-Cost Utility"
- Cluster 1 - "Low-Cost Spells / Low-Power Aggro"
- Cluster 2 - "Low-Cost Creatures / Midrange Control"
- Cluster 3 - "High-Cost Powerhouses / High-Power Beatdown"

For each cluster, we provide the median and mean values of the attributes used in the clustering, as well as a description of the cluster's characteristics and potential use in Magic: The Gathering gameplay.

`EDA`

Exploratory data analysis (EDA) can be performed using the columns in the cards.csv file to gain a deeper understanding of the clusters and identify potential synergies or strategies. The following steps can be taken during EDA:

Verify the cluster titles and traits by checking the cards in each cluster to see if they fit the cluster's description based on their basic statistics.

Identify any unique or common keywords by checking the 'keywords' column to see if any keywords appear more frequently in certain clusters.

Analyze the color distribution by checking the 'colors' column to see which colors are dominant in each cluster.

Investigate the format distribution by checking the 'format' column to see which formats each cluster is most commonly used in.

Explore the principal component (PC) values in each cluster to see if there are any patterns or trends.

Check the edhrecRank and edhrecSaltiness values to see which clusters contain cards that are more popular or more niche.

By performing EDA using these columns, it's possible to gain a deeper understanding of the clusters and potentially identify more useful insights for deck construction and in-game strategies.

`Conclusion`

This project provides a useful clustering analysis of Magic the Gathering cards that can be used to improve deck construction and in-game strategies. The CSV files and clusters can be used by players to identify potential synergies and create powerful decks. The EDA steps can be used to further explore the data and gain deeper insights into the game.
