# An Overview of vcWEB Container and Module Ecosystem Orchestration

This platform is all about the orchestration of container image and module ecosystems that culminate into applications and solutions.

It starts with container ecosystems, structured sets of containers providing the desired interactions for the application within. This is managed by the ContEco controlplane.

The output of the ContEco controlplane is a base image of a functional module. The ModEco controlplane manages the configuration of the containerised applications, and their deployment and operation. 

These functional modules are the building blocks of containerised applications and solutions.

## Aim

This platform aims to provide an orchestration tool that is well suited for flexible and reproducible Proof of Concepts that can then evolve into  software solutions.

## WARNING

The platform is in its early stage of development, so lots remains under construction.  
But there should already be enough to be of interest to an inquisitive mind.

## Where to Start

Nothing better than seeing some action.  
The easiest way in is to start up the ModEco controlplane and try out some of the functional modules.

## In A Nutshell

It's all about containers which are the elementary building blocks of the platform. Like DNA in cells they carry the associated repository within.  
These containers all have a common wrapper governing their interactions within the ecosystem.   
And the controlplane associated with the ecosystem brings it all to life.

## Enjoy

More complete documentation should become available over time, but for now start your journey with the ModeEco or ContEco controlplane. Check out a few repositories and get a sense of the full(er) picture.

More documentation is available from the `conteco.docs` images, while the controlplane implement a `--help` flag for the API.

