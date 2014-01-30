# Description



# Abstract

Cloud Foundry has many moving parts, most of which were until recently written in Ruby, with many interdependencies. Recently, we have begun to rewrite many of these components in Go to improve portability, reduce the number of long-running Ruby processes, and harness the power of a low-level systems language. While running a distrubuted, production application, we have applied agile methodologies such as TDD and continuous deployment to iteratively replace the old Ruby components with these new compiled Go binaries, without effecting our production PaaS.

 * Test Driven Development methodologies in Go
 * Integrating compiled Go binaries with Ruby collaborators
 * Leveraging interfaces to abstract away dependencies