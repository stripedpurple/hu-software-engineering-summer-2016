# Journal # 2

## by Austin Barrett - Sunday, June 5, 2016 

## Chapter 3	

### 3.1 Agile Methods

​	In the early days of software development their existed a large focus on Software Engineering Processes, most of which did not scale well. These processes worked great for large companies and certain forms of software development. However they have their pitfalls. Processes driven by a need for documenting, lackadaisical communication, and changes in negotiations as well as specifications. To tackle these issues a group of developers in the 1990s form to create the ***agile manifesto*** , which states:

> We are uncovering better ways of developing software by doing it and helping others do it. Through this work we have come to value:
> - Individuals and interactions over processes and tools
> - Working software over comprehensive documentation
> - Customer collaboration instead of quibbling over contract negotiation
> - Responding to change over following a plan
>
> That is, while there is value in the items on the right, we value the items on the left more.

This manifesto was later adopted and used to craft new methodologies and processes for software development. Agile methods have a great focus on incremental development as oppossed the formal / classical approach to development which required the delivery in full. As mentioned before, this type of development can be problematic due to the ever changing requirements expierenced in common software development. 

### 3.2 Plan-driven and agile development

​	Much of agile and plan driven development differ from each other, however, they do share one key facet, they utilize incremental cycles. (See figure 3.2)

***Figure 3.2 :***



![Figure 3.2](./journal_2_fig3.2.png)Agile is vision/value driven development, as opposed to traditional development which is plan driven. By being focused on the vision / value of a project development becomes more fluid, allowing for features to be the scope of a project, not a requirements.

Sommerville provides a list of question to ask when deciding on a development process. The questions are as follows:

1. Is it important to have a very detailed specification and design before moving to implementation? If so, you probably need to use a plan-driven approach.
2. Is an incremental delivery strategy, where you deliver the software to customers and get rapid feedback from them, realistic? If so, consider using agile methods.
3. How large is the system that is being developed? Agile methods are most effective when the system can be developed with a small co-located team who can communicate informally. This may not be possible for large systems that require larger development teams so a plan-driven approach may have to be used.
4. What type of system is being developed? Systems that require a lot of analysis before implementation (e.g., real-time system with complex timing requirements) usually need a fairly detailed design to carry out this analysis. A plan- driven approach may be best in those circumstances.
5. What is the expected system lifetime? Long-lifetime systems may require more design documentation to communicate the original intentions of the system developers to the support team. However, supporters of agile methods rightly argue that documentation is frequently not kept up to date and it is not of much use for long-term system maintenance.
6. What technologies are available to support system development? Agile methods often rely on good tools to keep track of an evolving design. If you are developing a system using an IDE that does not have good tools for program visualization and analysis, then more design documentation may be required.
7. How is the development team organized? If the development team is distributed or if part of the development is being outsourced, then you may need to develop design documents to communicate across the development teams. You may need to plan in advance what these are.
8. Are there cultural issues that may affect the system development? Traditional engineering organizations have a culture of plan-based development, as this is the norm in engineering. This usually requires extensive design documentation, rather than the informal knowledge used in agile processes.
9. How good are the designers and programmers in the development team? It is sometimes argued that agile methods require higher skill levels than plan-based approaches in which programmers simply translate a detailed design into code. If you have a team with relatively low skill levels, you may need to use the best people to develop the design, with others responsible for programming.philosophies
10. Is the system subject to external regulation? If a system has to be approved by an external regulator (e.g., the Federal Aviation Authority [FAA] approve software that is critical to the operation of an aircraft) then you will probably be required to produce detailed documentation as part of the system safety case.

Overall the importance of assigning a label to your software development process is nil. Modern companies and development teams tend to use a hybrid of the two, taking aspects of agile and applying them to plan driven development.

### 3.3 Extreme Programming

​	Extreme Programming (XP) as its name suggests is a method of agile programing in which emphasis on good practices are pushed to the extreme. XP embraces many of the philosophies of agile. However XP is really best suited for small to medium teams, and can be quite costly, causing it to be used only for short projects. 

There are serval very important aspects to XP. They can be distilled down into two main parts testing, and pair programming.

#### Testing in XP

By testing first and often bugs can be detected easily and early. Most testing in XP is done so through Unit Tests in which code is broken into the smallest possible modules. Once tested the code can then be refactored, making code clean and easy to maintain. Once a unit is complete it is added to the overall project, and then tested all side the rest of the software. This is know as continuous integration. Programming in this fashion allows for small incremental releases. Once complete the release under goes a code review.

#### Pair Programming

Code review is the process in which a group of developers and associated team members gather to critique, improve, and understand the new code and its place in the system. In XP code review happens in teams and helps reenforce collective ownership. Collective ownership occurs because programming is done in pairs, and each member of the pair is responsible for understanding the code as it applies to the system, as well as the codes failure, thus removing the stigma of failure from the individual.

### 3.4 Agile project management

​	Scaling agile processes to large systems and projects is extremely difficult. Systems at this scale require design and some documentation at the beginning of the project before modules can be built. Without this, it can be functionally impossible to make real progress or even begin. Continuous integration is nearly impossible when multiple separate teams are working on a project.  It becomes impractical to rebuild systems every time a new change in committed to the project. Further, these modules could be incompatible with the system, as teams are not privy to the system.



