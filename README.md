# eslint-plugin-view-models

This package simply imports and exports `view-models/eslint-plugin` at whichever version you are using.

Documentation for this plugin can be found [here](https://github.com/asbjornh/viewmodels/blob/master/docs/eslint-plugin.md).

## Why a proxy plugin?

Because with eslint the only way to load a plugin is to create an npm package with a name starting with `eslint-plugin-`. In order to ensure that this eslint plugin tracks the correct version of `view-models`, the source code for the plugin lives there.
