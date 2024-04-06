# Changelog of CUPP

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## 4.0.0
- Rename to x-cupp (eXtended-Common User Password Profiler)
- Remove functions to make it generate only based on interactive mode
- Change ascii
- Refactored Cupp to remove redundant code and implement a more efficient solution by reducing complexity
- Add various other password patterns to combination generated
- Added support for the `-d` argument .
  - This argument allows users to run x-cupp with a default set of options, skipping the interactive question process.
  - When using the `-d` argument, users are required to provide a name for the targeted individual or entity.
- Increase config's numsto from 100 to 10000

## 3.2.0-alpha

 - ran 2to3 on cupp.py to make it Python3 compatible

## 3.1.0-alpha
 - added Python3 port
 - Bugfixes

## 3.0.0
 - added word length shaping function
 - added wordlists downloader function
 - added alectodb parser
 - fixed thresholds for word concatenations
 - fixed sorting in final parsing
 - fixed some user input validations
 - ascii cow now looks nicer :)

## 2.0.0
 - added l33t mode
 - added char mode
 - ability to make pwnsauce with other wordlists or wyd.pl outputs
 - cupp.cfg makes cupp.py easier to configure 


## 1.0.0
- Initial release

