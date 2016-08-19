# Journal 10

## Austin Barrett | Friday, August 19, 2016 

## Chapter 18 - Distributed software engineering

​	A distributed software engineering as the name suggests, is an approach to software development in which the resulting system is distributed across multiple pieces of (commodity) hardware. The benefits of such a systems are that the system is easily scaled,  system failover, and resource sharing.

### 18.1 Distributed systems issues (TL;DRA)

​	When considering distributed SE a few issues must be kept in mind. These issues include transparency, openness, scalability, security, quality of service, and failure management.

Scaling issues come in two forms, vertical & horizontal scaling. Vertical scaling or scaling up, is when a hardware component is upgraded so that the individual node in the system can handle more. Horizontal scaling or scaling out, is when a new node (typically a server composed of commodity hardware) is added to the system, furthering its distribution.

### 18.2 Client–server computing

​	Client–server systems are distributed systems in which the system is composed of a client computer that fetches resources & presents them to the end user, & a server that provides the data, functionality, & other interaction with the system to the client.

Client–server systems should be design with a clear separation between the servers role as a data provider, & the clients role as a presenter. However this line does sometime get blurred. As an example in my application I  utilize a server to facilitate all database interactions, & a client side MVC to facilitate simple functionality & advanced presenting with live two way data binding. 

### 18.3 Architectural patterns for distributed systems

​	Because of system requirements several architectural patterns have emerged including master-slave architectures, two-tier and multitier client–server architectures, distributed component architectures, and peer-to-peer architectures.

In a distributed system component communication is facilitated using middleware. A large part of the express js framework is building middleware to agent the functionality of the framework to meet the needs of the application.

Most distributed systems fall under a client serve model or a P2P model. P2P (Peer-to-peer) architectures are decentralized architectures in which there is no client or server. All nodes in the system are equal, & can be distributed across several organizations. In the P2P model there is no master or hierarchy.

### 18.4 Software as a service

Software as a service is a methodology of code deployment in which a server provides a service to a client. The client can be as simple as a web browser or a fully customized system that needs to be downloaded then run locally.