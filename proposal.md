## Title
BOSH: A LEGO based cloud operating system

## Talk Overview

#### Why Rewrite [Rob]
 - Large legacy codebase with poor test coverage
 - Monolithic organization
 - High barrier to entry for community involvement
 - IaaS + Operating System matrix hell

#### Abstracting the operating system [Caleb]
 - Move platform and infrastructure interactions into NIX style commands
   * Separation of concerns
   * Extensibility (new blobstores, etc)

#### Why Go [Rob]
 - Long running ruby proccess and memory pressure
 - Portability
   * non-NIX stemcell support
 - Injectability
 - Super shiny

#### Writing the Go Agent [Jeff]
 - Experiences with TDD in Go?
 - Removing infrastructure + platform dual dependencies
   * VSphere cdrom settings
   * Networking configuration
   * Drive naming/type logic
 - Plugging CPI logic leaks

#### CPI Extraction [Caleb]
 - Why
   * Community engagement/empowerment
   * Polyglottal possibilities (VSphere)
   * Baremetal
   * Containers (Docker)
 - How
 - Challenges

#### What's Next [Caleb]
 - Stemcell builder extraction
 - Stemcell extraction

## Conclusions
 - Leave your contracts loose...but not too loose.
 - Systems programming geeks arise!
 - TDD systems programming what?
 - BOSH will deploy all the things on all other things...eventually.

## Suggested Track
 - Cloud Computing
 - Tools and Techniques

