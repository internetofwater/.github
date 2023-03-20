The [Internet of Water](https://internetofwater.org) is a multi-stakeholder project to create an ecosystem of water data providers that publish their data in a FAIR (Findable, Accessible, Interoperable, and Reusable) manner. The Internet of Water includes a suite of open source software development and data curation activities to assist in the publication and indexing of water data. These activities are managed by the [Center for Geospatial Solutions at the Lincoln Institute of Land Policy](https://cgs.earth)

Open Source Projects that we manage on GitHub include:

1. [Glossary](#Glossary): An ontology of water science, data, and policy-related concepts.
2. [Water Budget Framework](#Water-Budget-Framework): An ontology of water budgeting components, estimation methods and models, model parameters, and data sources required to build water budgets.
3. [Data Inventories](#Data-Inventory): We conduct data inventories of the Federal and State governments, systematically identifying which government departments and agencies collect water data, and the discoverability, accessibility, and interoperability of the data they publish.
4. [geoconnex.us](#geoconnex.us). Infrastructure to support the publication of structured metadata on the web about hydrologic features, including persistent identifiers, spatial data infrastructure, structured data harvesting, and knowledge graph curation, management and publication
5. [HubKit](#hubkit) A suite of existing open source software projects designed to allow users to publish geospatial and tabular time-series water sensor or modeled output data using open data and API standards as published by the Open Geospatial Consortium

## Glossary

The glossary is managed with [vocbench3](https://purl.org/iow/vocbench3) in an ontology that assigns URIs to unique concepts corresponding to unique definitions. So, terms with conflicting definitions by different organizations are encoded as unique concepts that have a semantic relationship to the same term, which is a unique concept on its own.

The current glossary can be browsed at <https://purl.org/iow/Glossary> (currently for demo purposes only)

The glossary GitHub repository is <https://github.com/internetofwater/glossary>

The underlying ontology is stored in the graph database <https://purl.org/iow/vocbench3/graphdb>


## Water Budget Framework

The water budget framework is an ontology of 5 major concepts:

1. Water Budgeting Framework Developer: Entities that have developed and published frameworks to estimate water budgets. So far, included developers include the [USGS](www.usgs.gov), [California Department of Water Resources](https://water.ca.gov/), and [Utah Department of Water Resources](https://water.utah.gov/).

2. Water Budget Compenent: The distinct flows of water into, out of, and within a given water budgeting zone.

3. Estimation Methods: The methods documented to be in use in estimating water budget components

4. Parameters: The inputs to estimation methods, generally represented by single variables in an estimating model.

5. Data Resources: Sources of raw or modeled data that have been documented to serve as parameters

## Data Inventories

See at <https://internetofwater.org/resources/inventory/>
Code to conduct data inventories is at <https://github.com/internetofwater/DataInventory>


## geoconnex.us

geoconnex is a suite of many interrelated open source tools and infrastructure, with development managed on GitHub. See [about.geoconnex.us](https://github.com/internetofwater/about.geoconnex.us)

## hubkit

[HubKit](https://github.com/internetofwater/HubKit) combines custom UIs to map csv files to the [SensorThings](https://github.com/opengeospatial/sensorthings) data model, a customized deployment of the [FROST](https://fraunhoferiosb.github.io/FROST-Server/) open source database and API implementation of SensorThings API, and a customized deployment of [pygeoapi](https://pygeoapi.io) to provide an OGC-API Features interface to SensorThings data and publication of JSON-LD structured metadata compliant with the geoconnex.us [harvester](https://github.com/internetofwater/harvest.geoconnex.us).
