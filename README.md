# Introduction

This repository contains a number of example transformations for the Kettle Beam project

# Required

## The kettle-beam plugin

Download a recent release: https://github.com/mattcasters/kettle-beam
Follow installation and configuration instructions in README.md.
Look at an overview blog post: http://diethardsteiner.github.io/pdi/2018/12/01/Kettle-Beam.html
 
## The pentaho-pdi-dataset plugin

Download this plugins over here: https://github.com/mattcasters/pentaho-pdi-dataset
No need to configure anything, everything needed is included in this project.

# Optional

## The kettle-environment plugin

This makes it easier to configure your working environment.
Download it at: https://github.com/mattcasters/kettle-environment
You can also skip this and configure the variables yourself, see below for details.

## The GitSpoon plugin 

Download it at: https://github.com/HiromuHota/pdi-git-plugin
You can also use command line tools to do use git.

# Configure

If the this folder is located in ```<SAMPLES>```

Create a Kettle Environment with the following minimal settings:

* Metastore base folder set to ```<SAMPLES>``` or set ```PENTAHO_METASTORE_FOLDER```
* Unit tests base path set to ```<SAMPLES>``` or set ```UNIT_TESTS_BASE_PATH```
* Data Sets CSV folder set to ```<SAMPLES>/datasets``` or set ```DATASETS_BASE_PATH```

# Run all tests

Run the transformation ```run-all-tests.ktr```

# Run on Beam

The Direct Beam Job Configuration is working with these examples.
To run on Dataflow or Spark you need to configure the Job Configurations and your environment.




