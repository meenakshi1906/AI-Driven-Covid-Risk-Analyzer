# AI-Driven-Covid-Risk-Analyzer
IBM GRM Project

Topic: How AI can solve some of the problems posed by Covid.

It’s impossible to contain covid-19 without knowing who’s infected, until a safe and effective vaccine is widely available. If we combine machine learning with test pooling, large populations can be tested weekly or even daily, for as low as Rs220 to Rs370 per person. Infrequent testing (monthly seems to be the default in many proposals) or haphazard screening allow active cases to spread the virus for weeks before it’s caught. And the price is still high at around Rs1000 per test. Pooled testing, guided by machine-learning algorithms, can fundamentally change this calculus. In pooled testing, many people’s samples are combined into one. If no virus is detected in the combined sample, that means no one in the pool is infected. The entire pool can be cleared with just one test. But there’s a catch; if anyone in the pool is infected, the test will be positive and more testing will be required to figure out who has the virus. Machine learning can give us the precise individual-level estimates we need to make pooling work, by identifying those likely to test positive and keeping them out of large pools. Such groups of risky and non-risky participants can be made based on the following factors that can be fed into the machine learning algorithm:

Occupation (for example, healthcare workers and policemen are more prone)
Residential location
Workplace location
Patients with obvious symptoms
Travel history
Whether participant has been in close contact with positively tested person or not.
Immunity level from previous hospital records.
Blood Type (Once researchers have established evidence that people with type O blood have lower risk)

# Our Solution
We use the AI Watson Assistant to ask the participant for the following information and save it on a database on IBM cloud. An additional column calculates the total score gathered by each participant which then decides what risk level group they get admitted to. The score for Travel, Residential and Workplace locations are calculated with the help of machine learning. The AI compares the user’s input with that of up to date covid hotspot locations from online sources to decide how risky the location is. The occupations are also given particular score based on risk factor with the help of online data. The three risk level groups can be used by hospitals to apply one of the strategies described earlier and can help save time and cost per test kit.

# Covid Risk Analyzer Project link
(Remember to use only locations of districts of Southern Kerala. Due to limitations of IBM Cloud Trial plan we could not outsource to locations around the entire country.)

https://covid-risk-analyzer-node.eu-gb.mybluemix.net/ui/#!/0?socketid=SnyG-fM8KekV8rAPAAAi

# Demo Video
https://www.youtube.com/watch?v=FxsSVuUYuzc&list=PLnf9A2PCWDDTsdnbhqM3CzW4OZEoLW801&index=2&ab_channel=CyrilShaji

# Prepared by Team T853

Cyril Shaji

Kuriachen Sunil

Chandichen Sunil

Meenakshi Sajeev
