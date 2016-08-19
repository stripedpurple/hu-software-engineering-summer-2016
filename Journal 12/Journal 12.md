# Journal 12

## Austin Barrett | Friday, August 19, 2016 

## Chapter 20 - Embedded Software

​	An embedded software system is  a hardware/software system that reacts to external events. The software is embedded on the hardware, typically in read only memory. Generally these systems are considered to be real-time systems. A real-time system is one that responses to an event in time period less than or equal to specified period. In a real-time system correctness is measure in terms of I/O responsiveness, & time elapsed between I/O event & response.

### 20.1 Embedded systems design 

​	Most embedded systems follow the stimulus-response model. This means that when ever a stimulus (event) occurs it triggers a response. 

When designing a embedded system state models are a valuable tool. The state model represents a transition from one state to another when an event is triggered. State models can be thought of as finite state machines , & look quite similar too.

Because of time constraints, & performance overhead, it is extremely important to pick the correct programming language when designing an embedded system. Most embedded systems today use a system level language like C, however it is sometimes necessary to us machine language like assembly when working with an embedded system.

### 20.2 Architectural patterns

​	Similar to the architectural patterns previously written about, embedded systems also have a set of common patterns.

1. Observe &  React - This is used when a system needs to monitor an input for an event, i.e. pilot depressing a break pedal .
2. Environmental Control - Similar to the observe & react pattern, this pattern monitors an input, & sends a control signal based on the input data.
3. Process Pipeline - In this pattern data taken in is transformed so that it can be processed.

Though these pattern is exist that should not be used as a template for a system but rather as general approach.


### 20.3 Timing analysis

​		When designing a real-time systems, it is important to conduct timing analyses, which involve checking compliance with process deadlines &  stimuli response time. It is unto the system designer to decide the process frequency (how often each process should run), & the expected & worst-case execution time for processes.

### 20.4 Real-time operating systems

​	Real-time operating systems (RTOS) are bare metal (stripped down) operating systems that provide a means of scheduling process, & very few other things. Generally, a RTOS requires a RTC (Real Time Clock), interrupt handler, scheduler, resource manager, & dispatcher.