# DataEthicsIP
Data Ethics 259 Independent Project

My project looks at data context and how the ability to classify and separate data allows for more accurate conclusions and a better understanding of the data itself. It heavily leans on the idea of the Simpson Paradox, in which trends that appear in smaller groups of data will reverse or disappear in larger groups of data. My projects takes overview player passing data from the 2021-2022 English Premier League and looks at various ways of splitting the data into smaller groups to produce better insights and conclusions.

i) The question I address is: how does lack of context harm a data scientist’s ability to extract meaningful information, or more importantly, how can context be added to a dataset to allow data scientist’s to better extract meaningful information?
ii and iii) In my research, I read about the Simpson paradox, in which meaningful trends can appear in smaller segments of datasets that otherwise would not be seen in the full dataset. Taking the data I chose to use, soccer player passing data, I took two approaches, first splitting it by team, which showed me top passers per team, some of which otherwise would’ve been obscured in the larger dataset. Second, I split the types of passes into several categories, showing me better tails and separation between player passing ability. At the same time, I also split players by position, using k-means clustering to determine player positions, as, while player positions were listed in the dataset, depending on scheme, formation, and tactics, position definitions are to a degree fluid. The k-means clustering allowed me to better categorize players into four groups, most significantly dividing midfielders between defensive, attacking, and true midfield role. The conclusion I reached was essentially that splitting data works. The best way to get meaningful insight from a dataset is to drill into it; to look at smaller subsections and extract meaning from those.

 <img src="Poster.png" alt="Poster"> 
