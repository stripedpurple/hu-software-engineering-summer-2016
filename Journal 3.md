# Journal 3

## by Austin Barrett - Sunday, June 12, 2016

## Chapter 4 Requirements Engineering

​	Requirements for a system describe what the system should do, what services it provides, and constrains its operations. Requirements reflect the needs a customers has for a system  serving a certain purpose. Requirements Engineering (RE) is the process of  analyzing, documenting, and checking system services and constraints.

### Functional and non-functional requirements 4.1

​	Functional requirements describe what the system should do. Requirements are dependent on the type of software being developed, the intended users, and the way in which the client wrote the requirements. Sometimes functional requirements are written as abstract user requirements only understood by system users. However, functional requirements can describe the system's functionality in greater detail. Put simply functional requirements are those which define features, whereas non-functional requirements define qualities of the system.

Non-functional requirements can impact the entire system instead of a single component. Non-functional requirements can be further broken down into three sub-type requirements.

| Name                        | Definition                               | Example                                  |
| --------------------------- | ---------------------------------------- | ---------------------------------------- |
| Product requirements        | These requirements specify or constrain the behavior of the software. | Performance, memory, reliability, acceptable failure rates, security, and usability requirements. |
| Organizational requirements | These requirements are defined by vague system requirements derived from the organizations, or developer's culture | Operational process requirements, development process requirements, development environment or process standards. |
| External requirements       | Requirements that are derived from factors external to the system and its development process. | Regulatory requirements                  |

### The software requirements document 4.2

​	A software requirement document in its simplest and most distilled form is a list of requirements for a project. However software requirement documents can be quite large depending on the type of project. Given a project that requires interaction with a PLC or MCU, or even a sensitive data set, requirements documents become very important. To contrast projects like video games act more like a live being, growing, evolving, and ever changing, ergo they need less strict and detailed requirement document(s). In most modern day projects thing change to fast to crank out new requirement document(s), instead methodologies the reside in the agile camp, use things like cards, list, and boards to add to the requirements, but as features.



### Requirements specification 4.3															

​	Requirement Specification is the process of creating a requirement document. Ideally specifications, whether for users or the system, should be clear, concise, and easy to read. 

#### User and System Requirements

User requirements should define the functional and non-functional requirements for a system without requiring the user to have technical knowledge. This means that the document should be devoid of industry jargon, models, and other industry isms. Instead user requirements should be written in plain everyday language. However this can be troublesome. Much like reading the bible, people will and do interpret the meaning differently, which can then lead to confusion amongst those involved.

System Requirements are an elaboration on the user requirements, but with a great deal more detail. System requirements serve as a starting point for developers to begin designing and implementing the system. They also provide a description of how user requirements should be delivered. Just like user requirements, system requirements should specify the externals of a system, and leave the design and implementation of the system up to the developer(s). However this is a complicated feat for more involved, and feature rich systems, as they require a much higher level of detail. 

#### Natural language specification

Natural language specification is specification through common language. However, because of region, and background words and phrases used in  natural language specifications can have different meanings, and therefore cause misunderstanding. To help mitigate these issues Sommervile recommends the following.

1. Define a standard for the requirement documentation. This includes format, style, syntax, etc..
2. Use consistent language to distinguish between mandatory and optional requirements. 
3. Use typographical cues i.e. bolding, italicizing, and underlining.
4. Do not assume that readers understand technical software engineering language. Define possibly unknown terms, or better yet leave out the jargon.
5. Give context and meaning to requirements.


#### Structured specifications

Structured natural language specifications are more rigid and limited forms of natural language specifications but with a given structure. The structure is usually derived from an agreed upon template. Using a structured specification streamlines parts of the requirement specification, and makes for a more clear meaning, relying less on the users interpretation. However this can still have its problems, especially in the case of complex computations.

### Requirements elicitation and analysis 4.5

​	After an initial feasibility study, the next stage of the requirements engineering process  (REP) is requirements elicitation and analysis. During this activity, developers work with customers / users to determine the scope of the system, the services it should provide, the required performance / hardware constraints, etc. More simply, the developer gather requirements from the customer and users.

Generally, there are four activities used in the REP. They are as follows:

1. *requirement discovery* collaboration with stakeholders and other system users to gather requirements.
2. *requirement classification in organization* as its name clearly states it is the process of organizing and classifying requirements.
3. *requirements prioritization and negotiation* the process of distilling requirements and features to their most rational and functional form. This is done because stakeholders requirements have the potential to conflict.
4. *requirements specification* the collected requirements are documented. As discussed in the previous section these documents can be simple two extremely formal.

#### Interviews

During requirement elicitation it is commonplace to hold interviews with stakeholders. Interviews happened in one of two ways, closed interviews in which the interviewer asks the interviewee a predefined set of questions, or open interview where in nothing is predefined. Both methods are generally used in conjunction, because because neither technique alone yields 100% useful information. Though interviews are useful for gathering user-based requirements is harder to elicit system domain requirements from this process. The router these complications can be simply derived from the interviewees comfort with the domain, or the general culture/understanding of the domain. Effective interviewers are able to mitigate these issues and derive usable requirements from the interviews.

#### Scenarios

In lieu of doing an interview software engineers can provide the stakeholders with one for more scenarios. Doing so helps the stakeholders and division interactions with the system and convey likes and dislikes, as well as further requirements and unneeded requirements.

In general scenarios will include:

1. A description of what the system and users expects when the scenario starts
2. A description of the normal flow of events in the scenario.
3. A description of what can go wrong and how this is handled.
4. Information about other activities that might be going on at the same time.
5. A description of the system state when the scenario finishes.

#### Use cases

Use cases in their simplest form are used to describe the actors and interactions of the system. Use cases are a large part of the object oriented method and are used in UML. Use cases are visual representations that describe interactions between users in the system, comprised of stick figures and textual annotations. Scenarios and use cases are the most effective forms of eliciting requirements from stakeholders.

#### Ethnography

Ethnography is a form of requirement eliciting that requires the developer to embed themselves in the workplace for which the system is being built. More simply, ethnography is the observation of stakeholders, there work, and environment to derive requirements. Because of its focus on the user, ethnography have trouble identifying system in domain requirements.

### Requirements Validation 4.6

Requirements validation is used to determine the validity of requirements before they are implemented. This is done to ensure that the requirements specified meet the description of the desired system. If this process is skipped future May arise, which can be costly as it requires retool and in retesting. During requirement validation several different types of checks should be completed. Validation check should occur to make sure that user features/requirements are necessary and do not conflict other features/requirements. A consistency check ensures that documented requirements do not conflict. Completeness checks ensure that all functions are defined and so are their constraints.	Realism checks are used to guarantee the feasibility of a system, this is done so by looking at current technology. Verifiability it's a key aspect every climate validation. It is used to ensure that the contractor and the customer are in agreement with any and all documented requirements.

### Requirements Management 4.7

​	Managing requirements can be exceptionally hard to do and large systems. The reason for this is because some problems are too complex to easily define. Other issues may arise such as environmental changes, hardware changes an introduction of new business practices; a disconnect between the people pain and the people using the system; and diverse city amongst end-users and their expectations

#### Requirement Management Planning

During the initial phases of RE it is important to design a plan for managing requirements and their future possible changes. This can be achieved by using several requirement management planning techniques as requirement identification,  a change management process, traceability policies, and tool support.

#### Requirements Change Management

Requirement change management is used after the requirement document has been approved. When changes are proposed the process to ensure that the requirements stay complete, coherent, and copacetic. The three fundamental stages of the change management process our as follows:

1. *Problem analysis and change specification* - problem or a new requirement is identified, and a proposal for a new requirement for change is made.
2. *Change analysis and costing* - during the stage an analysis of the effects of the proposed change for new requirement is completed. This is done to ensure the feasibility, and cost-effectiveness of the proposed change.
3. *Change implementation* - after approval the change is implemented into the requirements document and where ever else necessary.

