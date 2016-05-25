#Journal 1

## BY Austin Barrett Monday, May 23, 2016  

##Chapter 1

###**Professional Software Development**

​     Software engineering, what is it? Ian Sommerville, author of Software Engineering 9th Edition, defines software engineering as "an engineering discipline that is concerned with all aspects of software production." (p. 6) Simply put software engineering is the reallife practical applications of Computer Science.

These application can be broken down into eight major types.

1. Standalone applications
2. Interactive transaction based applications
3. Embedded control systems
4. Batch processing systems
5. Entertainment systems
6. Systems for modeling and simulation
7. Data collection systems
8. Systems of systems

As an  engineer, one must be able to select the appropriate application type. Each application type has different requirements that will effect the programming languages needed to complete software. 

Example

> A airplane manufactorer needs a new braking system that is able to deploy the brakes within a drastically short period.

Given this requirement, it would seem quite inapropriate to use an interprated language like python or ruby to build the embedded control system for the brakes, instead it would be more logical to use a lower level language like c or assembly, because the languages are compiled and don't need to be interprated on the fly. Other consideration for this project are what development style used. When developing such a system the developers need to, as the old adage says, measure twice cut once. Continous deployment or Increamental development would not be appropriate, because the they take an infeild aproach to testing that promotes a fail fast and often attitude to working out bugs. Which is never a good idea when failing fast could mean killing many.

###**Software Engineering Ethics**

     As software engineers do what they do best, they must think about the possible uses, and application of the technologies involved. 

Example I  

> A banking firm decides to contract a software development team to build a mobile application to allow its patrons to be able to facilitate their banking transaction. The team that will be developing this software will have to take into consideration that they will be in possession of sensative information, access to restricted systems, as well as possiblilty that there software could be compromised.

Moreover, a developer must be able to express to their employer what they are comfortable with doing. Some developers may have some qualms with what is being asked of them, and therefore should be able to advocate for their position.

Example II

>A development team is approached by the government to build missle guidance system. However one of the team members is anti-war, therefore morallly and ethically objects to building the software. 

This developer must be able to communicate their inability to work on the project with their team, and potential employer. Communication of the developers opinions is important because it could their opinions could effect the team later down the line.

## Chapter 2

​     Software processes are a collection of related activities that aid in the production of software. These activaties may include build a software from scratch or by use third party off the self software to integrate with a new application. Sommerville outline four activaties that are usaully part of the a software process.

|          Software specification          |    Software design and implementation    |           Software validation            |            Software evolution            |
| :--------------------------------------: | :--------------------------------------: | :--------------------------------------: | :--------------------------------------: |
| The functionality of the software and constraints on its operation must be defined. | The software to meet the specification must be produced. | The software must be validated to ensure that it does what the customer wants. | The software must evolve to meet changing customer needs. |

Software Process have the ablity to scale to greater complexities, and therefore need acompanying techniques and tools.

### **Software Process Models & Process Activities**

​     Simply put Software Process Models are representations used to describe, convey, or demostrate a sowftware process. in this chapter Sommerville discusses three different Software Process Models.

1. ***The waterfall model*** - This approach to SPM (Software Process Model[ing]) represents the above activaties a procedural steps, in which each successive step is directly depend on its predecessor.
2. ***Incremental development*** - This SPM combines specification, design and implementation, and validation into one step. Once completed the fourth tenet ( Evolution ) begins, and the funtionallity is added to the software interatively.
3. ***Reuse-oriented software engineering*** - This model requires of the software the ability to be modular, sticking functionality it reusable and change parts. The primary focus of this model is integration with third party software and services.


As demostrated by incrementative development these activaties can become interwoven with each other. With this occurs it adds a certain amount of complexity to the overall software process. To aid in the furtherment of the software process there have been sveral tecniques and developed. Moreover, the scope of these activaties can extended far beyond the developer(s), requiring interaction with manajerial staff, and clients / users. Being a technical, and collaborative process tools play an exceptionally large role. From tracking changes to keeping a team on track, and much more, tools have completely redefined what the modern software developer and software can do.

### **Coping With Change**

​     As business, and technology change so must the software developers create, and the techniques they use to create them. The problem with change is it has an impact on many aspects of the product. Changing with requirements or the market can be costly. Developer have to rework code which takes time, and as the saying goes time is money. Also implementing new technology can have many other adverse monetary effects, such as licensing, data model restructuring, hardware complience, etc. However the converse is true as well. Some changes can increase profit or decrease lost. Example decreasing the upstart time of an application, or decreasing the time for a transation has a long term value and can also add to the brand. Upgrading hardware can also have an dramatic impact on lost. Example it is cheaper to buy 4GB of RAM than 2GB, or upgrading your AWS (Amazon Web Services) EC2 (Elastic Cloud Compute) instances to a newer hypervisor can cut a bill in as much as half. 

Never the less,change will happen and the are many tools and techniques the can help ease the transition.

### **The Rational Unified Process**

The Rational Unified Process (RUP) was created by rational, a software company that was aquired by IBM in 2003. Originally RUP was developed as a SPM program / framework designed to streamline development while giving it the ridged structure used by Rational. However, since the software's inception it has grown into a full fledged SPM compairable to the Waterfall Model.
