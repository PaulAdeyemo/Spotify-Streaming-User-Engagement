# Spotify-Dashboard


## Problem Statement

This dashboard aims to help Spotify streaming platform understand their users better. It also helps the Spotify know how their users engaged with albums over time. Also, in today’s digital music era, understanding the listening pattern is crucial for both users and streaming platforms in other to make informed decisions. 



### Steps followed in Project

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in all of the columns errors & empty values were present except column named "Album name" & “track name”.
- Step 5 : For calculating total album name & total track name, null values were not taken into account as only less than 1% values are null in this columns(i.e. column named "album name" & “track name”) 
- Step 6 : Data was then loaded into power BI after cleaning was performed with power query tool. 
- Step 7 : Calculations were done to answer all the business questions required so as to uncover insights into the aim of the analysis using DAX calculation features in Power BI.
- Step 8 : Spotify official color was used for this project and this was sourced from https://www.color-hex.com/color-palettes/?keyword=spotify
- Step 9 : Dashboard UI design template was sourced from https://www.pinterest.com/zerpixelung/dashboard-ui/ for dashboard inspiration and layout.
- Step 10 : Visual filters (Slicers) was added for one field named "Platform".

# Insights
- The total track streamed from 2013 to 2024 is 13665.

- Over the months, February recorded the least number of track streamed across all platform  contributing 24.5% of the overall track, while September recorded the highest number of track streamed across all platform contributing 34.6% of the overall track across all the years.

- It is worthy of note that most users prefer to stream their songs on Android platform as compared to other streaming platform. This contributed to the highest number of track streamed in 2021 which makes up 40.1% of all the songs streamed on Android platform across all the years.

-  "Ode to the Met" track is the most streamed across all streaming platform. This means  that the more android user stream a track  the  more they likely stream "Ode to the Met" track.

-  There is a significant dip in the number of tracks streamed in 2024 as compared to previous year (2023) from Jan to Jul. However, Aug to Nov 2024 recorded a significant rise in the number of tracks streamed as compared to 2023.

- Most Spotify users engages with more tracks on weekdays as compared to weekends at about 12AM - 7am & 4pm - 11pm majorly with android users.

# Recommendation
1. Leverage High-Engagement Months (September Focus)
Since September accounts for 34.6% of all streams, platform-specific promotions, artist drops, or exclusive content campaigns should be concentrated in September to maximize impact and revenue.

✅ Action: Align release schedules, app updates, or seasonal campaigns with this period.

2. Optimize Engagement During Low-Traffic Months (February Dip)
February’s 24.5% share indicates a drop in user activity. This can be an opportunity for retention campaigns, discounts, or curated playlists to sustain engagement during a lull period.

✅ Action: Test incentive-based campaigns or partnerships during February to flatten seasonality.

3. Prioritize Android Experience & Marketing
Android users dominate stream volumes, especially with a 40.1% spike in 2021. Android should remain the primary focus for feature updates, performance optimization, and push notifications.

✅ Action: Allocate greater development and ad spend toward Android user acquisition and retention.

4. Feature “Ode to the Met” in Algorithmic & Editorial Playlists
Given that “Ode to the Met” is consistently the most-streamed track, and closely tied to Android user activity, it may be a key driver for stickiness or session length.

✅ Action: Promote similar tracks, create ‘Because you liked Ode to the Met’ playlists, or analyze its metadata to inform content curation.

5. Investigate 2024 Streaming Dip (Jan–Jul) & Act on Aug–Nov Recovery
The decline in early 2024 may suggest content fatigue, platform issues, or seasonal disengagement. The recovery in Aug–Nov should be analyzed for triggers (new releases, marketing, platform changes).

✅ Action: Run A/B tests or retrospective campaign analysis to identify what contributed to the bounce-back and replicate it earlier in future years.

6. Align Spotify & Android Engagement Windows with Targeted Pushes
High engagement on weekdays between 12AM–7AM & 4PM–11PM suggests user behavior peaks during commutes and late-night listening.

✅ Action: Schedule push notifications, new content releases, or ads to align with these time bands for better click-through and conversion rates.



