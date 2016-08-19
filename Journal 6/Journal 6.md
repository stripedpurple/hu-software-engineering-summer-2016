# Journal 6

## Austin Barrett | Wednesday, August 17, 2016 

## Chapter 8 - Software Testing

​	Software testing is the process of determining faults in a software system. Testing can only demonstrate the presence of errors, but not the lack there of.

### 8.1 Development Testing

​	Development testing misdone by the development team as the name suggest. These treat are conducted by the programmer or by an appointed tester. The goal testing software's to try to ***break*** the software. If the software does not break, there is a good chance one is not test right, or the program is simple enough that testing is moot. 

Development testing is composed of the following activities:

- Unit testing, in which individual objects and methods are tested
- Component testing, in which components (groups of objects) are tested
- System testing, in which a systems is tested

All of the testing referred to in this section is mostly only applicable to OO development than therefore have no place in the functional prototyped world of javascript. However, while building my application I  did conduct some none standardized testing in a development environment modeled after the production environment.

### 8.2 Test Driven Development (TDD)

​	Test Driven Development (TDD) is a form of development in which there is great emphasis placed on (Unit) testing. These tests are usually conducted using a unit testing framework like JUnit, or python unittest. Further TDD is effective in reducing the cost of regression testing, which tests a system after changes.

### 8.3 Release Testing

​	Release testing is the process of testing a release. Release testing is geared to releases intended for use outside of the development team, i.e. customers or other departments.

Different parts of Release Testing include

- Requirements-based testing is the process of testing requirements set out during Requirements Engineering
- Scenario testing, in which the a collection of scenarios for the system are developed, & implemented as a test cases
- Performance Testing, involves pushing a system till the performance becomes unacceptable

### 8.4 User Testing

​	User testing is the point at which a system is put in the the hands of an end user. User testing can happen in three separate ways. Alpha testing, in which the user aside the development team test a system. Beta testing, in which a release is distributed to the end user. This allows for user feedback & bug reporting. Acceptance testing, in which the customer test a near final version of the system, & decide whether or not the system in ready for deployment.