# Slim loader for Webpack

Import .slim files as modules in your webpack project. Returns a rendered template.

## Setup

Add to your webpack config module.loaders:

````
{ test: /\.html\.slim$/, loader: "slim" }
````
