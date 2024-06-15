# A/B Test for Subscription Page Design

## Project Description

### Hypothesis

- **Null Hypothesis (H0):**
  There is no significant difference in the conversion rate between the original onboarding screen offering a weekly subscription at $4.99 and the alternative design offering the same subscription at a 50% discount. The percentage of users purchasing the subscription remains the same for both designs.
  
- **Alternative Hypothesis (H1):**
  The alternative design with a 50% discount on the weekly subscription at $4.99 will result in a higher conversion rate compared to the original onboarding screen. Users presented with the discounted offer will be more likely to purchase the subscription than those presented with the original offer, indicating that the discount has a positive impact on user engagement and conversion.

### Test Description

We conducted an A/B test to evaluate the impact of an alternative subscription page design on the conversion rate in a mobile application:

- **Original Design (Control Group A):**
  Users were shown the standard onboarding screen with a $4.99 weekly subscription offer.
  
- **Alternative Design (Experimental Group B):**
  Users were presented with the same $4.99 weekly subscription offer but with a 50% discount.

### Key Metrics

- **Sample Size:**
  - Control Group A: 10,013 users
  - Experimental Group B: 9,985 users

- **Conversion Rates:**
  - Control Group A: 6.10%
  - Experimental Group B: 8.90%

- **Test Duration:**
  The A/B test was conducted over 22 days, from July 3rd to July 25th, 2023.

### Statistical Analysis

- **Distribution Testing:**
  - The average conversion rate was compared between Control Group A (6.10%) and Experimental Group B (8.90%).

- **Hypothesis Testing:**
  - Chi-squared test and permutation test confirmed that the difference in conversion rates between the two groups is statistically significant (p < 0.05). The null hypothesis was rejected, indicating that the alternative design with a 50% discount led to a higher conversion rate.

### Visualizations

- **Distribution of A/B Groups:**
  - KDE plots and histograms visualizing the distribution of conversion rates in Control Group A and Experimental Group B.

- **Conversion Rate Comparison:**
  - Bar plot with 95% confidence intervals comparing the mean conversion rates between the two groups.

- **Cumulative Conversion Rate:**
  - Line plot showing the cumulative conversion rate change over time for Control Group A and Experimental Group B.

### Conclusion

Based on the results and statistical significance:
- The alternative subscription page design with a 50% discount significantly increased the conversion rate compared to the original design.
- We recommend implementing the new screen version to maximize user engagement and revenue.
