# GloSAT LATsdb

This repository contains information about the GloSAT land near-surface air temperature station database (GloSAT LATsdb)

### What is GloSAT LATsdb?

It is a database of monthly air temperatures over land from weather stations used to generate the gridded GloSAT global temperature datasets, as part of the GloSAT project.

This station database was developed from the CRUTEM5 station database used for the gridded CRUTEM5 and HadCRUT5 global temperature datasets (see: https://crudata.uea.ac.uk/cru/data/temperature/) but extended back to 1781, with the inclusion of additional data acquisitions, the application of an adjustment to reduce biases due to changing thermometer screens, and with the use of local expectation kriging to help estimate normals where a station has incomplete data during the 1961-1990 baseline.

### Source code information including homogeneity indicators

GloSAT LATsdb uses the same two-digit Source Codes that were used by CRUTEM5.0:

- Text format [source-codes/crutem2digit_sourcecodes.txt]
- CSV format https://github.com/TimOsbornClim/GloSAT-LATsdb/blob/main/crutem2digit_sourcecodes.csv
- TSV format https://github.com/TimOsbornClim/GloSAT-LATsdb/blob/main/crutem2digit_sourcecodes.tsv


