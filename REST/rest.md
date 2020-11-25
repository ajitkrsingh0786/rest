# REST ARCHITECTURE
REST stands for REpresentational State Transfer. It is not a specification it is a software architectural style or design that defines the set of rules to be used for creating web services and uses HTTP Protocol. It allows requesting systems to access and manipulate web resources by using a uniform and predefined set of rules.

![Markdown Logo](https://www.tutorialride.com/images/software-architecture-and-design/two-tier-client-server-architecture.jpg)

The source(i.e server) and client are the major part of the REST architecture. 
Source simply provides access to resources and the client accesses and modifies the resources.
> ## Most commonly HTTP methods used in REST-based architecture are:
1. **GET** − It provides read-only access to a resource.
1. **POST** − It is used to create a new resource.
1. **DELETE** − It is used to remove a resource.
1. **PUT** − It is used to update an existing resource or create a new resource.

> ## Principle of RESTful API:
There are six principles:
* Stateless
* Client-Server
* Uniform Interface
* Cacheable
* Layered System
* Code on Demand

### **Stateless**
When the request is sent from the client to the server it contains all the information required to make the server understand it. So it can be a part of the URL or query string parameter or body or headers. URL is used for uniquely identifying the resource and the body holds the state of the requesting resource. Once the processing is done by the server and the response is sent back to the client through header status or response body.

### **Client-Server**
It has a uniform interface that separates the client from the server. So it helps in improving the user interface portability across multiple platforms and enhances the stability of the server components.
Uniform Interface
To obtain uniformity through the applications RSET has defined four interface constraints which are resource identification, resource manipulation using representation, self-descriptive messages, and hypermedia as the engine of the applications state. 

### **Cacheable**
In order to provide a better performance, the applications are often made cacheable. It is done by labeling the response by the server as cashable or non-cashable either implicitly or explicitly.

### **Layered System**
REST allows us to use a layered system architecture composed of multiple layers. Each layer doesn't know anything about any layer other than that of the immediate layer and there can be a lot of intermediate servers between the client and the end server.

### **Code on Demand**
It is an optional constraint and it's used least. Most of the time, we send the static representations of resources in the form of XML or JSON. But we are also free to return executable code when needed to support a part of our application.

## Conclusion
In this paragraph, I discussed the REST architecture, the most common HTTP methods used in REST-based architecture, and also discussed the six architectural constraints of REST API in detail. that's it for now.

## References
* https://restfulapi.net/rest-architectural-constraints/
* https://restfulapi.net/
* https://www.geeksforgeeks.org/rest-api-architectural-constraints/
* https://www.youtube.com/watch?v=rtWH70_MMHM
* https://dzone.com/refcardz/rest-foundations-restful?chapter=1
* https://www.tutorialspoint.com/restful/restful_introduction.htm