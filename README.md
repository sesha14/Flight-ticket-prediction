# Flight-ticket-prediction
The purpose of this project is to think about how aircraft ticket costs change after some time, remove the elements that impact these variances, and depict how they're associated (basically surmise the models that air bearers use to value their tickets). At that point, utilizing that data, construct a framework that can help buyers settle on buying choices by anticipating how air ticket costs will advance later on.
Airline carriers execute dynamic valuing for their tickets, and base their estimating choices on request prediction models. The explanation behind such a complex framework is, that each flight just has a set number of seats to sell, so aircraft need to manage the request. 
For the situation where the request is relied upon to surpass the limit, the carrier may build costs, to diminish the rate at which seats fill.
Then again, a seat that goes unsold speaks to lost income, and selling that seat at any cost over the administration cost for a solitary traveler would have been an increasingly best situation. 

Data Details
The collection of information is the most significant part of this project. There are different sources of information on various sites that are utilized to prepare the models. These websites give data about the numerous routes, times, carriers and
fares. 
Different sources from APIs to buyer travel sites are accessible for information scraping.
There are sure features that would be extremely helpful in training a prediction algorithm, yet which the air-carriers, because of their competitive condition, don't
discharge to the general population. 
This incorporates the real number of accessible seats on a flight, the dispersion of ticket buys over the lifetime of passage and finegrained marketing projections. Likewise, the openly accessible admission information
does exclude specific sorts of tickets, as a consolidator and corporate tickets, which 
are consulted in private with the aircraft. 
At long last, some ease aircraft don't distribute their rates on the booking frameworks, and are accordingly not filed by most
online frameworks. 
Thus, for this project we have gathered dataset from Analytics India website which consist data of air carriers from India.

Feature Selection
We have a dataset of flight details with eleven different features. The size of the training dataset is 10,683 records. At first we are going to train the models using this
training dataset. 
After this, we are going to test the models which perform well with a
test dataset that has 2671 records.

Features we have:
• Airline: The name of the airline. Depending on the company of the airline the
fare prices changes.
• Date of Journey: Date of journey is essential feature to predict the flight ticket
value as in peak period many people prefer to travel for example in Christmas
vacation people travel to different part of the world
• Source: Location from where flight is departing is determining factor to predict
fare
• Destination: The destination where the service ends
• Route: The route was taken by the flight to reach the destination.
• Dep Time: The time when the journey starts from the source.
• Arrival Time: Time of arrival at the destination.
• Duration: Total duration of the flight. This is one the important feature as
based on time duration flight tickets changes. For example for smaller
duration of flight tickets are cheaper and vice versa.
• Total Stops: Total stops between the source and destination. Lesser the
stops higher the price.
• Price: The price of the ticket
