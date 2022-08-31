# CRUD

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

* 100’s = header renders but body will fail before start
* 200’s = Success codes, all validation requirements were met during time of send
* 300’s = Redirect codes, client must issue new request to redirect
* 400’s = client error codes
* 500’s = server error codes


1. What is a status code 202?
    * valid request process when ready

1. What is a status code 308?
    * permanent redirect, tells user not to use current link

1. What code would you use if an update didn’t return data to a client?
    * 204 No content

1. What code would you use if a resource used to exist but no longer does?
    * 308 Permanent Redirect

1. What is the ‘Forbidden’ status code?
    * client has no permission 

## REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
    * Its private information .env is hidden

1. What is middleware?
    * function that have access to request obbjects

1. What does app.use(express.json()) do?
    * allow acceptance of json

1. What does the /:id mean in a route?
    * That it is a parameter

1. What is the difference between PUT and PATCH?
    * Put is to update all patch updates whats needed

1. How do you make a default value in a schema?
    * default:

1. What does a 500 error status code mean?
    * Internal Server Error

1. What is the difference between a status 200 and a status 201?
    * Successfully created an object is 201. 200 is successful nothing more