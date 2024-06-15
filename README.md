# App Subscribe Page A/B Test Project

## Test Hypothesis

- **Hypothesis 0 (Null Hypothesis):**
  There is no significant difference in the conversion rate between the original onboarding screen offering a weekly subscription at $4.99 and the alternative design offering the same subscription at a 50% discount. The percentage of users purchasing the subscription remains the same for both designs.

- **Hypothesis 1 (Alternative Hypothesis):**
  The alternative design with a 50% discount on the weekly subscription at $4.99 will result in a higher conversion rate compared to the original onboarding screen. Users presented with the discounted offer will be more likely to purchase the subscription than those presented with the original offer, indicating that the discount has a positive impact on user engagement and conversion.

## Test Description

We are going to test the impact of an alternative design on the conversion rate for the weekly subscription offer in our mobile application. The current onboarding screen presents users with a $4.99 weekly subscription, and 17% of users who receive this offer make a purchase.

The alternative design introduces a discounted offer, presenting the same $4.99 weekly subscription but with a 50% discount. We want to assess whether this discounted offer influences user behavior positively, leading to a higher CR (Conversion Rate) compared to the original design.

- **Daily User App Installations:** 2,000 users

## Scenarios for Testing

- **Control Group A:**
  The original onboarding screen is shown to users with the $4.99 weekly subscription price.

- **Experimental Group B:**
  The alternative onboarding screen is shown to users with the $4.99 weekly subscription offer and a 50% discount.

## Data Collection

- Collect data on the number of users in each group.
- Track the number of users who make a purchase in each group.
- Record additional metrics, such as user engagement, time spent on the screen, and any interactions with the subscription options.

## Expected Outcomes

1. If the null hypothesis is true, there will be no significant difference in conversion rates between the two groups.
2. If the alternative hypothesis is true, the experimental group with the discounted offer will show a higher conversion rate than the control group.

## Confidence and Potential Risks

- **Confidence:** 75%
- **Daily User Installations:** 2,000

### Potential Impact on Key Metrics: Medium/High

- **Positive Impact:** The discounted offer has the potential to positively impact the conversion rate for the weekly subscription, leading to increased revenue and user engagement.
- **Negative Impact:** There's a possibility that the discounted offer might devalue the product in the eyes of users, causing a negative impact on revenue if the increased conversion rate doesn't offset the reduced subscription revenue per user.

### Risks: Medium

- **User Perception Risk:** Offering a discount may influence users to expect discounts regularly, potentially affecting long-term revenue if users delay purchases anticipating future discounts.
- **Risk of User Misperception:** Users may discover that the actual subscription price remains the same despite the advertised discount. This could lead to a perception of deception or feeling misled, resulting in negative user sentiment and potential harm to the app's reputation.

## Affected Metrics

### Primary Metrics

- **Metric 1: Conversion Rate (installation to subscription)**
  - Current value: 5.78%
  - CR = 0.34 (CR installation to visit) * 0.17 (CR visit to subscription) * 100% = 5.78%

- **Metric 2: Revenue (daily revenue from subscriptions)**
  - Current value: $574

### Secondary Metrics

- **Metric 3: Daily Paid Users Number**
  - Current value: 115

## Statistical Significance

To be 95% sure in a 16% (relative) boost, we need a sample size of 10,216 users for each test group (20,432 total).

## Audience and Duration

To minimize potential risks, we plan to use 50% of daily users for this A/B test, evenly divided into two groups. Only new users will be used for this test.

- **Total Days:** 21 days
- **Group Names:**
  - Group A: Control group with the old Subscription screen - 10,000 users
  - Group B: Test group with 50% discount subscription screen - 10,000 users

## Potential Outcomes

- If at least one primary metric is up and others aren’t down, we’re implementing the new screen version.
- If at least one primary metric is down and others aren’t up, we’re not rolling out the new screen version.
- If there are no statistically significant outcomes from the test in terms of metrics, we are not implementing the new screen version.

## Conclusion

As seen from the chart below, there is a significant difference between the CR (mean) of the two groups. With a 95% confidence level, we can assume that the Alternative hypothesis is True. The onboarding screen with the $4.99 weekly subscription offer and a 50% discount increases conversions.

Additionally, the chart below shows the dynamic change in CR over time. Considering that the primary metric is up and others aren’t down, we are rolling out the new screen version with a 50% discount.
