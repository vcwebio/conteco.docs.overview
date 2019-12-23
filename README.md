# `docs.overview` - vcWEB Platform: Building Solutions from Container and Module Ecosystems

This platform is about the orchestration of modules and containers organised in ecosystems with the aim to create and manage containerised solutions.

__ContEco__  
The container ecosystem provides structure to sets of containers. These are then cast into modules. The container ecosystem is managed by __controlplane.conteco__.

__ModEco__  
The module ecosystem is concerned with configuring the applications that installed within the containers of the module. It is managed by __controlplane.modeco__.

__SolEco__  
Modules are combined together into solution.

__InfoMetis__
Bringing the different layer together under a single umbrella.

## WARNING

The platform is in its early stage of development, with lots under construction.  
But there should already be enough to be of interest to an inquisitive mind.

## Where to Start

Nothing better than seeing some action.  
The easiest way in is to start up the ModEco controlplane and try out some of the functional modules. See `conteco.docs.modeco` for more details.

## In A Nutshell

Containers are the elementary building blocks of the platform. Like DNA in cells they carry the associated repository within.

These containers all have a common wrapper governing their interactions within the ecosystem.

And the controlplane associated with the ecosystem brings it all to life.

## Enjoy

More complete documentation should become available over time, but for now start your journey with what can be found in `conteco.docs.conteco` and `conteco.docs.modeco` to find out more about these ecosystems. Check out a few repositories and get a sense of the full(er) picture.

More technical documentation can be found within the container image repositories. The most significant for the platform are `conteco.image.wrapper`, `conteco.controlplane.conteco` and `conteco.controlplane.modeco`.

All feedback is welcome - conteco@vcweb.io.
