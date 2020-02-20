[`Back to docs.overview`](../../README.md) >> [`How To`](../HOW-TO.md) >> How To Create and Configure a Module

-----
# How to Create and Configure a Module

A __ModEco__ module is defined by the CONTECO_TYPE name part.
The CONTECO_NAME name part contains the name of the module package.  

## Module Settings

__CONTECO_DC_GLOBAL_BASE_LIST__ - required  
The list of all the ContEco sets that make up the module package.
This determines the service stacks that are imported under the _.template_ extension.

__CONTECO_DC_GLOBAL_BASE_LIST_STACKS__ - generated  
This list is automatically generated and contains the number of service stacks of the __ContEco__ set.

__CONTECO_DC_GLOBAL_STACKNAMES_BASE__ - generated  
The list of service stack BASE names. These are the default names for the module service stacks.

__CONTECO_DC_GLOBAL_STACKNAMES__ - optional / prepopulated  
The list of service stack names as in use by the module. Often these will be different from the default BASE name.

__CONTECO_DC_GLOBAL_BOOTSTACKS__ - optional / prepopulated  
The list of service stacks flagged as module BOOT stacks.  
BOOT stacks are service stacks that require to be up and running first.

__CONTECO_DC_GLOBAL_RUNSTACKS__ - optional / prepopulated  
The list of service stacks flagged as module RUN stacks.  
RUN service stack must be started after the BOOT stacks.

__CONTECO_DC_GLOBAL_VOLUME_LIST__ - generated  
The list of volumes in use by the service stacks.

__CONTECO_DC_GLOBAL_VOLUME_INITIALISED__ - optional  
The list of volumes to be initialised prior to starting the associated service stacks.

-----
[`Back to docs.overview`](../../README.md) >> [`How To`](../HOW-TO.md) >> How To Create and Configure a Module
