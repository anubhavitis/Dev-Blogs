# HTTP fundamentals

I have been working as a golang backend engineer for about a year now, have been playing with HTTP response and requests on daily basis. Understanding HTTP is the core of application development, and every developer should be crystal clear with them.

Recently, I came through an interesting session on HTTP at Crio Winter of Code and am sharing its notes with DevCommunity. Let's get it started!
<hr>
# What is HTTP?

HTTP stands for HyperText Transfer Protocol. It is, like the name suggests, a set of rules for querying the web.

As we humans communicate with each other through a common language following a set of grammatical rules. On the web, clients and servers communicate through requests and responses, that follow a set of rules called HTTP.

<img src="https://user-images.githubusercontent.com/26124625/104128631-ca559580-538e-11eb-8c01-ea90185db2eb.png"> </img>

The client makes an HTTP request that contains methods, headers, body, etc., and when the server receives that request, it responds to the client with an HTTP response that contains status, headers, body, etc.
<hr>
# HTTP Methods

<img src="https://user-images.githubusercontent.com/26124625/104128717-30dab380-538f-11eb-8a88-832f746f164c.png"> </img>

Like our language has different kinds of statements(Interrogative, Informative, Imperative, etc.), there are several types of HTTP methods of clients requests with specific roles. Some of the most important methods are:
- GET
- POST
- PUT
- DELETE

###  GET
GET methods are the HTTP requests which a client makes to a server for getting resources from the server. For e.g whenever you open Google.com in your browser, it makes a GET request to google's server.

### POST
POST methods are the HTTP requests which a client makes to a server for sending new data to a server. For e.g. when you do add a tweet, your application makes a POST request to twitter's server that contains data about your tweet

### PUT
PUT methods are almost like POST methods, instead of adding information to a server, they are intended to update existing information on the server. For e.g. when you change your profile pic on Twitter, your application makes a PUT request to twitter's server that contains a new image that'll replace your old image.

### DELETE
DELETE methods are the HTTP requests which a client makes to a server for deleting the existing data from the server. For e.g. whenever you delete a tweet on Twitter, your application makes a DELETE request to Twitter for deleting your tweet from its database.

> There are more HTTP methods, but we'll limit our discussion till here only. Click <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods"> here </a> to learn more.
<hr>
# HTTP status codes

<img src="https://user-images.githubusercontent.com/26124625/104128716-2fa98680-538f-11eb-9bb6-2ee610f46f03.png"> </img>

HTTP Status codes are part of the HTTP Response. It helps the client understand what happened to the request. It's 3 digits numeric code(like 404, 502), which have an appropriate definition in HTTP bias, A reason phrase is also returned along with it. For eg. 404: Page not found!

There are 5 types of HTTP status codes based on starting digit:
- 1xx: Information Responses
- 2xx: Successful Responses
- 3xx: Redirect Responses
- 4xx: Client Errors
- 5xx: Server Errors
> check more about various status codes <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Status" > here </a>.
<hr>

# How to make an HTTP request?

Instead of your browser, there are several other ways to make HTTP requests and accept responses from servers, these are incredibly useful for developers to test their applications before deploying. We'll look into 2 most popular way of making HTTP requests:
- Using CLI
- Using GUI

### Making HTTP requests with CLI

cURL is like a web-browser, but for the command line. Use <a href="https://curl.haxx.se/download.html" > this link</a> to download and install cURL in your machine. You can follow <a href="https://www.geeksforgeeks.org/curl-command-in-linux-with-examples/"> this tutorial </a> to understand how to use cURL commands to make HTTP requests.

### Making HTTP requests with GUI

There is various software that is available for making HTTP requests, You can use anyone. PostMan is one of the most famous apps for it, you can install it on your machine using <a href="https://www.postman.com/downloads/"> this link</a>.

<hr>

I hope you have a good understanding of HTTP basics now. If this article helped you, support it, and sharing among your peers.

#### Happy Coding!
