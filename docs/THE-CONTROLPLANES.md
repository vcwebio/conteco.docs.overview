[`Back to docs.overview`](../README.md) >> The Controlplanes

-----
# The Controlplanes

## API Sections

All controlplanes share the same top level API structure.  
It consists of 5 live cycle sections - __config__, __build__, __release__, __deploy__ and __run__, repository management - __repo__ and __console__.

All sections contain methods that execute within the context of a repository, except for console which is specifically for methods that execute without repository context.

The __console__, __repo__, __build__ and __release__ sections plus part of __config__ are shared by all controlplanes.

## Controlplane overview

All controlplanes shares common repository configuration and management methods and implement config methods specific to the layer.

All controlplanes share the same build and release methods.

### ContEco Controlplane

Configuration of:
* the container wrapper
* setup of the container image applications - structural interactions & default settings
* service stack assets: docker-compose.yml & environment

[The ContEco Controlplane in Detail](./controlplanes/CONTECO.md)

### ModEco Controlplane

Configuration of:
* input and output of the module container set
* UI of the module
* functional configuration of container applications

[The ModEco Controlplane in Detail](./controlplanes/MODECO.md)

-----
[`Back to docs.overview`](../README.md) >> The Controlplanes
