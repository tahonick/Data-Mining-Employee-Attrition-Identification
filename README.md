# Employee Attrition Identification via Data Mining

Gallup states that attrition costs US companies at least one trillion dollars annually! We studied the publicly available IBM HR dataset, available via Kaggle to apply a variety of data mining methods to identify groups of employees most likely to leave the fictitious company.

## Our objectives for this project:

 - Study data for employees who both leave and stay to gain a better understanding of factors that contribute to attrition
 - Attempt to develop a reasonable strategy for companies to minimize attrition

## Goals and findings:

Understand which employees are leaving, in terms of characteristics and experiences
 - Logistic Regression was our best performing model and suggested the greatest predictor of an individual leaving included:
   - Eligibility for Overtime (i.e. Salary vs Hourly Employee)
   - Age
   - Marital Status
 - The data indicated younger, non-married, hourly employees tend to leave at greater rates than other individuals.

Predict which current employees are at risk of leaving
- We could apply these models to datasets of current employees to better predict what departments have the highest risk of employees leaving. While it would be difficult to hire only older, married, salaried individuals for future roles, there could be incentives such as stock options and other performance goals to entice high performing individuals to stay longer.
 - Correlation vs causality: Employees that were “Grandfathered in” in terms of benefits

How we might specifically retain top performers (i.e. Is there anything unique about them? Can we capture that extra cost in ourmodel?)
 - Current data states that 85% of employees received 3 out of 4 (“Excellent”) while 15% received 4 out of 4 (“Outstanding”).
 - Since there wasn’t great variability in performance rating, it is difficult to determine unique characteristics of top performers.
 - Either company is great at finding high performing individuals, or managers will have to assign scores differently (e.g. rankingsystem) to better identify true high performing individuals.

Determine which levers the company can use to reduce attrition going forward (particularly for top performers)
 - As we were unable to identify true top performers, we will have to rely on the characteristics discovered from the logistic regression model to best reduce attrition going forward for all employees.
