API - Application programming interfacing - rules and protocols on how can software interact with each other.

Restful API - apis that follow a set of rules.

A server is a computer (or part of a computer) where the data lives and where the processing happens.

 - Stores information

 - Runs code

 - Does the actual work

 - Like the “kitchen” in a restaurant

Think of it as the place where everything happens.

🧑‍🍳 API = The Rules / Menu / Waiter

An API is how you are allowed to talk to the server.

It decides:

 - what you can ask for

 - what format you must use

 - what the server will give back

API is like:

the menu (what requests are allowed)

the waiter (carries your request)

the rules (“you must order in this format”)


JSON (Javascript Object Notation) - its a way to format data that can  be sent over the internet in a readable way.


JS Object --> JSON

const jsonData = JS0n.stringify(data);


JSON --> JSObject

const data = JS0n.parse(jsonData)



FORMATTING API REQUEST - ENDPOINTS, PATH PARAMETERS AND QUERY PARAMETERS

Api Endpoint - BaseURL/Endpoint

Query Parameters - BaseURL/Endpoint?query=value

Multiple Query Parameters - BaseURL/Endpoint?query=value&query2=value

Path Parameters - BaseURL/Endpoint/{path-parameter}


-------------------

API AUTHENTICATION - authenticating yourself with the API provider.

Tiers
No Authentication
Basic Authentication - provide a username and password to the Api provider.
Api Key Authorisation - 
Token Based Authentication