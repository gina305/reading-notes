# APIs

1. What does REST stand for?
- REST stands for REspresentation State Transfer. It allows a server to react to CRUD (Create, Read, Update and Delete) requests between a client and a server.

REST APIs are designed around a resource.

2. What is an identifier of a resource? 
- A resource identifier is a URI that uniquely identifies that resource. Here is a an example of a resource: https://switchcode.com/blogs/1


3. What are the most common HTTP verbs?
- The most common HTTP verbs are GET, POST, PUT and DELETE.


4. What should the URIs be based on? 
- URIs should be based on nouns (i.e blog) not the request type (get-blog). 

5. Give an example of a good URI: https://switchcode.com/blogs


6. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- A ‘chatty’  API exposes a large number of small resources. This is a bad thing because multiple requests will be required to find all of the data required.

7. What status code does a successful GET request return?  200 (OK)

8. What status code does an unsuccessful GET request return?  404 (Not Found)

9. What status code does a successful POST request return?  400 (Bad Request)

10. What status code does a successful DELETE request return?  204 (No Content)