## Data analysis project investigating factors that influence drivers' decisions to accept location-based mobile coupons for restaurants, bars, and coffee houses during various driving scenarios.

https://github.com/mgesteban/coupons_acceptance/blob/main/coupon_acceptance_analysis.ipynb



# Problem Statement

## Primary Question
**What factors determine whether a driver will accept a mobile coupon delivered to their phone while driving?**

## Specific Problem
When location-based coupons are delivered to drivers' mobile phones for nearby venues (restaurants, bars, coffee houses), we need to understand which factors influence their decision to:
- Accept and use the coupon immediately ("right away")
- Accept and use the coupon later (before expiration)  
- Reject the coupon entirely

## Business Context
While proximity triggers coupon delivery, acceptance rates vary significantly. Understanding the key drivers of acceptance behavior will enable more effective targeted marketing and higher redemption rates.

## Key Research Questions

### Analysis Framework

| Dimension | Factors | Research Questions |
|-----------|---------|-------------------|
| **User Profile** | • Age<br>• Gender<br>• Income<br>• Education<br>• Marital Status<br>• Children | How do demographic characteristics influence coupon acceptance rates? |
| **Venue Type** | • Restaurants <$20<br>• Restaurants $20-50<br>• Coffee Houses<br>• Bars<br>• Takeout | Which venue types have highest acceptance? How do they differ? |
| **Context** | • Weather<br>• Time<br>• Temperature<br>• Destination<br>• Passengers | What situational factors drive acceptance decisions? |
| **Behavior** | • Visit Frequency<br>• Dining Habits | Do lifestyle patterns predict coupon usage? |


## Executive Summary
This analysis reveals that **social context is the strongest predictor of coupon acceptance**, with acceptance rates increasing by 15-20% when drivers have passengers. Budget-conscious venues (restaurants <$20) show the highest acceptance rates (70%+), while bar coupons require careful targeting based on age, social context, and lifestyle factors.

## Key Findings
1. Overall acceptance rate: 56.84% - Over half of the users accepted the coupon (56.84%), which is a positive indicator. It suggests that the coupon offer is generally appealing or effective to a majority of the audience in this dataset.
2. People traveling with friends (not with kids) are most likely to accept the coupons.
3. Those people earning below $50K will most likely accept the coupons.
4. Coffee House coupons show the highest volume (approximately 4,000 observations), making them the dominant promotional vehicle in this dataset.
5. The analysis reveals a strong positive correlation between temperature and coupon acceptance rates, with acceptance increasing steadily as temperatures rise—showing approximately 7 percentage points higher acceptance at 80°F compared to cooler temperatures of 30°F or 55°F. This pattern suggests that warmer weather encourages more spontaneous purchasing behavior and increased mobility, with people being more receptive to impromptu outings and purchases. The trend aligns particularly well with the dominance of Coffee House coupons in the dataset, as hot weather naturally drives demand for cold beverages like iced coffees and frappes, while also motivating people to seek out air-conditioned indoor spaces that cafes provide for social breaks and leisure activities. Conversely, cooler temperatures (30°F and 55°F) show similar, lower acceptance rates, indicating that cold weather reduces people's willingness to venture out for non-essential purchases, thereby decreasing overall coupon redemption rates across food and leisure categories.
6. Males have a slightly higher acceptance rate than females — a difference of ~3.8%.
7. Users who go to bars more than 3 times/month have a significantly higher acceptance rate (62.25%).
8. Drivers who to to bars more than once and with passengers who are not a kid(s) are high-value segment for promotional campaigns.


## Recommendations
Based on the analysis, the overall coupon acceptance rate of 56.84% is encouraging, indicating that the offers are broadly appealing. However, deeper segmentation reveals key patterns that can enhance marketing effectiveness. Social context and user demographics are strong predictors of acceptance—people traveling with friends or partners are more likely to redeem coupons than those traveling alone or with children. Similarly, users with incomes below $50K demonstrate higher acceptance, suggesting that cost-conscious consumers are more responsive to discounts. Among coupon types, Coffee House promotions stand out, not only for their volume but also because they align well with warm weather trends and social habits, particularly in warmer temperatures where acceptance peaks at 80°F. This supports targeting spontaneous, weather-sensitive outings with Coffee House or casual dining offers.

Further analysis reveals that frequent bar-goers (more than 3 visits per month) are substantially more likely to accept coupons, with acceptance rates climbing to 62.25%. This trend is even more pronounced (up to 71.32%) among individuals who also travel with adults (not kids) and work in professions outside of farming, fishing, or forestry. These users represent a high-value segment for campaign targeting, as their lifestyle and context suggest both higher social engagement and greater likelihood of using discounts during outings. To optimize campaign performance, marketing efforts should focus on socially active, working-age adults, especially in warmer seasons, with messaging tailored to their routines and preferences—such as quick coffee breaks, after-work socializing, or casual bar visits.
