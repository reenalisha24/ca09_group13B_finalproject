# ca09_group13B_finalproject
# Executive Summary
Our goal is to utilize city-specific data available on airbnb to predict what a night for a 4-night booking for 
two people in a private room in Rio de Janeiro is likely to cost. 
For this, we created a regression model, first by handling data and understanding it, 
then by finding the most significant and predictive variables for our aims, building multiple models and comparing them.

The final model used to predict our stay in a [specific private room accommodation in Rioˈs Copacabana neighbourhood](https://bit.ly/3lJM4eK) 
predicted a price of BRL 123, and indicated a 95% certainty for the price to be within the range of BRL 41 to BRL 361, 
whereas the real price asked was c. BRL 250.

The model achieved to explain 43% of movements in price for the said AirBnB accomodations in Rio De Janeiro by looking at 9 different influencing variables:
- First, the number of reviews for an accommodation is considered.
- Then, the score rating from 1 to 5 for the accommodation is taken into account.
- It is then controlled for whether the accommodation is a private room, a hotel room, or a shared room.
- Further, the model considers whether a room is hosted by an AirBnB "superhost" or not.
- Additionally, it is significant to predict the price whether an accommodation is immediately bookable, or if a request to book has to be made prior.
- Also, the differentiation of whether the accommodation is available for 30 days is made.
- In addition to the review criteria above, the number of reviews an accommodation receives in a given timeframe helps to explain the price.
- The number of bedrooms further is significant in predicting the price of an accommodation.
- Lastly, the neighbourhood the accommodation is in significantly affects the price it will be offered for.
