# Hubot GO transit alerts

hubot script to display GO (Toronto transit) alerts

## Inspiration

This script is heavily inspired by the [TTC Alerts](github.com/hubot-scripts/hubot-ttc-alerts.git) script

## Installation

### Update the files to include the hubot-go-alerts module:

#### package.json
    ...
    "dependencies": {
      ...
      "hubot-go-alerts": ">= 0.0.1"
      ...
    },
    ...

#### external-scripts.json
    [...,"hubot-go-alerts"]

Run `npm install` to install hubot-go-alerts and dependencies.

## Commands

```javascript
hubot go me
```

## Directory Structure

Using the common directory structure for hubot script packages it will be easy
to manage and allow others to easily contribute to your package.

### script

This directory is home to a couple of development scripts; `bootstrap` and `test`
they're used to bootstrap the development environment and run tests
respectively.

### src

This directory is home to the actual hubot scripts in the package. Your
`index.coffee` entry point will load the scripts from this directory.

### test

This directory is home to any tests you write for your scripts. This example
package uses Mocha, Chai and Sinon to manage writing tests.
