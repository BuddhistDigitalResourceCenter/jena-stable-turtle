# Jena Stable Turtle output plugin

This repository contains code to define a new [RDF Writer](https://jena.apache.org/documentation/io/rdf-output.html) for [Jena](https://jena.apache.org/) which is turtle always sorted in the same way. It has been developped to reduce the diff noise when the data is stored on a git repository, we are confident there are plenty of other use cases where it will be useful.

### Changes from the stock turtle output

## Installation

TODO

## Use

TODO

## Change log

## License

All the code on this repository is under the [Apache 2.0 License](LICENSE). 

The original parts are `Copyright © 2017 Buddhist Digital Resource Center`, and the file `TurtleShell.java` (coming from the [Jena repository](https://github.com/apache/jena/blob/master/jena-arq/src/main/java/org/apache/jena/riot/writer/TurtleShell.java)) is `Copyright © 2011-2017 Apache Software Foundation (ASF)`, see [NOTICE](https://github.com/apache/jena/blob/master/NOTICE) for more information.