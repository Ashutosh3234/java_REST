
#     JAVA REST API

Problem statement:

Implement an application in java which provides a REST API with endpoints for searching, creating and deleting “server” objects:

● GET servers. Should return all the servers if no parameters are passed. When server id is passed as a parameter - return a single server or 404 if there’s no such a server.

 ● PUT a server. The server object is passed as a json-encoded message body. Here’s an example: { “name”: ”my centos”, “id”: “123”, “language”:”java”, “framework”:”django” }

● DELETE a server. The parameter is a server ID.
 
● GET (find) servers by name. The parameter is a string. Must check if a server name contains this string and return one or more servers found. Return 404 if nothing is found. “Server” objects should be stored in MongoDB database. Be sure that you can show how your application responds to requests using postman, curl or any other HTTP client.


# Software's Used

- Spring Tool's(developing Spring Framework-based applications)

- Postman(to write functional tests, integration tests, regression tests, and more)

- MongoDB(for database)

## About spring tool's 

An Application Programming Interface (API) establishes a connection between computers or between computer programs (applications) by providing readily available codes and information pipelines. 

It is a type of software interface that acts as a mediator among other pieces of software to streamline the interaction with one other.

Owing to diverse application architectures, different types of APIs such as Program, Local, Web, or REST APIs assist developers in building robust digital solutions.

Representational State Transfer, also known as REST, is basically a standardized Software Architecture Style, or in simple words, a specific type of API used by the industry to establish a connection between Client and Server. 

REST API is built to guide the development and design of the World Wide Web’s architecture.

REST APIs provide a flexible, lightweight way of integrating computer applications. REST APIs are a simple and standardized approach to communication, which means we don’t have to worry about how to format your data, it’s all standardized and industry use.

REST APIs are scalable as well, which means as your service scales, you don’t have to worry about the growing complexity. 

we can easily make modifications to your data and keep track of that across Clients and Servers. 


## Creating project with spring tool's

Let’s create a simple spring application where we will implement standard MVC controller as well as REST controller. Create a “Demo” in Eclipse and then convert it to Maven project. 

This will provide us with maven based web application structure and we can build our application on top of it. Below image shows the final project structure of our Spring MVC Controller application.

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/d1.png?raw=true)

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/d2.png?raw=true)

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/d3.png?raw=true)



## Using postman with spring tool's (output)

GET:

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/postman%203.png?raw=true)


POST:

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/postman2.png?raw=true)


PUT:

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/postman2.png?raw=true)




# mongoDB server

![Login](https://github.com/Ashutosh3234/java_rest/blob/main/mongodb1.png?raw=true)



