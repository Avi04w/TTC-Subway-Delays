Toronto Subway Delay Analysis: Causes, Timing, and Line-Specific
Patterns
================
Avi Walia
March 10, 2025

# Introduction

The Toronto Transit Commission (TTC) subway system is a critical part of
Toronto’s public transportation network, servicing over a million riders
daily across multiple lines. However, subway delays have been a
persistent issue, impacting the efficiency and reliability of the
service. Understanding the primary causes of these delays and how they
vary by time of day and across different subway lines is essential for
improving service quality and enhancing passenger experience.

This study aims to investigate the following questions:

1.  What are the primary causes of subway delays in Toronto?
2.  How do these delays vary by time of day and subway line/station?

**Hypothesis:**

- **Hypothesis 1:** Mechanical issues are the most common causes of
  subway delays in Toronto.
- **Hypothesis 2:** Delays are more frequent during peak hours (7-9 AM
  and 4-6 PM) compared to non-peak hours.
- **Hypothesis 3:** The Yonge-University line experiences more frequent
  delays than other lines due to higher passenger volumes and longer
  track lengths. Bloor-Yonge and Union stations will have the most and
  longest delays on this line since they are the most crowded stations
  in terms of ridership.

To address these questions and test the hypotheses, we will utilize the
TTC subway Delay Data provided by the City of Toronto’s Open Data
portal. The dataset contains detailed information on delay incidents for
the year 2024, including:

- **Delay Codes**
- **Time Stamp Information** such as date, time, and day of the week
- **Location Details** including the station and subway line affected
- **Duration of Delays** measured in minutes

There is also another data set that includes metadata explaining the
description of each delay code.

The data was acquired using the City’s Open Data API. By exploring and
analyzing this dataset, we seek to identify patterns and trends in delay
causes, assess peak times for delays, and determine if specific lines
and/or stations are more prone to certain types of delays. This analysis
will inform potential strategies for mitigating delays and improving the
TTC’s operational efficiency.
