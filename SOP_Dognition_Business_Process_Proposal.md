# Dognition Business Process Improvement Proposal

## Author: Ashma Poudel  
## Target Role: Business Analyst / Product Analyst  
## Tools Used: Tableau, SQL, Excel  

---

## 1. Executive Summary

This project analyzes user engagement behavior within Dognition’s freemium model to identify opportunities for improving test completion rates and stabilizing long-term growth.

While the Free Start model drives strong acquisition, behavioral data reveals significant early-stage drop-offs and inconsistent engagement patterns.

This proposal recommends operational and behavioral improvements to increase user retention and average tests completed per user.

---

## 2. Business Problem Statement

Dognition’s Free Start model successfully attracts users but does not effectively convert them into long-term engaged participants.

Key challenges identified:

- Sharp retention drop between Tests 7–10  
- Long engagement gaps leading to user churn  
- Revenue heavily dependent on promotional spikes  
- Low habit formation consistency  

👉 The core issue is **behavioral retention**, not acquisition volume.

---

## 3. Data Overview

- Dataset: 177,000+ test records  
- Key fields analyzed:
  - User ID  
  - Test completion sequence  
  - Enrollment type (Free vs Paid)  
  - Test timestamps  
  - Monthly growth trends  

Data was analyzed using Tableau to identify engagement patterns, drop-off points, and time-based behavior trends.

In addition, SQL was used to perform segmentation analysis to evaluate the impact of user characteristics on engagement behavior.

---

## 4. Analytical Approach

The analysis was conducted in four stages:

1. Test progression comparison between Free and Paid users  
2. Engagement gap calculation between consecutive tests  
3. Hourly engagement distribution analysis  
4. Monthly growth volatility assessment  

Behavioral trends were visualized to detect friction points in the user journey.

---

## 5. Key Insights

### Insight 1: Retention Cliff  
Free users experience a sharp drop-off between Tests 7–10, indicating friction before conversion.

### Insight 2: Engagement Consistency Predicts Completion  
Shorter testing gaps strongly correlate with higher completion rates.  
Consistent engagement significantly improves progression.

### Insight 3: Peak Usage Occurs Between 6–8 PM  
Evening engagement exceeds morning usage, suggesting post-work behavioral patterns.

### Insight 4: Growth is Promotion-Driven  
Growth spikes align with Free Start campaigns, indicating unstable organic retention.

---

## 6. Recommendations

### 1. Extend Free Momentum
- Increase free test access to 10–12 tests  
- Introduce pre-paywall streak rewards  
- Trigger upgrade prompts during peak hours  

### 2. Strengthen Habit Formation
- Implement 24-hour reminder notifications  
- Add “Continue Progress” prompts  
- Introduce consistency-based badge systems  

### 3. Stabilize Revenue Growth
- Reduce reliance on promotional spikes  
- Introduce mid-tier subscription model  
- Optimize referral prompts during peak engagement  

---

## 7. Implementation Roadmap

**Phase 1 (0–1 Month):**
- Adjust paywall trigger  
- Implement engagement reminders  

**Phase 2 (1–3 Months):**
- Launch streak reward system  
- Introduce time-based upgrade prompts  

**Phase 3 (3–6 Months):**
- Evaluate conversion uplift  
- Optimize pricing strategy  

---

## 8. KPI Tracking Framework

- Average tests completed per user  
- Retention rate between Tests 7–10  
- Average engagement gap (hours)  
- Conversion rate (Free → Paid)  
- Monthly recurring revenue stability  

---

## 9. Supporting Analysis (SQL)

SQL-based analysis was conducted to evaluate whether engagement differences are influenced by user attributes such as personality dimensions and breed types.

### Key Findings:
- Engagement is consistent across personality groups  
- Breed type shows minimal variation in test completion  
- No strong correlation between user traits and engagement behavior  

### Insight:
User engagement is driven more by product experience and behavioral design than by inherent user characteristics.

---

## Conclusion

Dognition’s growth challenge is behavioral rather than structural.

By shifting focus from acquisition spikes to habit reinforcement and strategic monetization timing, the platform can significantly increase user lifetime engagement and revenue stability.

This proposal outlines a data-backed roadmap for sustainable retention improvement.
