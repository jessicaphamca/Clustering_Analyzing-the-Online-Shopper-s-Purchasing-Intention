# Website Visitor Behavior Analysis

## Introduction
This project analyzes website visitor behavior using various data analysis techniques, including univariate, bivariate, clustering, and hypothesis testing. The goal is to uncover key insights about traffic patterns, engagement levels, and conversion rates, and provide actionable recommendations to optimize website performance and improve user experience.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Data Summary](#data-summary)
4. [Univariate and Bivariate Analysis](#univariate-and-bivariate-analysis)
5. [Clustering Analysis](#clustering-analysis)
6. [Hypothesis Testing](#hypothesis-testing)
7. [A/B Testing](#ab-testing)
8. [Key Insights](#key-insights)
9. [Conclusion](#conclusion)
10. [Recommendations](#recommendations)

## Project Overview
This project explores the behavior of website visitors based on various metrics such as traffic type, visitor type, browser usage, operating systems, and revenue generation. Clustering analysis is used to segment users into groups, followed by hypothesis testing and A/B testing to validate these findings and optimize the website experience.

## Data Summary
The data consists of various features such as:
- **Traffic Type**: Identifies different traffic sources.
- **Weekend Visits**: Whether the user visited during a weekend.
- **Visitor Type**: Whether the visitor is a returning user or new.
- **Revenue**: Whether the visit resulted in a purchase.
- **Geographical Regions**: Identifies different regions contributing to traffic.
- **Browser and Operating Systems**: Most commonly used browsers and operating systems.

## Univariate and Bivariate Analysis
- **Traffic Type**: Traffic Type 2 has the highest number of visitors, followed by Types 1, 3, and 4.
- **Weekend Visits**: More traffic on weekdays than weekends.
- **Visitor Type**: Returning visitors outnumber new visitors, indicating user retention.
- **Revenue Conversion**: The website has a conversion rate of 15.47%.
- **Geographical Patterns**: Region 1 and Region 3 account for over 50% of the total traffic.
- **Browser and OS Usage**: Browser 2 and OS 2 drive the majority of traffic.
- **Page Visits**: Administrative pages are frequently visited, particularly page 0.
- **Special Days**: Special Days show no significant impact on visitor numbers.
  
## Clustering Analysis
We used K-means clustering to segment users into 3 clusters:
- **Cluster 0**: Moderately engaged users.
- **Cluster 1**: Low engagement, high bounce users.
- **Cluster 2**: Highly engaged, high-value users.

## Hypothesis Testing
ANOVA was conducted to determine if the differences between clusters for specific features, such as ExitRates, were statistically significant. The p-values indicate significant differences between the clusters.

## A/B Testing
A/B testing compared two versions of the website based on BounceRates, ExitRates, and ProductRelated_Duration:
- **Version B** outperformed Version A, showing lower BounceRates, ExitRates, and higher ProductRelated_Duration.

## Key Insights
- **ExitRates** emerged as the most important feature for distinguishing user engagement levels.
- **BounceRates and ExitRates** were highly correlated (0.91).
- **ProductRelated_Duration** was significantly longer in Version B, indicating higher user engagement.
  
## Conclusion
The clustering analysis and hypothesis testing revealed important user segments. Version B of the website was statistically proven to offer a better user experience, with reduced bounce rates and higher engagement metrics.

## Recommendations
- Deploy **Version B** of the website to a larger audience, as it reduces both BounceRates and ExitRates while increasing ProductRelated_Duration.
- Focus on optimizing user experience for **Traffic Type 2** and **OS 2**, as they drive the most visitors and conversions.
- Consider strategies to convert more of the returning visitors into paying customers to increase the overall conversion rate.

For more details, refer to the project’s GitHub repository [here](https://github.com/jessicaphamca/Website-Visitor-Behavior-Analysis/blob/main/Website_Visitor_Behavior_Analysis.ipynb).

