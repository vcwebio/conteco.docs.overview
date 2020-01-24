# `docs.overview` - vcWEB Platform - Infometis

This platform is about the orchestration of modules and containers organised in ecosystems with the aim to create and manage containerised solutions running on clusters.  
InfoMetis - the top layer - brings all these ecosystems into a platform.  
Each ecosystem is managed by its own controlplane - see [The Ecosystems](./docs/THE-ECOSYSTEMS.md) and [The Controlplanes](./docs/THE-CONTROLPLANES.md) for more details.

* __ContEco__ - providing structure to sets of containers, managed by __controlplane.conteco__.
* __ModEco__ - creating functional modules, managed by __controlplane.modeco__.
* __SwarEco__ - creating and running clusters, managed by __controlplane.swareco__.
* __SolEco__ - creating and running containerised solutions, managed by __controlplane.soleco__.
* __InfoMetis__ - the platform.

## Warning

The platform is in its early stage of development, with lots under construction.  
But there should already be enough to be of interest to an inquisitive mind.  
__ContEco__ and __ModEco__ are nearing completion, and development is being started on __Swareco__ and __SolEco__.

## Where to Start

Nothing better than seeing some action. Start up the __ModEco__ controlplane and try out some of the functional modules.  
See [How to Run the Controlplane](./docs/how-to/HOW-TO-RUN-THE-CONTROLPLANE.md)] and [How to Run a Module](./docs/how-to/HOW-TO-RUN-A-MODULE.md)] for more details.  
The [How To](./docs/HOW-TO.md) will be the place to go to find practical hands-on information - it is currently under construction.

## In A Nutshell

Containers are the most elementary building blocks of the platform. Like DNA in cells they carry their build-code within.  
All have a common wrapper governing their interactions within the ecosystem.  
These structures are used to create [ModEco Modules](./docs/THE-MODECO-MODULE.md), the functional buildings block to create SwarEco clusters and SolEco solutions.
And at every stage there is a controlplane to bring the ecosystem to life.

## Enjoy

Documentation should improve over time, with the main documentation to be found here.  
More technical documentation can be found within the container image repositories. The most significant for the platform are `conteco.image.wrapper` and the controlplanes, e.g. `conteco.controlplane.conteco` and `conteco.controlplane.modeco`.

All feedback is welcome - conteco@vcweb.io.
