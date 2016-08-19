# Journal 5

## by Austin Barrett - Sunday, July 17, 2016  

## Chapter 6 - Architectural Design 

​	Architectural Design is the first step in software in the software design process, & bridges the gap between design , & requirements engineering. Explicitly defining architectural designs , & documentation has several advantages.

1. Stakeholder communication becomes easier when present, as they help facilitate communicate , & understanding.
2. System Analysis during architectural design aids in determining the feasibility of a system.
3. Large-scale Reuse — some systems have similar requirements , & therefore can be reused in other systems.

### 6.1 Architectural Design Decisions

​	Architectural Design Decisions can be thought of as a collection of decisions, based on the architect's  experience. These decision lead to a contractual design for a given software project. These architectural design decisions aRequirements Engineering based on architectural patterns / styles that can be reused. While making these decisions, the architect must consider performance, security, safety, availability, & maintainability.

### 6.2 Architectural Views

​	Architectural views are used to represent different facets of a system's architecture. It is impossible to represent every part of an architecture in a single architectural view. The 4+1 model provides a generic way to represent multiple views of a system. In the 4+1 model, it is suggested that there are four fundamental views of a software architecture. 

1. Logical View
2. Process View
3. Development View
4. Physical View 

It has been suggested that there should be a 5th view called the Conceptual view, which provides a high level view of the system. This view can aid in bridging the gap between the the customer, end user, & the architect.

Depending on the development methodology employed by the software development team, these views can be represented in UML. This is less true in agile development which focus less on documentation.

### 6.3 Architectural Patterns (Styles)

​	Architectural  Patterns are stylized, abstract descriptions of best practices for  system architecture. Examples of architectural patterns are layered, repository, client/server, & pipe/filter architecture.

#### Layered architecture 

In this architectural pattern, each functional competent can operate as a layered in the system. This pattern makes supporting incremental development significantly easier. Because each layer of the system works nearly independently, & only effects the adjacent layer. 

These concepts can be seen in the commonly used MVC model. I utilize the MVC model in my a LEAN (Level Express Angular Node) application. In this model there are three main layers, the model, the view, & the controller.

#### Repository architecture

This pattern is just a small foot note in Sommerville's writing & therefore will be will be excruciatingly brief. Repository architecture is simply a pattern in which data is shared between components & software. At fundamental level this is how VCS (Version Control System) works. A common set of code is shared between many devices, with every change being stored as a previous version.

#### Client / Server Architecture 

In this architectural pattern two or more pieces of software communicate usually over a network protocol. In this model the softwares tend to be distributed. Each software component should be independent of each other & therefore easier to maintain.

Being a full stack application, the client server model is implied. My application acts as a server, & when a browser connected to the application it becomes a client.

#### Pipe/Filter architecture

Pipe/Filter architecture is named after unix pipes, & derive their general functionality from said unix pipes. Data flows from one function to another, with output of the original function being passed into the next function. The functions manipulate, & filter the output until it reaches its final state. 

This pattern can be seen in my application. Javascript, which is the main language used in my application, is implemented as a functional language, following the pipe/filter model.

### Application Architecture 

​	An application architecture is a generic way to create an application. These architectures are highly re-usable ways to write an application. Though not every application has the same functionality, it can follow a similar pattern. 



## Chapter 7

​	Software design & implementation is a  set of activities that start off the programming process. This is the phase in which the basic logic is worked out. The granularity of the design depends on the system being developed, & the methodology used to develop it. 

### 7.1 Object Oriented Design using The UML

​	Object-oriented design is the approach to software development in which data is strutted as real world objects & are defined by their classes. The data contained in objects is considered private. The core of OOP is the relationships that exist between objects. 

When working in OO it is common to use UML (Unified Modeling Language) to represent the many facets of OO. However it is this developers opinion that UML is a excessively verbose, & therefore pointless, hence the absence of it from the developed application.

Many developers utilize UML to nail down the general logic of a system, as well as the scope, constraints, & design. This is done so through different types of models & diagrams.

### 7.2 Design Patterns

​	Design Patterns are general solutions to common problems. These patterns are vague in nature, & are only to be consider as a framework not a full solution. These design patterns are most commonly seen in OO design & rely great on the four pillars of OO design. 

Design Patterns are highly reusable, as their name suggests. They provide a high-level overview of a concept that can be utilized as an outline for a system. This is different from code reuse, in that components in the design pattern do not contain  executable code. If the pattern did contain executable code it would not be necessary for a new system to be developed.

For inexperienced developers patterns can be quite troublesome. Often it takes developing a system with a particular pattern to determine whether or not it is the appropriate solution to the problem.

### 7.3 Implementation Issues

 	Implementation issues come in many forms. Some issues are derived in the fact that they are also solutions.

Reuse can be an extremely handy way of dealing with common code needs. From libraries to off the shelf software, there are plenty of solutions to common problems. However, reuse can be costly. It take time & money to identify code or software for reuse. Further, the cost of implementing an unknown comment can also be costly. If the component has dependencies, or require a new software to be written to bridge it into a system, more time will go to waste.

Configuration management deals with the changes made in a system. Configuration management is broken down into three activities. Version management, which is concerned with changes made to a system. System integration, which is concerned with what version of a components are used in the building of a system. And lastly, issue tracking, which is used to report, handle, & correct issues in the system.

Host/target development refers to development on a host platform & deployment on a different platform. When developing a system, it is necessary to keep in mind what hardware, OS, & other dependencies are required for the system to run. This is extremely prevalent today when you consider the average developer develops on a system that is much more powerful than the commodity hardware that it is to be deployed to.

### 7.4 Open Source Development

###	Open Source is the practice of making the code to a system publicly available. This means that anyone can propose, & make changes to the software. There are varying levels of open source, & are laid out in the licensing that accompanies the software.  

















