# Journal 11

## Austin Barrett | Friday, August 19, 2016 

## Chapter 19 - Service-oriented architecture

​	Service-oriented architecture is an approach to software engineering where a system is designed to be used a service for other application, & is usually accessed using & api (service interface). 

### 19.1 Services as reusable components 

​	Services can be thought of as components like in CBSE. Each service is independent, & provide an interface to some functionality. The difference between services & components is a service is generally accessed from an api, requiring minimal glue code; & a comment requires copious amounts of glue code. Further, service provide a layer of abstraction that alls application developers to right code without worrying about how the business logic is implemented.

### 19.2 Service engineering

​	Service engineering is the process of build service oriented applications. Classifications of services include:

- Utility services that provide a generic functionality
- Business services that provide generic business process
- Coordination or process services that facilitate inter service execution & communicate 

Each classification is an example of candidate service to be identified during the service engineering process. Identifying a candidate is driven by system requirements, but also helps to solidify implementation, & deployment details.

### 19.3 Software development with services

​	When developing with services the end goal is to create a composite services, which is a composition of services & components. Many businesses are beginning to convert old monolithic architecture over to SO architecture, allowing for the application to have a larger reach throughout the organization. 

To help aid in this conversion process another modeling notation was created. The notation at hand is BPMN, which is a graphic language for modeling the business process

### How this all related to my project

​	Thought my application is intended to be used as a standalone application, it was still designed with a semi SOA approach. everyone interaction with the db in facilitated over custom api endpoints. Though the endpoints were written to be RESTful, & therefore do not follow a SOAP standard or XML protocol.