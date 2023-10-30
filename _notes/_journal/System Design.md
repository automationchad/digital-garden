---
title: 
up: []
related: 
created: 2023-10-30
tags:
  - 0🌲
---
https://neetcode.io/courses/system-design-for-beginners/0

**Intro**

This is an introduction to what system design is and what problems we’re solving when designing a system. This boils down to putting pieces together in a way that is scalable, available, and performant.

- 

Once we've got the  [[Functional requirements]] and [[Non-functional requirements]] we can turn those into: 

1. a high-level architecture, 
2. what services to use, 
3. how to configure those services.

Address [[Functional requirements]]. 
	How does a request flow through the system?



logic ([[§APIs]], batch job), data (database, blob store) handle everything in [[Functional requirements]]

The key to system design are the [[Non-functional requirements]]:

- [[Scalability]]: A system often needs to handle large numbers of clients, so the system must be able to handle this load without impacting performance.
	- Can each part of the system meet its load?
- [[Performance]]: A system should be able to respond to users’ requests within a reasonable amount of time (latency) and should be able to handle a large number of requests (throughput)
	- Can I make any part faster (or respond faster)?
- [[Availability]]: Even if one part of a system fails, the system as a whole should be able to continue uninterrupted, even if the system fails while it is processing a task.
	- For each component, what will happen if it fails? What could that component be doing when it fails?



