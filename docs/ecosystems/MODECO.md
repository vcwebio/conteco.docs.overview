[`Back to docs.overview`](../README.md) >> [`The Ecosystems`](../THE-ECOSYSTEMS.md) >> ModEco Ecosystem in Detail

-----
# ModEco Ecosystem in Detail

The __ModEco__ ecosystem consists of functional modules. These modules are configured from sets of __ContEco__ container images.

## Configuration

The module configuration can be found in the `/modeco` folder and consists of:
* _settings files_ in the root of the folder
* _service stack docker-compose.yml_ in the `stacks/` subfolder
* _application configuration_ in the `configs/` subfolder
* _volume initialisation_ in the `volumes/` subfolder

### Module Settings

There are three levels of settings:
* _settings.template_ and _stacks/*.docker-compose.yml.template_ containing the configuration of the __ContEco__ stacks
* _settings.base_ and _stacks/*.docker-compose.yml_ containing the base settings of the module
* _settings_ containing the module specific settings



## Base Template Library


-----
[`Back to docs.overview`](../README.md) >> [`The Ecosystems`](../THE-ECOSYSTEMS.md) >> ModEco Ecosystem in Detail
