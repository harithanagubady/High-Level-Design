# High-Level-Design

1. Introduction to Distributed Systems
2. What Distributed Systems Achieve for us?
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
3. Reliable, Scalable and Maintainable Applications
   1. RELIABILITY
      1. Hardware Faults
         * Add redundancy
      2. Software Errors
         * assumptions and interactions, thorough testing, process isolation, crash and restart processes; measuring, monitoring and analysing system behaviour
      3. Human Errors
         * well-designed abstractions, sandbox environments for experimenting, testing, quick roll-back, monitoring, and good management practices
   2. SCALABILITY
      1. Describing load - twitter timeline example
      2. Describing performance - throughput and response time, latency vs response time, SLAs and SLOs, percentiles, scaling
   3. MAINTAINABILITY
      1. Operability
      2. Simplicity - abstraction
      3. Evolvability