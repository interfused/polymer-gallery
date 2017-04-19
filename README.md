# Polymer Gallery (polymer v2)
The purpose of this basic app is to test polymer and component based architecture. This gallery components project takes a JSON formatted file and creates categorized tabs. Additionally, allows for custom shared styles and filters content based off of a selected category. Though the existing polymer components set available at is far more dynamic stylistically, the purpopse of this exercise was to create polymer elements from scratch and be able to modify / theme accordingly.

For more information on polymer, please visit the [Polymer Project](https://www.polymer-project.org/) 

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
