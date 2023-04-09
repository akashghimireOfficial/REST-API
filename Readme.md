# **Introduction to REST APIs**

In *REST API*, REST stands for *REpresentational State Transfer*, and *API* stands for *Application Programming Interface.*

## Application Programming Interface

Before learning about REST APIs, let us learn what APIs are.

*API* or Application Programming Interface is a a set of rules,protocols,and tools for building software applications. APIs makes it possible for different types of component such as Software, web-based services. 

The key component of API is an Interface. In simple words *Interface* can be said as the point of component between two components(Software, Web based server, or even hardware). And the way these component communicate with each other are govern by sets of API rules and protocol. 


*Local APIs* vs *Remote APIs*

Local APIs allow software and other application within a device to communicate with each other. One of the examples of it is "win32" APIs which allows communication between different software running in a window desktop. Here, in "win32" APIs, different *fucntions* acts as interface and bridge commnication between various devices. 

Remote APIs allow exchange of data and information betweeen componenet between two or more computers. One of the most popular API is web-based APIs. We used web-based APIs in our daily life activities. 

Let us take an example of me enjoying the "Youtube Videos" from my laptop. 

First, I open a browser, and type the url of the Youtube. The browser makes as HTTP request directly to Youtube server and I can see the website on my Laptop Browser.  Next, when i interact with the website and the browser needs to retrive information about vidoes, playlist, and other from the Youtube server.In this stage, browser makes API calls to Youtube server using *Youtube API.* Then the Youtube server makes response to the browser again using *Youtube API.* Here, *Youtube APIs* makes it easier for browser and youtube server to communuicate with each other. 


## REpresentational state Transfer(REST) APIs 

REST API is one of the popular web-based API architecture. The APIs following the REST API architectures are  called RESTful APIs. 

Criterias for a Remote API to be referred as RESTful API:

1. **Client-Server Architecture**:  RESTful API must involve "client" and "server". *Clients* make request, while the *Servers* response accordingly. 

2. **Statelessness**: RESTful API should not maintain state between requests.  This means the requests made by the client should not be stored in server. For example, using stateless protocol like *HTTP* for requesting the data from the server. 

3. **Cachebility**: Responses from a RESTful API should be cacheable; This allos clients to load frequently used data locally.

4. **Layered System**: RESTful API should be designed to operate in a layered system. Clients should only be exposed to the endpoints(resources) exposed by the server. Client do not need to know underlying infrastructure within the server. This makes it  easy to update and changed the API without effecting the clients. 

5. **Uniform Interface**: A RESTful API should have uniform interface, meaning that it should have consistent and well-defined resource representations, request/response structure amd standard error handling. This makes it easy for clients to understand and use of APIs. For example: Standard HTTP status codes such as *200(ok),404(Not Found).*  Another example is use of standard data formats such as *JSON or XML*, to represent resource and exchange data between client and server. 

