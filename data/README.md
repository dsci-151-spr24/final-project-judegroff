The name of this data is Global_Music_Streaming_Listener_Preferences, and has 5000 observations and 12 variables.

- `User_ID`: Character data, represents one music platform "user".

- `Age`: Numerical data with the range 10-60, tells the age of the user.

- `Country`: Character data, represents where the music platform user streamed from.

- `Streaming.Platform`: Character data, tells the music platform the user streamed from.

- `Top.Genre`: Character data, tells the users most listened to genre of music.

- `Minutes.Streamed.Per.Day`: Numerical data with the range 0-600, shows the average amount of minutes listened per day in the years 2018-2024.

- `Number.of.Songs.Liked`: Numerical data with the range 0-500, shows the amount of songs the user has liked.

- `Most.Played.Artist`: Character data, shows the users most listened to artist.

- `Subscription.Type`: Character data, tells the type of subscription paid/not paid for.

- `Listening.Time..Morning.Afternoon.Night.`: Character data, tells the time of day the user listened to music the most.

- `Discover.Weekly.Engagement....`: Numeric data with the range 10-90, represents the percentage based on how much they interacted with weekly discovery feature.

- `Repeat.Song.Rate....`: Numeric data with the range 5-80, represents the percentage based on if a user would repeat a song.


##Executive Summary

This presentation explores global music streaming trends, with a specific focus on comparing these trends to those within the United States.

This presentation uses "Global_Music_Streaming_Listener_Preferences" dataset, which has 5000 observations and 12 variables, the variables being: User_ID, Age, Country, Streaming.Platform, Top.Genre, Minutes.Streamed.Per.Day, Number.of.Songs.Liked, Most.Played.Artist, Subscription.Type, Listening.Time..Morning.Afternoon.Night., Discover.Weekly.Engagement...., and Repeat.Song.Rate.....


The primary research questions addressed in this presentation are:

1.  What are the most popular music streaming platforms globally and in the USA?
2.  How does the usage of different streaming platforms compare between the USA and the rest of the world?
3.  What are the differences in subscriptions (paid vs. not paid) between the USA and global users?
4.  Does a region with more paid subscribers listen to more music overall?


My methods were varying, when I first read in the dataset, I shortened the name to "GMSLP" as to make typing it in code easier. I also made multiple subsets of the read in data, such as "platform_counts", "platform_percentages", "platform_usage", and "region totals" for use in later visualisations and tables. The first tables show what the percentage of each streaming platforms usage globally and then in the USA, followed by a visualisation that compares global excluding USA users, and USA users. Then another visualisation is shown to compare whether people in the USA pay more often for music streaming subscriptions or not, which can be correlated to whether or not a country more willing to pay for music, also listens to more music, which is compared on the follwing slides with 2 tables.

Findings:

1. Amazon Music is the most used streaming platform globally, with 17.22% of users.

2. USA users are more likely to pay for a music subscription, but it only seems 1% more likely, although this may have varied with a larger sample of users.

3. This does not result in more listening time it would seem, which you could assume is because the USA is generally a wealthier country, they may be more inclined to purchase a music streaming subscription even if they do not use it as much.
