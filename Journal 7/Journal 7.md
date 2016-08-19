# Journal 7

## Austin Barrett | Wednesday, August 17, 2016 

## Chapter 9 - Software Evolution

​	Software evolution is the inventible change of a system. This means that the software development process is not over after it has been implemented. Software evolution is thought to be the most costly part of software development. This is because it is a continuation of the system that does not end quickly.

### 9.1 Evolution Processes

​	Evolution is usually drive by user requests, both formal & informal. Change is also driven by currently unimplemented requirements, & newly discovered bugs.

### 9.2 Program evolution dynamics 

​	Program evolution dynamics is the of system change. Research conducted by Lehman & other Computer scientist led to the discovery of what is referred to as Lehman’s laws.

| Law                         | Description                              |
| --------------------------- | ---------------------------------------- |
| Continuing change           | A program that is used in a real-world environment must necessarily change, or else become progressively less useful in that environment. |
| Increasing complexity       | As an evolving program changes, its structure tends to become more complex. Extra resources must be devoted to preserving and simplifying the structure. |
| Large program evolution     | Program evolution is a self-regulating process. System attributes such as size, time between releases, and the number of reported errors is approximately invariant for each system release. |
| Organizational stability    | Over a program’s lifetime, its rate of development is approximately constant and independent of the resources devoted to system development. |
| Conservation of familiarity | Over the lifetime of a system, the incremental change in each release is approximately constant. |
| Continuing growth           | The functionality offered by systems has to continually increase to maintain user satisfaction. |
| Declining quality           | The quality of systems will decline unless they are modified to reflect changes in their operational environment. |
| Feedback system             | Evolution processes incorporate multiagent, multiloop feedback systems and you have to treat them as feedback systems to achieve significant product improvement. |

### 9.3 Software maintenance

​	There are three types of software maintenance. Fault repairs, which deals with fixing bugs. Environmental adaptation. in which the software is modified to work in a new environment. Functionality additions, where new or remain functionality is implemented. Early on, in the development process, thought should be given to what parts of the system might change. When this is considered it becomes easier to implement during the evolution of the system.

Software reengineering is concerned with re-documenting, refactoring, and/or translating a software to a new programming language. Reengineering is beneficial, because it help reduce risk such as future failure, & reduces cost such as build a new system from scratch.

Refactoring reduces the need for future maintenance. This migration technique work through removing redundant code, improving software structure, reducing complexity, & increasing understandability.

​	I have seen some of this already in my project. I have had to reduced redundant code, & cut down the complexity of the api service that maintains the control over the database.

### 9.4 Legacy system management

​	Legacy systems are important, & have copious amounts of business value. However, it is important to take an in-depth look at a legacy system, as it may be impartial to maintain it. Instead the evolution of a system should have one of the following strategies applied to it.

- Scrap the system completely
- leave the s system unchanged & continue with regular maintenance
- Reengineer the system to improve maintainability
- Replace all or part of the system

