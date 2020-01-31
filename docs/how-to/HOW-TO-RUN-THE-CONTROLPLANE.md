[`Back to docs.overview`](../../README.md) >> [`How To`](../HOW-TO.md) >> How To Run the Controlplane

-----
# How to Run the Controlplane

Interactive use of the controlplane is done using the CLI.  
The CLI has its own image - controlplane.cli - and it comes with full instructions.

Controlplanes can also be driven by automated processes.

## Extraction of the  Controlplane CLI

Extraction of the CLI scripts is a multistep process which is self-explanatory.  
Simply create a working folder and open a console.  
Do 'docker run' on the image and follow the instructions:

```bash
docker run vcwebio/conteco.controlplane.cli
```

It will first instruct you how to run the image with required volumes and arguments.  
Following this it will proceed to generate the script files.

There are additional instructions with regards to the required data volume (v2 only).  
Under normal use, just continue using the existing volume.

## CLI Command Structure

CLI v1: [controlplane] [section] [[method] [arguments]] [repository selector]

CLI v2: [controlplane] [repository selector] [section] [[method] [arguments]]

## Repository Selection

The CLI allows to work on more than one image repository at a time.  

Repositories are selected using type - CONTECO_TYPE - and name - CONTECO_NAME - only.
The context supplies the registry prefix - CONTECO_REGISTRY -, the realm - CONTECO_REALM_RUNTIME - and the ecosystem - CONTECO_ECOSYSTEM_RUNTIME.  

The repository selector allows for prefix wild-carding, there is no need to add * in order to achieve this.  
However, in order to indicate an exact repository you must end the selector in $.

## API Sections

There is a fixed set of API sections which are the same for all controlplanes.  
console - repo - config - build - release - deploy - run
All sections run within the context of an image repository, except for 'console' which is for global actions.  

Note that not all controlplanes implement all sections - e.g. deploy and run.  
And some sections are the same across all controlplane - repo, build and release.  
The config section is part inherited and part implemented by each controlplane.

Specific API information for a controlplane can be found in the resp. controlplane repository.  
For more general information on the controlplane, see information on the ecosystem that a specific controlplane acts upon.

-----
[`Back to docs.overview`](../../README.md) >> [`How To`](../HOW-TO.md) >> How To Run the Controlplane
