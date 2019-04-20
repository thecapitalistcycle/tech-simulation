# Economic Statistics

## Glossary

Use OECD glossary:

https://stats.oecd.org/glossary/download.asp

Downloads are based on old SNA. Check for updates from:

1. Online version continuously updated:

https://stats.oecd.org/glossary/index.htm

2. Handbook for SUT and IOT (2018)

3. Latest SNA and proposed changes.

## Statistical Data and Metadata Exchange - SDMX

https://sdmx.org/?page_id=5008

Use for both input to and output from simulation models and games.

Note:

1. EURACE appliance has full python data stack for visualizing ABM output.

2. JupyterLab with Bokeh then later just static pages.

3. Python quant tools.

### Validation and Transformation Language

VTL 2.0 included in SDMX has user oriented information model and language.

### Update 2019-04-20 relevant to

https://github.com/axfreeman/Economic-History

pandas is the heart of the python data stack which is now dominant for data researchers (covers everything that previously made R and matlab dominant)

SDMX is the standard for statistical data

List of tools here:

https://sdmx.org/?page_id=4500

Most comprehensive client software is based on pandas:

https://pandasdmx.readthedocs.io/en/latest/

Note that readthedocs supports many software packages, especially python based. Each has downloads for latest docs in pdf, epub and html formats. 

pandasdmx can convert to and from pretty well everything (spreadsheets, databases etc) using odo:

https://odo.readthedocs.io/en/latest/

Note that this includes sparksql. But no relation to SPARQL used by Wikidata for RDF triples in wikipedia:

https://en.m.wikipedia.org/wiki/SPARQL

Java/.NET based Web service provider infrastructure:

https://ec.europa.eu/eurostat/web/sdmx-infospace/sdmx-it-tools/sdmx-ri

Simpler approach is to just use peer to peer git for efficient dissemination of tsv data and json/yaml meta data using diffs.

Can be extended to automated update distribution with user friendly package managers and easily maintained repositories similar to software distributions for Linux, Mac, Windows, Android and iOS.

Oddly I haven't noticed a python module for VTL although it should be easier to do. But there are others freely available which can of course work with the pandas/odo data formats above.

https://www.google.com/search?q=validation+and+transformation+language+tools

