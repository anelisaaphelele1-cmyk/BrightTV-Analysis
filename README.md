# BrightTV-Analysis
Overview

This case study analyses user consumption patterns for BrightTV, focusing on understanding when users watch, what they watch, and which factors influence their engagement.
The objective was to generate insights that could support BrightTV’s Customer Value Management (CVM) team and help the CEO achieve the goal of growing the company’s subscription base.

🛠️ How the Case Study Was Done
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

Channel consumption comparisons

Heatmaps for “hour vs day” behaviour

Histograms for session duration patterns

Developed insights based on these visuals to support decision-making

📊 Key Insights Found
1. User & Usage Trends

Peak viewing occurs in evening hours, especially between 18:00–21:00

Higher consumption on weekends, showing leisure-driven usage

Some channels consistently outperform others

Session duration varies by content type (e.g., movies have longer watch times)

2. Factors Influencing Consumption

Time of day and day of week strongly influence viewing patterns

Content type significantly affects session length

New content releases boost short-term consumption

Platform-related factors (internet availability, streaming quality) impact usage consistency

3. Low-Consumption Periods Identified

Midweek, especially Tuesdays and Wednesdays, show lower viewing activity

Midday periods (10:00–15:00) have the lowest session counts

These times present opportunities for targeted content scheduling

4. Content Recommendations

Mid-week content drops (new episodes, fresh releases)

Short-form content to suit low-engagement hours

Local-language and kids’ content for afternoon periods

Sports recap shows during low days to boost activity

5. Recommendations for Growing the User Base

Personalized recommendations using viewing behavior

Improved content discovery

Push notifications for new releases

Partner bundles (ISPs, mobile networks)

Referral-based growth campaigns

Reactivation campaigns for dormant users

🧰 Tools Used

Snowflake

Microsoft – Data review and visualization

PowerPoint – Final presentation design

Miro – Flow diagrams and insight mapping



