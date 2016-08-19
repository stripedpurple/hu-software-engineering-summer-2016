# Journal 13

## Austin Barrett | Friday, August 19, 2016 

## Chapter 21 - Aspect-Oriented Software Engineering

​		Aspect-oriented software engineering (AOSE) is beneficial in that it supports the separation of concerns. Aspects allow for cross-cutting concerns to be handled separately, while individual or core corns are addressed. Further, aspects prevent excessive code from muddling up core concerns, & eliminating additional complexity & duplicate code.

### 21.1 The Separation Of Concerns

The separation of concerns is the idea that all parts of a system have only one concern, meaning that its purpose is as simple as possible.

Tangling is an issue that occurs when a pieces of functionality is implemented in more than one system requirements. Whereas scattering occurs when a single functionality is implemented as pieces across multiple parts of a system.

### 21.2 Aspects, Join Points, And Pointcuts

​	AOSE has a particular vocabulary for referring to different facets of an aspect. 

| Term       | Definition                               |
| ---------- | ---------------------------------------- |
| advice     | The code implementing a concern.         |
| aspect     | A program abstraction that defines a cross-cutting concern. It includes the definition of a pointcut and the adviceassociated with that concern. |
| join point | An event in an executing program where the advice associated with an aspect may be executed. |
| join point | model The set of events that may be referenced in a pointcut. |
| pointcut   | A statement, included in an aspect, that defines the join points where the associated aspect advice should be executed. |
| weaving    | The incorporation of advice code at the specified join points by an aspect weaver. |

***Note:*** *no part of this chapter is relevant to my project, & the closet any concern has ever come to being needed was easily fixed using a piece of middleware*

