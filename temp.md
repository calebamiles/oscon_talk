#### BOSH Goals

BOSH has the near herculean goal of solving two rather complex problems: as a
software deployment operator how do I programmatically create an ensemble of
clusters from a disparate collection of software; and how can I, as a software
packager or developer, package software once and run anywhere regardless of
what infrastructure is being targeted, and in a perfect world, what platform is
being utilized. Through contracts between the target platform and 
infrastructure, BOSH releases allow software packagers to ship their software
with batteries included to any combination of supported infrastructure and
platform.

#### Abstracting the operating system

The various contracts between the platform and infrastructure which allow BOSH
to facilitate controlled interactions between components of a BOSH release, 
the infrastructure and the platform were all fulfilled by Ruby classes embedded
in the BOSH code base which had the effect of pushing the logic required to do
simple things such as configuring network settings into the BOSH Agent which
makes supporting additional Operating Systems as platforms much more difficult
than it should be. It is also somewhat unclear what the contract is between the
BOSH Agent and the platform since so much logic about platform particulars was
contained in the Agent. 

The philosophy of creating simple programs that do a particular job well is
perhaps even more relevant as software deployments We have often found that 
a system composed of many small components is easier to test drive and
we do hope that it will also empower the community to extend and maintain BOSH
in an ever growing collection of environments from containers on baremetal to
Raspberry Pi federations.

- Go Agent driver of decomposition
  * removing BOSH agent functionality from the codebase

#### CPI Extraction

Improving and extracting the acceptance suite for IaaS developers serves two
related purposes. First, the extraction helps to decouple testing and 
implementation which have a way of naturally growing into each other. 
Second, as an executable contract, the BOSH acceptnce tests guide future 
IaaS developers the information they need to make their resources available to
BOSH.


