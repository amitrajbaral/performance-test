# Performance Testing with Taurus

##Performance testing
Performance Testing is a type of testing to ensure software applications will perform well under their expected workload.

Features and Functionality supported by a Application is not the only concern. A software application's performance like its response time, reliability, resource usage and scalability do matter. The goal of Performance Testing is not to find bugs but to eliminate performance bottlenecks.

The focus of Performance Testing is checking application's

Speed - Determines whether the application responds quickly
Scalability - Determines maximum user load the software application can handle.
Stability - Determines if the application is stable under varying loads.

Performance Testing is popularly called as “Perf Testing” and is a subset of performance engineering.

##Common Performance Problems in the application
- Poor response time 
- Poor scalability
- Bottlenecking 
  - CPU utilization
  - Memory utilization
  - Network utilization
  - Operating System limitations
  - Disk usage
   
##Process of performance testing
1. Identify testing environment
1. Decide performance acceptance criteria
1. Plan and design performance test
1. Configure test environment
1. Run the test
1. Analyze, refactor the application and re-test

##Parameters Monitor from Performance testing

- Processor usage 
- Memory use 
- Disk time 
- Bandwidth 
- Committed memory - amount of virtual memory used.
- Disk queue length 
- Network output queue length 
- Response time of the response is received.
- Maximum active sessions 
- Database locks 
- Thread counts 
- Garbage collection 

##Performance testing tools
1. Jmeter
1. Gatling
1. NeoLoad
1. NUnit
1. Mocha
1. `Taurus` and many others

##`Taurus`
-- https://gettaurus.org/
Taurus is an open-source automation framework that helps to test performance of applications. Briefly, Taurus is a tool that provides a simple way to create and run performance tests, as well as an easy integration with additional open-source functional and performance testing software, like Selenium, Gatling or JMeter. It uses Jmeter as default load generator.

###Installation
If you have JDK1.8 and python 2.7+ installed in the machine we want to execute perf Testing. 

For Mac
``````
brew install bzt
``````
or to upgrade the existing version 
``````
brew upgrade bzt
``````
If this doesn't work for you, you can follow other manually installation instructions from this link. https://gettaurus.org/install/Installation/
