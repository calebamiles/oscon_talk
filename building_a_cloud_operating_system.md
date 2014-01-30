### Description

BOSH provides the foundation of the CloudFoundry Platform as a Service by
faciliating controlled interactions between applications, cloud infrastrures
and operating systems. Through focusing on the interfaces between collaborating
components and leveraging the strengths of Go, a large monolithic code base has
been refactored into a collection of focused and interchangeable components. 

### Abstract

CloudFoundry BOSH makes it possible to repeatably and reliably deploy software:
from isolated ETCD or Riak clusters to the entire CloudFoundry Platform as a 
Service which requires the federation of multiple clusters into a useful 
service. In order to better facilitate the controlled interactions between 
application software, the operating system and the infrastructure while also 
empowering community extension and maintenance of BOSH, several core components
of BOSH have either been extracted from the original code base or have been
rewritten in Go. These changes have allowed us to replace tightly coupled Ruby
collaborators with loosely coupled, tightly focused, and portable binaries. By
adhering to the spirit of *NIX design principals we are creating the next
generation operating system for the cloud.

 * Challenges in refactoring a production system.
 * Assembling a system by preferring interfaces over inheritance.
 * Writing future-resilient software by creating opportunities for community
   involvement.
