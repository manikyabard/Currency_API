# Currency APIs
## This project is created to show how to use various APIs for getting the needed data.
### Questions faced while making the project.
#### What is an API?
	In basic terms, APIs just allow applications to communicate with one another.

	When people speak of “an API”, they sometimes generalize and actually mean “a publicly available web-based API that returns data, likely in JSON or XML”. The API is not the database or even the server, it is the code that governs the access point(s) for the server.
#### What is an Access key?
	An API access key is a unique code that is passed in to an API to identify the calling application or user. API keys are used to track and control how the API is being used, for example to prevent malicious use or abuse of the API. The API key often acts as both a unique identifier and a secret token for authentication, and generally has a set of access that is specific to the identity associated with it.
#### Where to get APIs for different task?
	For the purpose of this project, or any other, APIs can be found on rapidapi.com which is one of the best sites for providing APIs for a large number of use cases.
#### I have selected my API. How do I use it in my project?
	After selecting your API, 
#### The Libraries used in this project are _requests_ and _json_.
#### requests:
	This has been used to get the data from an API call using the get function.
#### json:
	This has been used to parse the string data to json format for easily manipulating and accessing whatever is needed.
### A description of the functions defined:
#### convs( base , target )
	this function converts 'base' currency to 'target' currency
	An API call is made from which the rate of the 'target' currency is printed
#### listconv( base )
	this function takes a currency symbol and returns a list of corresponding symbols and values for all currencies
#### conv_country( base , country )
	this function converts base currency to a currency of any Country specified
## API sources:
---
####	https://fixer.io/dashboard
####	https://rapidapi.com/
---
