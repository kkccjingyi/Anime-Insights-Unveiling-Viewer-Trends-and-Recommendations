# Anime-Insights-Unveiling-Viewer-Trends-and-Recommendations


## Summary ##
The Anime Insights project offers a comprehensive analysis of the anime viewership landscape, focusing on identifying viewer preferences, demographic trends, and patterns in content consumption. Utilizing extensive datasets from MyAnimeList, the project provides in-depth insights into the diverse and dynamic world of anime.

Our analysis is aimed at empowering streaming companies to refine their recommendation algorithms, thereby offering more personalized and accurate anime suggestions to their diverse user base. By examining various aspects such as genre popularity, viewer demographics, and individual ratings, the project sheds light on the intricate preferences and behaviors of anime enthusiasts.

Key findings of the project include the identification of popular genres and trends in viewer preferences, understanding the impact of different anime characteristics on viewer choices, and analyzing the effectiveness of existing recommendation systems. These insights are invaluable for streaming services in enhancing viewer engagement and satisfaction, as well as for anime producers and studios in anticipating market trends and tailoring their content accordingly.

In conclusion, the Anime Insights project serves as a vital resource for anyone interested in the evolving landscape of anime viewership and its implications for content creation and distribution in the streaming era.

​
**Authors**: Kunjingyi Chen, Aryan Kumar, Mauro Wang, Tanvi Sheth, Pritam Pandit

**Date**: 12/12/2023

---
​
## Data Source ##


This dataset has been procured from MyAnimeList and the owner in Sajid Uddin. Direct access link: https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset/data
​---

**Data Overview**
There are 3 tables in the dataset. The following tables explain each feature in the dataset.

---
​
**anime_data_2023**

|Index| Feature           | Description |
|:----------------| :---------------- | :--------|
|0| anime_id | Unique ID for each anime. |
|1| Name | The name of the anime in its original language. |
|2| English name | The English name of the anime. |
|3| Other name | Native name or title of the anime(can be in Japanese, Chinese or Korean). |
|4| Score | The score or rating given to the anime. |
|5| Genres | The genres of the anime, separated by commas. |
|6| Type | The type of the anime (e.g., TV series, movie, OVA, etc.). |
|7| Episodes | The number of episodes in the anime. |
|8|  Aired | The dates when the anime was aired. |
|9|  Premiered | The season and year when the anime premiered. |
|10| Status | The status of the anime (e.g., Finished Airing, Currently Airing, etc.). |
|11| Producers | The production companies or producers of the anime. |
|12| Licensors | The licensors of the anime (e.g., streaming platforms). |
|13| Studios | The animation studios that worked on the anime. |
|14| Source | The source material of the anime (e.g., manga, light novel, original). |
|15| Duration | The duration of each episode. |
|16| Rating | The age rating of the anime. |
|17| Rank | The rank of the anime based on popularity or other criteria. |
|18| Popularity | The popularity rank of the anime. |
|19| Favorites | The number of times the anime was marked as a favorite by users. |
|20| Scored By | PThe number of users who scored the anime. |
|21|  Members | The number of members who have added the anime to their list on the platform. |
|22|  Image URL | The URL of the anime's image or poster. |
​
---
**users-details-2023**

|Index| Feature           | Description |
|:----------------| :---------------- | :--------|
|0| Mal ID | Unique ID for each user. |
|1| Username | The username of the user. |
|2| Gender | The gender of the user. |
|3| Birthday | The birthday of the user (in ISO format). |
|4| Location | The location or country of the user. |
|5| Joined | The date when the user joined the platform (in ISO format). |
|6| Days Watched | The total number of days the user has spent watching anime. |
|7| Mean Score | The average score given by the user to the anime they have watched. |
|8| Watching | The number of anime currently being watched by the user. |
|9| Completed | The number of anime completed by the user. |
|10| On Hold | The number of anime on hold by the user. |
|11| Dropped | The number of anime dropped by the user. |
|12| Plan to Watch | The number of anime the user plans to watch in the future. |
|13| Total Entries | The total number of anime entries in the user's list. |
|14| Rewatched | The number of anime rewatched by the user. |
|15| Episodes Watched | The total number of episodes watched by the user. |
---
**users-score-2023**

|Index| Feature           | Description |
|:----------------| :---------------- | :--------|
|0| user_id | Unique ID for each user. |
|1| Username | The username of the user. |
|2| anime_id | Unique ID for each anime. |
|3| Anime Title | The title of the anime. |
|4| rating | The rating given by the user to the anime. |
---
---
​**Reference**

[1] MyAnimeList, Data Source [Reference](https://myanimelist.net/)

[2] Anime News Network. [Reference](https://www.animenewsnetwork.com/encyclopedia/people.php?id=150459)

[3] Nielson, **Streaming claims largest piece of TV viewing pie in July, Nielson**. [Reference](https://www.nielsen.com/insights/2022/streaming-claims-largest-piece-of-tv-viewing-pie-in-july/)

[4] M. Soltanieh-ha, "BA775 - Business Anaytics Toolbox", Fall 2023

---
