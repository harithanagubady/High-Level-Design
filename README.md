# High-Level-Design

# OUTLINE
* ### [Distributed Systems](#distributed-systems)

## Distributed Systems
Notes link [**here**](https://github.com/harithanagubady/High-Level-Design/tree/main/_01_Distributed%20Systems)
#### [1. Introduction to Distributed Systems](https://github.com/harithanagubady/High-Level-Design/blob/main/_01_Distributed%20Systems/_01_Introduction%20to%20Distributed%20Systems.pdf)
#### [2. What Distributed Systems Achieve for us?](https://github.com/harithanagubady/High-Level-Design/blob/main/_01_Distributed%20Systems/_02_What%20distributed%20systems%20achieve%20for%20us.pdf)
   1. Fault-tolerance
   2. Reliability
   3. Handling Hardware and Software Faults
   4. Availability
      * SPoF
      * SLA
      * SLO
      * SLI
    5. Scalability
    6. Load Balancing in Distributed Systems
    7. Load Balancing Algorithms
       * Application-layer algorithms
         * Hashing
         * Endpoint evaluation
       * Network-layer algorithms
         * Random selection
         * Round robin
         * Least connection
         * Ip hashing
         * Least pending requests
    8. Measuring Load and Performance
    9. Scalability and Load Balancers
#### [3. Reliable, Scalable and Maintainable Applications](https://github.com/harithanagubady/High-Level-Design/blob/main/_01_Distributed%20Systems/_03_Reliable%2C%20Scalable%2C%20Maintainable%20Applications.pdf)
   1. RELIABILITY
      * Hardware Faults
         * Add redundancy
      * Software Errors
         * assumptions and interactions, thorough testing, process isolation, crash and restart processes; measuring, monitoring and analysing system behaviour
      * Human Errors
         * well-designed abstractions, sandbox environments for experimenting, testing, quick roll-back, monitoring, and good management practices
   2. SCALABILITY
      * Describing load 
        * twitter timeline example
      * Describing performance 
        * throughput and response time, latency vs response time, SLAs and SLOs, percentiles, scaling
   3. MAINTAINABILITY
      * Operability
      * Simplicity 
        * abstraction
      * Evolvability