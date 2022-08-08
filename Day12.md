
# CRUD 

## 1- In your own words, describe what each group of status code represents:

  100’s =These are informational status codes; they usually tell the client that the header part of the request has been received and
  the server will try to comply with a transmission demand of the client. Like using a different protocol or
  telling the client that its request will fail before they start sending the body.

  200’s = success and in some case it is mean all reqirement valid.
  300’s = informed the client that this resource is not available at the specific location.
  400’s = Invalid request from client . 
  500’s = it is often from server overhelmed or maybe down 

## 2- What is a status code 202? 
Ans : 202 Accepted - Often used for asynchronous processing.
This code tells the client that the request was valid, but its processing will finish sometime in the future
## 3- What is a status code 308?
Ans :300 Multiple Choices - This redirect is used if there are multiple representations for one resource and the client (or its user) 
has to choose one of them.
## 4- What code would you use if an update didn’t return data to a client?
Ans : 204 No Content
## 6- What is the ‘Forbidden’ status code?
Ans : 403 Forbidden


Why do we need to pull our MongoDB database string out of our server and put it into our .env? due to the sensitve information 
What is middleware? Ans : Middleware functions have access to the request object and the response object and also the next function in the application
request-response lifecycle.
What does app.use(express.json()) do? to allow the express accept JSON
What does the /:id mean in a route? paramt to specify the user by the ID 
What is the difference between PUT and PATCH? Patch update one Record , Put update all 
How do you make a default value in a schema?
You can set default values in the schema of certain components to replace null values retrieved from the data source.


What does a 500 error status code mean? QAns : it is often from server overhelmed or maybe down 
What is the difference between a status 200 and a status 201? 200the reques sucess , and 201 accept it 

#Usuful Link 
(Status Code )[https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/]
(express and Router)[https://www.youtube.com/watch?v=fgTGADljAeg&ab_channel=WebDevSimplified]

# Things I want to know more about
  Mongo DB
