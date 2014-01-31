# Title
### Agile Go Development for the Cloud

# Description

Learn how to apply agile methodologies while introducing Go into a large scale production environment. Follow along as we take you through many of the design decisions we made, and the refactorings that resulted as we introduced Go into the Cloud Foundry platform.


# Abstract

Learn how to apply agile methodologies while introducing Go into a large scale production environment.

Cloud Foundry has many moving parts, most of which were until recently written in Ruby. We are rewriting many of these components in Go to improve portability, reduce the number of long-running Ruby processes, and harness the power of a low-level systems language. We did all of this while running a large scale, distributed, production application. We have applied agile methodologies such as TDD and continuous deployment to iteratively replace the old Ruby components with these new compiled Go binaries. Follow along as we take you through many of the design decisions we made, and the refactorings that resulted as we introduced Go into the Cloud Foundry platform.  We will cover:

 * Test Driven Development methodologies in Go
 * Techniques for managing distribution of Go binaries
 * Integrating compiled Go binaries with Ruby collaborators
 * Managing Go library dependcies
 * Leveraging Go interfaces for cleaner and more extensible code
