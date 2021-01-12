# API

APIs are one of the most significant parts of software development, every developer must be well versed with them. I have been working as a golang backend engineer for about a year now, have constructed plenty of APIs for various projects.

Recently, I came through an interesting session on APIs at <a href="https://www.crio.do/">Crio: Learn by Doing</a> and am sharing its notes with DevCommunity. Let's get it started!

<hr>

# What is an API?

API stands for **Application Programming Interface**, is a set of functions that allows applications to access data and interact with external software components, operating systems, or microservices.

<img src="https://user-images.githubusercontent.com/26124625/104198884-ca1bcf80-544c-11eb-94d1-22548426ad4d.png"></img>

In simple words, an API is like a waiter in a restaurant. You don’t go into a cafe and walk straight into the kitchen to tell the chef what you wanna eat. The waiter does that for you, and that’s exactly what an API is - with the client being you, the customer, and any resource that can send data, being the chef.

<hr>

# Benefits of using APIs

- **Security**: While using an API, client-side and server-side application works independently, and they communicate through API, so if anyone tries to hack into the client-side app, the server stays unaffected and secured.

- **Flexibility**: APIs allow content to be embedded from any site or application more easily. For e.g. an API written in GO can be used by Node.js/Django.

- **Efficiency**: When access is provided to an API, the content generated can be published automatically and is available for every channel. It allows it to be shared and distributed more easily.

- **Innovation**: With an API, an application layer can be created which can be used to distribute information and services to new audiences which can be personalized to create custom user experiences.

<hr>

# REST API

REST stands for **Representational State Transfer**, it is the most popular web API architecture. They follow a client-server model where one software program sends a request and the other response with some data.

<img src="https://user-images.githubusercontent.com/26124625/104197485-16fea680-544b-11eb-8aaa-d2bd74bf207a.png"> </img>

These APIs generally receive a response in **JSON** format, it's a standard format that is easily "understandable" by applications and can be handled well in most languages. For e.g. Ruby app can easily use JSON response from Java sever.

<img src="https://user-images.githubusercontent.com/26124625/104204412-431e2580-5453-11eb-9827-29a65aa6ff82.png"></img>

JSON stand for **JavaScript Object Notation**, it is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. Read more about it <a href="https://www.json.org/json-en.html"> here </a>

> There are several other forms of APIs (SOAP, XML-RPC, JSON-RPC, etc.), we'll limit our discussion to REST only. For more info, <a href="https://stoplight.io/api-types/"> Click here</a>

<hr>

# REST != HTTP

A lot of people prefer to compare HTTP with REST. REST and HTTP are not same.

In the REST architectural style, data and functionality are considered resources and are accessed using Uniform Resource Identifiers (URIs). The resources are acted upon by using a set of simple, well-defined operations. The clients and servers exchange representations of resources by using a standardized interface and protocol – typically HTTP.

Resources are decoupled from their representation so that their content can be accessed in a variety of formats, such as HTML, XML, plain text, PDF, JPEG, JSON, and others. Metadata about the resource is available and used, for example, to control caching, detect transmission errors, negotiate the appropriate representation format, and perform authentication or access control. And most importantly, every interaction with a resource is stateless.

<hr>

# API Requeset & Response

REST API request generally consists of Method, Body(auth and other parameters), and Host. Here is a sample request that I have been working on recently.

<img src="https://user-images.githubusercontent.com/26124625/104276950-e9a60d00-54cb-11eb-84d5-efc4b4202e2e.png"></img>

As stated earlier, REST API responses generally in JSON format. Here is a sample response to the above API requests. 

**Note**: To get a similar response from the previous request, you'll have to add an API key: and API secret.

<img src="https://user-images.githubusercontent.com/26124625/104276947-e874e000-54cb-11eb-8a62-d5f0614f236e.png"></img>

<hr>

> For more information, goto <a href="https://restfulapi.net/"> reastfulapi.net </a>

I hope you have a good understanding of APIs now. If this article helped you, support it, and share it among your peers.

Connect with me: <a href="https://linkedin.com/in/anubhavitis"> LinkedIn </a>|<a href="https://twitter.com/anubhavitis"> Twitter </a>|<a href="https://github.com/anubhavitis"> GitHub </a>

#### Happy Coding!