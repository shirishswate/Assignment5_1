# Will a customer accept the coupon? 

The goal of this project is to distinguish between customers/drivers who accepted a driving coupon versus those that did not, using visualizations and statistical summaries to reveal underlying patterns.

The data is sourced from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver.

**The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy**

[Link to notebook used](https://github.com/shirishswate/Assignment5_1/blob/main/prompt.ipynb)

## Data Summary

The dataset includes responses on five types of coupons: less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50). Each entry corresponds to a survey response indicating acceptance ("Y = 1") or rejection ("Y = 0") of the coupon in a given driving scenario.

![Distribution of Coupon Types](/plotimages/all_coupon_distribution.png)

## Methodology

- Used Pythonand seaborn for data plotting and statistical analysis
- Examined the distribution of coupon types and acceptance rates.
- Analyzed relations between acceptance rate  and visit frequency, customer age, passenger type, income and occupation.
- Generated visualizations to support findings and hypothesis.

## Key Findings

- Coffee houses coupons were accepted at a rate of 50.14%, and type of passanger does not have much impact of the acceptance rate.
- Coupon acceptance correlated with, higher visit frequencies to coffee houses as well as Bars, 
- Presence of friends or partners as opposed to presence of Kids has significant impact on Bar coupon acceptance rate.
- Younger customers (below age 30) are more inclined to accept coupons, especially when visiting coffee houses or Bars more than once a month.
- Customers/drivers are more likely to accpet coupons during warmer weather than colder weather.
- Low income customers who visit cheaper restaurants more than 4 times a month are moderatly likely to accept Bar or coffee coupons.

## Hypothesis

It can be concluded that customers who are young, frequently visit coffee houses or Bars , and are accompanied by peers ( except in case of Bar coupons when accompanied by Kids) are more likely to accept driving coupons. This demographic represents a key target for marketing strategies aimed at increasing coupon acceptance rates.

## Actionable Recommendations

- **Target Frequent Visitors**: Focus promotions on customers with frequent visiting habits.
- **Target young customers**: Target coupons to younger age groups.
- **Capitalize on Social Visits**: Focus coupon disribution during social outings with friends or partners.
- **Maximize during warmer weather**: Leverage high-acceptance period, particularly during warmer weather, for coupon offers.

## Next Steps

The next step is to develop a machine learning model to validate the hypothesis. This model can confirm the observations and work as a tool to design similar campaigns by predicting most effective patterns.

---

Please refer to the included Jupyter Notebook which includes all data visualizations and statistical analyses performed during the study.
