# syntect resources

This repo contains default language definitions and other resources used by various components of the xi-editor project.

To get a new syntax definition working in xi:
- add the syntax to this repository
- update the submodule in the xi-syntect plugin
- run `make assets` in the xi-syntect plugin
- build the plugin and/or commit and PR the new manifest and submodule.
