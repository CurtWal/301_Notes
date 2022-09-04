Friday August 2, 2022

In your own words, describe what each group of status code represents:

- 100’s = information codes
- 200’s = successfully loaded
- 300’s = redirection 
- 400’s = code errors
- 500’s = server errors

What is a status code 202?
- Accepted status code telling the client that the request was accepted but will be processed later


What is a status code 308?
- Permanent Redirect tells the client to use another url to access the resource


What code would you use if an update didn’t return data to a client?
- Code 204 No Content


What code would you use if a resource used to exist but no longer does?
- Code 404 Gone


What is the ‘Forbidden’ status code?
- code 403 the client has authorized but still has no permission to access the resource


Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- To store sensitive information 


What is middleware?
- functions that execute during the lifecycle of a request to the Express server.


What does app.use(express.json()) do?
-  It parses incoming JSON requests and puts the parsed data in req.


What does the /:id mean in a route?
- The direct location of the object it is referring to


What is the difference between PUT and PATCH?
- Put updates a ENTIRE resource with information from the request
- Patch updates a PART of a resource with information from the request


How do you make a default value in a schema?
- ex: Default : Data.now


What does a 500 error status code mean?
- It means that the server encountered an unexpected condition that prevented it from fulfilling the request.


What is the difference between a status 200 and a status 201?
- A status 200 means that the request was recieved and understood and is being processed.
- A status 201 means that a request was successful and as a result a resource has been created.

