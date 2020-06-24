# Getting Started

## Get and build Meshlab

''
$ sudo apt install libgl1-mesa-dev
$ sudo apt install qt5-default libxml5patterns5 libxml5patterns5-dev qtscript5-dev
$ sudo apt install jq
$ mkdir ~/metaspace
$ cd metaspace
$ git clone --recursive https://github.com/cnr-isti-vclab/meshlab
$ cd meshlab
$ cmake src/
$ make
''

## Get and build Open-Asset-Importer-Library

''
$ cd metaspace
$ git clone git@github.com:assimp/assimp.git
$ cd assimp
$ cmake CMakeLists.txt
$ make
''
# nightguard.sh

Processes all steps for each directory.

# Process Steps

## 000

Automated step: STL files of scans.

## 100

Manual step: Z-Paint the faces to be deleted (black). Save as PLY format.

## 200

Automated step: Execute '200.sh /path/to/folder/af00'

## 300

Automated step

## 400

Automated step
