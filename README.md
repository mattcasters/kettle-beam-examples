# kettle-beam-examples

Example transformations for the Kettle Beam project

## Required

* The kettle-beam plugin
* The pentaho-pdi-dataset plugin

## Optional

* The kettle-environment plugin
* The GitSpoon plugin 

## Configure

If the this folder is located in ```<SAMPLES>```

Create a Kettle Environment with the following minimal settings:

* Metastore base folder set to ```<SAMPLES>``` or set PENTAHO_METASTORE_FOLDER
* Unit tests base path set to ```<SAMPLES>``` or set UNIT_TESTS_BASE_PATH
* Data Sets CSV folder set to ```<SAMPLES>/datasets``` or set DATASETS_BASE_PATH

## Run all tests

Run the transformation ```run-all-tests.ktr```


