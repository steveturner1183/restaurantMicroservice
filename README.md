## **Project Name**

Restaurant microservice

## **Project Description**

This microservice will take a location as an input and return an array 5 top restaurants in the area as JSON object. Price and address information are also included  

Return values:  

price - String - value in range from $ to $$$$
street - String - street number and name
city - String - city name
state - String - state name abbreviation, e.g. New York = NY

## **Requirements**

Python 3.9  
click 8.0.3
colorama 0.4.4
Flask 2.0.2
itsdangerous 2.0.1
Jinja2 3.0.2
MarkupSafe 2.0.1
Werkzeug 2.0.2

## **Usage Instructions**

**When this proejct was up and running, a request could be sent to: http://flip1.engr.oregonstate.edu:9797/search?city={your city here}&state={your state here}
Please note this is no longer operational and for display purpose only.**

The city name must include city and state to give the most accurate results. Spaces should be entered as % to pass to the url

Example:  

City = New York  
State = NY

http://flip1.engr.oregonstate.edu:9797/search?city=New%York&state=NY

Results will be returned in JSON format

rest_data["name"] = name
rest_data["price"] = price
rest_data["street"] = street
rest_data["city"] = city
rest_data["state"] = state