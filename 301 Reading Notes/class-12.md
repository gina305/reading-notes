# CRUD (Create, Read, Update, Delete)

## Status Codes Based On REST Methods
In your own words, describe what each group of status code represents:

* 100’s = Indicates informational status codes that tell the client that the header part of the request has been received and the server will try to respond to the client’s request. 
* 200’s = Indicates success codes that tell the client that its request was accepted.
* 300’s = Indicates redirection codes that tell the client that the resource they are requesting isn’t available at the expected location.
* 400’s =  Indicates a client error that means an invalid request was sent from a client to the server. 
* 500’s = Indicates a server error which means the server is overwhelmed or unreachable.

What is a status code 202?
* Code 202 indicates that the request has been accepted for processing, but the processing has not been completed.

What is a status code 308?
* Cod 308 indicates that the requested resource has been permanently moved to another URI.

What code would you use if an update didn’t return data to a client?
* Code 204 returns no content to the client.

What code would you use if a resource used to exist but no longer does? 
* Code 404 means 'resource not found', and applies to any entity for which a request was made but not satisfied. 

What is the ‘Forbidden’ status code?
* Code 403 issues a forbidden response that indicates that the server understands the request but refuses to authorize it.

______________________
Why do we need to pull our MongoDB database string out of our server and put it into our .env?
* This is so our credentials are not stored on the server. Also,this loads the database URL as an environment variable that we can use thoughout the server code. 

What is middleware?
* Middleware helps you with logging, error reporting, making asynchronous requests, and a whole lot more.

What does app.use(express.json()) do?
 * It is a built-in middleware function in Express that parses incoming requests that contain JSON payloads.

What does the /:id mean in a route?
* In a route, this indicates a parameter. A param is denoted by a colon :. In a route, the value of its params is stored in this.$route.params. 
What is the difference between PUT and PATCH?
* The PUT method uses the request URI to supply a modified version of the requested resource, whereas the PATCH method supplies a set of instructions to modify the resource.
How do you make a default value in a schema?
* In Mongoose, you can use the new Schema method to define default values.
What does a 500 error status code mean?
* Status code 500 is a generic server error response that indicates an unexpected condition that prevented it from fulfilling the request.
What is the difference between a status 200 and a status 201?
* Status code 200 means that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created 
