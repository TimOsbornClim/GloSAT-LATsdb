# GloSAT LATsdb

This repository contains information about the GloSAT land near-surface monthly air temperature station database (GloSAT LATsdb)

## What is GloSAT LATsdb?

It is a database of monthly air temperatures over land from weather stations used to generate the gridded GloSAT global temperature datasets, as part of the [GloSAT project](https://glosat.org).

This station database was developed from the CRUTEM5 station database used for the gridded CRUTEM5 and HadCRUT5 global temperature datasets (see: [https://crudata.uea.ac.uk/cru/data/temperature/](https://crudata.uea.ac.uk/cru/data/temperature/)) but extended back to 1781, with the inclusion of additional data acquisitions, the application of an adjustment to reduce biases due to changing thermometer screens, and with the use of local expectation kriging to help estimate normals where a station has incomplete data during the 1961-1990 baseline.

## Data Source Code information (including Homogeneity Indicators)

#### Data Source Codes

GloSAT LATsdb uses the same two-digit Data Source Codes that were used by CRUTEM5.0.
A Data Source Code is provided for each station in the database, to indicate where the data for a station was obtained from.

> [!NOTE]
> Only an overall source code is given for each station, which indicates the dominant source.
> For some stations, all values will have come from that single source.
> For other stations, values will have come from multiple sources, and the overall source code just indicates the dominant source.

The CRUTEM 2-digit Data Source Code table gives details about each Data Source Code.
This table corresponds to the two-digit source codes used in CRUTEM5 and in some related datasets (e.g. GloSAT LATsdb v1.0.0.0).

- Text format [source-codes/crutem2digit_sourcecodes.txt](source-codes/crutem2digit_sourcecodes.txt)
- CSV format [source-codes/crutem2digit_sourcecodes.csv](source-codes/crutem2digit_sourcecodes.csv)
- TSV format [source-codes/crutem2digit_sourcecodes.tsv](source-codes/crutem2digit_sourcecodes.tsv)

#### Homogeneity Indicators

The Data Source Code table includes a Homogeneity Indicator for each data source.

For each data source, we conducted a broad-brush assessment of whether we judge that the data provider carried out a homogeneity assessment (and possibly applied adjustments to reduce inhomogeneities). Based on this, we assigned one of five homogeneity indicators to each data source:

<dl>
 <dt>HOM00</dt>
 <dd>Homogeneity has not been assessed or is unknown.</dd>
  <dt>HOM01</dt>
 <dd>Homogeneity not assessed, but data comes from a reliable source (e.g. an NMS or WWR) that probably checked for obvious problems (in the sense that series with obvious problems would have been removed).</dd>
  <dt>HOM02</dt>
 <dd>Homogeneity assessed and inhomogeneities corrected at source (by NMS or a regional effort in e.g. Nordic countries, China etc.) but method details were not available to us.</dd>
  <dt>HOM03</dt>
 <dd>Homogeneity assessed and inhomogeneities corrected at source via documented methods.</dd>
  <dt>HOM04</dt>
 <dd>Homogeneity assessed and inhomogeneities corrected by CRU using documented methods.</dd>
</dl>

> [!CAUTION]
> These indicators need to be treated with caution for various reasons: (i) we have not assessed the homogeneity of the data, we only considered what the data provider is likely to have done; (ii) only one homogeneity indicator is applied to each data source code to give a broad-brush indication, so it is possible that the data provider homogenised some but not all of their stations; (iii) some stations may be formed by combining data from multiple sources/providers but only one can be indicated; (iv) homogenisation may have been carried out only for a subset time period and data outside that period may not have been homogeneity assessed/adjusted. 

Alongside the homogeneity indicator, the approximate start and end years of the period to which homogenisation may have been applied (in some cases this may be unknown or too complex to express as a simple start and end year) and any further comments are provided.


