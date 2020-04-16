submassive
==========

Data collection utility for submitting network state date of CRXN to collectd.

## Usage

Run as follows, where `<configFile>` is the JSON file with the parameters
for your submassive node.

````
./submassive <configFile>
````

## Build

Make sure you havr `dmd` and `dub` installed, then run the following:

````
dub build
````