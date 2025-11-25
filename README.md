# BrightTV-Analysis
Overview

This case study analyses user consumption patterns for BrightTV, focusing on understanding when users watch, what they watch, and which factors influence their engagement.
The objective was to generate insights that could support BrightTV’s Customer Value Management (CVM) team and help the CEO achieve the goal of growing the company’s subscription base.



How the Case Study Was Done
1. Data Preparation

Imported the BrightTV dataset containing:
UserID, Channel, RecordDate, Time (UTC), and Session Duration

Cleaned the dataset to remove missing or corrupted values

Converted all timestamps from UTC → South African Time (UTC+2)

Extracted additional variables:

Viewing hour

Day of week

Month

Channel usage frequency

Aggregated data at daily, hourly, and channel level


2. Exploratory Data Analysis (EDA)

Analysed user activity patterns

Identified peak and low consumption periods

Compared channel performance

Analysed session duration variation across content types

Identified factors that influence overall viewing behaviour

3. Visualization & Insight Development

Created charts to visually interpret viewing behaviour, including:

Line charts for hourly trends

Bar charts for day-of-week trends

Bar graph showing Channel consumption comparisons

Day-of-Week Consumption

Line graph shwoing User Activity



Developed insights based on these visuals to support decision-making



Key Insights Found

1. Hourly Consumption Trends

00:00–04:00 — Consumption is at its lowest. Most users are asleep during these early hours.

04:00–07:00 — Viewership rises as people wake up and prepare for work or school, often watching morning shows.

07:00–11:00 — Consumption stabilizes; the number of active users remains constant during typical morning routines and commute times.

12:00–20:00 — A steady and significant increase in consumption is observed throughout the day, peaking during late afternoon and prime-time hours when users are home and relaxing.

After 20:00 — Viewership drops sharply as most users wind down for the night.

2. Daily Consumption Trends

Sunday — One of the highest consumption days. Users are home, relaxing, and spending time with family around TV content.

Saturday — Also high in consumption. People are home and have more free time to watch TV.

Monday — One of the lowest days. Users are busy, focused on work, and less likely to watch TV.

Tuesday–Thursday — Consumption increases after Monday, with a slight drop after Wednesday as the work week progresses.

3. Channelt Consumption

Supersport Live Events is the top-performing channel with 1,662 viewers, indicating strong preference for sports.

ICC Cricket World Cup 2011 ranks second with 1,465 viewers, reinforcing BrightTV’s highly engaged sports audience.

Live on Supersport has 2 viewers, both from the same day — likely a discontinued or inactive channel.

Wimbledon has 3 viewers, also likely inactive or shut down.

4. User Activity Insights

Active Users — Many users consistently engage with BrightTV. The average number of sessions per user is around 10, showing strong retention among engaged viewers.

Light Users — A large portion of users watch only once or very infrequently. This signals an opportunity for re-engagement and targeted campaigns.



Tools Used

Snowflake - Analyze data using SQL

Microsoft – Data review and visualization

PowerPoint – Final presentation design

Miro – Flow diagrams and insight mapping



