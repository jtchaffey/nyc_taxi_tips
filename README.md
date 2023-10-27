# nyctaxi
Predictive models of taxi fare tipping in New York City
Project conducted as part of Google Advanced Data Analytics Certification by Google on Coursera
This project was initially conducted using Jupyter Notebooks as part of the Google Advanced Data Analytics Certification curriculum, and is a copy of that notebook incorporating my own personal work. Because of this, formatting may present itself differently from other projects on GitHub, and this same project is available to view in its original form as a pdf on my LinkedIn profile under the title, "Activity_Course 6 Automatidata project lab".

**Overview**

This project made us of multiple linear regression and random forest model techniques to make predictions about taxi fares and tipping amounts from riders. Data was supplied by the New York City Taxi & Limousine Commission for yellow taxi cab rides taken during 2017. The final random forest model was evaluated to have an accuracy score of 71.2% and an F1 score of 74.8%, used from the goal of weighing precision and recall metrics equally. From a ranking of important ride features the most influential factors in predicting generous tipping behavior from taxi riders were the predicted fare amounts, travel distance, and travel duration.

**Business Understanding**

Use of predictive models like this would help to supplement wages for taxi drivers. Based on the income of taxi drivers coming in the form of gratuities, it would be beneficial to better understand factors that are able to help them earn the most money for their work.

**Data Understanding**

The data from the New York Taxi and Limousine Commission included information on over 22,000 rides and 18 features. These features included information such as pick-up and drop-off locations and times, the amount of passengers, trip duration and distance, toll information, and payment type. Feature engineering was used to separate rides based on the time of day they were taken, and encoding was used to qualify tip amounts as 'generous' or 'not generous', signifying that a tip met a threshold of 20% of the fare amount or not.

**Modeling Evaluation**

A random forest model using 100 decision trees was used to determine feature importances with regard to generous tipping behavior. Outside of the vendor identity, the predicted fare amount and ride distance were the two most notable features in determining generous rider gratuity. Ride duration was also rated as an important feature, but to a lesser extent.

**Conclusion**

Applications of the model will likely be beneficial to the income of taxi drivers by generating greater income through patron tips. However, the model still has more room for improvement based on its evaluation metrics. It may also be prudent for an additional model to be created which predicts tipping behavior based on individual riders and their past tipping behaviors, rather than features surrounding rides.
