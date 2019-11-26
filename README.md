# An Overview of vcWEB Container and Module Ecosystem Orchestration

This platform is all about the orchestration of container image and module ecosystems that culminate into applications and solutions.

It starts with container ecosystems, structured sets of containers providing the desired interactions for the application within. This is managed by the ContEco controlplane.

The output of the ContEco controlplane form the basis of a functional module, where the containerised applications are configured to satisfy the functional requirements of the module. This ecosystem is managed by the ModEco controlplane. 

These functional modules are the building blocks of containerised applications and solutions.

## Aim

This platform aims to provide an orchestration tool that is well suited for flexible and reproducible Proof of Concepts that can then evolve into  software solutions.

## WARNING

The platform is in its early stage of development, so there is lots under construction and missing.

But there should already be enough to be of interest to an inquisitive mind.

## Where to Start

Nothing better than seeing some action.  
The easiest way in is to start up the ModEco controlplane and try out some of the functional modules.

## In A Nutshell

### It's All About Containers

The __container__ is the elementary building block of the platform, look at is as a __cell__.

A __container__ is built from an associated __repository__, look at it as its __DNA__. 

### And Local Interaction

Each __container__ contains a common __wrapper__ governing how the __container__ interacts with its (local) environment.

This environment has more than one facet. For instance, there is the __cluster node__ that the __container__ runs on and the __repository__ that it is built from.

### And Messaging Between

The __controlplane__ brings it all to life through the __management APIs__ it implements.

## Enjoy

There will be a more formal contents overview later on, but for now start your journey with __controlplane.base__ and __container.wrapper__
to get a sense of the full(er) picture.

