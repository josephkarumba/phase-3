## SYRIA TEL CUSTOMER CHURN
## project overview
The primary aim of this project is to delve into the intricate patterns of customer churn within Syria Tel, a prominent telecommunications entity 
operating in Syria. By meticulously analyzing various facets contributing to churn, the overarching objective is to discern underlying factors and 
trends driving customers to discontinue their services. Through a comprehensive understanding of these churn dynamics, the project endeavors to 
devise effective strategies aimed at curbing churn rates and fostering enhanced customer retention. By leveraging insights gleaned from the data 
analysis, the project seeks to identify pivotal touchpoints and influential variables that influence customer decision-making processes. This 
strategic approach not only aids in mitigating churn but also lays the groundwork for cultivating lasting customer relationships and fostering 
sustainable growth for Syria Tel in a competitive telecom landscape.

## Business problem
The business problem at hand revolves around customer churn within Syria Tel, a telecommunications company operating in Syria. Customer churn, 
or the rate at which customers discontinue their services, poses a significant challenge to the company's sustainability and growth. High churn 
rates can lead to revenue loss, reduced market share, and diminished customer loyalty. Therefore, the key business problem lies in understanding 
the underlying factors driving churn among Syria Tel's customer base. Without a clear understanding of these factors, the company risks losing 
valuable customers and facing increased competition in the telecommunications market. Hence, the imperative is to identify and address the root 
causes of churn to develop effective strategies that foster customer retention and ensure long-term business success.

## The Data
Our data consists of historical records pertaining to Syria Tel's customer base, encompassing various attributes and behaviors associated with 
telecommunications services. This dataset includes information such as 

state: The state in which the customer resides.
account length: The duration that the account has been active.
area code: The area code of the customer's phone number.
phone number: The phone number of the customer. This is the uniq identifier
international plan: Whether the customer has an international calling plan.
voice mail plan: Whether the customer has a voice mail plan.
number vmail messages: The number of voice mail messages.
total day minutes: The total number of minutes the customer has used during the day.
total day calls: The total number of calls the customer has made during the day.
total day charge: The total charges for the day minutes.
total eve minutes: The total number of minutes the customer has used during the evening.
total eve calls: The total number of calls the customer has made during the evening.
total eve charge: The total charges for the evening minutes.
total night minutes: The total number of minutes the customer has used during the night.
total night calls: The total number of calls the customer has made during the night.
total night charge: The total charges for the night minutes.
total intl minutes: The total number of minutes the customer has used for international calls.
total intl calls: The total number of international calls the customer has made.
total intl charge: The total charges for the international minutes.
customer service calls: The number of calls the customer has made to customer service.
churn: Whether the customer has churned that is left the service or not. This is the target variable.

## Objectives

Our objectives entail analyzing customer churn patterns within Syria Tel's telecommunications service to 
uncover influential factors driving attrition, developing predictive models to forecast churn, and evaluating 
model performance to ensure accuracy. By achieving these goals, we aim to provide actionable insights and recommendations 
to Syria Tel, empowering them to devise effective strategies for reducing churn rates, enhancing customer retention, and fostering 
sustainable business growth in the competitive telecommunications market.

## Model Results
The Random Forest model emerged as the most effective predictive model for forecasting customer churn within Syria Tel's telecommunications 
service.The classification report provides insights into the precision, recall, and F1-score of the model for both churn and non-churn classes, highlighting its effectiveness in identifying churn instances while minimizing false positives and false negatives.

## CONCLUSION

## Limitations

Overfitting: Without proper regularization techniques or hyperparameter tuning, Random Forest models is prone to overfitting, especially when dealing with noisy or high-dimensional datasets. Overfitting may result in the model capturing noise in the data rather than true underlying patterns, leading to poor generalization on unseen data.

Computational Resources: Training Random Forest model is computationally intensive, particularly with large datasets or when using a large number of trees and features. This pose constraints on computational resources and increase the time required for model training and evaluation.

Imbalanced Data: the dataset is highly imbalanced, with a disproportionate number of churned and non-churned instances, Random Forest models exhibit biases towards the majority class. This can affect the model's ability to accurately predict churn, particularly for minority classes.

## RECOMMENDATIONS

 1.continuously monitor customer churn patterns, evaluate the effectiveness of implemented strategies, and adapt approaches based on evolving market dynamics and customer feedback. Regularly reassess the predictive model's performance and refine it as new data becomes available to ensure its accuracy and relevance over time

 2.Implement personalized promotional offers and discounts tailored to individual customers, especially those identified as at-risk of churning based on the model predictions.

 3.Use insights from the model to send targeted ads and promotions to customers who are at risk of leaving, based on their behavior and preferences.

  4.Implement robust feedback mechanisms to gather insights directly from customers regarding their satisfaction levels, preferences, and pain points. Use this feedback to continuously improve services, address customer concerns, and adapt offerings to evolving customer needs.

