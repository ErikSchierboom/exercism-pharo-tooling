# Exercism Pharo Tooling

## This Reposititory is no Longer Maintained
The tooling for the Pharo language track is maintained alongside the exercises in the [exercism/pharo](https://github.com/exercism/pharo) repository. Please go there for all issues, queries and contributions.

## Summary
This repository contains tools that help to integrate the Smalltalk and Pharo way of programming into the Exercism workflow.

## Tools

### Exercism
This tool exports Smalltalk code out of the Pharo image and into text files, ready to be pushed to Exercism.io by the exercism
command line tool.

#### Usage
Inside the Playground send the message `exportClass:` to the `Exercism` class with the class containing the code to be 
exported as the argument:

```smalltalk
Exercism exportClass: HelloWorld
```

## Licence
This repository is under the MIT licence with the copyright to Exercism, Inc.
