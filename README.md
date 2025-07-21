# coupons_acceptance

https://github.com/mgesteban/coupons_acceptance/blob/main/coupon_acceptance_analysis.ipynb
Data analysis project investigating factors that influence drivers' decisions to accept location-based mobile coupons for restaurants, bars, and coffee houses during various driving scenarios.

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

# Coupon Acceptance Analysis

## Executive Summary
This analysis reveals that **social context is the strongest predictor of coupon acceptance**, with acceptance rates increasing by 15-20% when drivers have passengers. Budget-conscious venues (restaurants <$20) show the highest acceptance rates (70%+), while bar coupons require careful targeting based on age, social context, and lifestyle factors.

## Key Findings
- Overall acceptance rate: 56.84%
- Best performing: Restaurant(<$20) coupons with friends (80.1% acceptance)
- Worst performing: Bar coupons with kids as passengers (<30% acceptance)
- Temperature and weather have minimal impact on acceptance decisions
