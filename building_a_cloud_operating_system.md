# Description

BOSH serves as the foundation of the Cloud Foundry Platform as a Service by
creating a cloud operating system to facilitate controlled interactions 
between application software and the underlying cloud infrastructure and operating systems. 
Through focusing on the interfaces between collaborating components and leveraging 
the strengths of Go, we'll show you how we refactored  a large monolithic code base  
into a collection of focused and interchangeable components. 

# Abstract

Cloud Foundry BOSH is a tool for reliably and repeatedly orchestrating large
scale distributed services. In the past year BOSH has undergone significant 
refactoring in order to expose the contracts between cloud infrastructures 
and operating systems that BOSH requires as extendable and maintainable
components which we like to think of as cloud device drivers. The *NIX design 
philosophy of combining portable, tightly focused applications into a coherent 
whole has even more relevance as computing continues to move towards distributed
and virtualized resources. Follow along and explore:

 * The challenges in refactoring a production system.
 * Creating a loosely coupled collection of components through interfaces
 * Writing future-resilient software by creating opportunities for community
   involvement.
