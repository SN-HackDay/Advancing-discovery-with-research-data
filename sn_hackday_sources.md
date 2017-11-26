### `SciGraph Linked Data`

RDF repository containing bibliographic metadata for complete Springer Nature archive: 7M journal articles and 4M book chapters (including abstracts), grants related to these articles, subject tags, disambiguated affiliation data using GRID institutions identifiers, and mappings to other ontologies and taxonomies.  

[SciGraph Downloads](http://scigraph.springernature.com/explorer/downloads/)

[SciGraph Data Explorer](http://scigraph.springernature.com/explorer/)

[SPARQL Queries Examples](https://github.com/springernature/scigraph/tree/master/2017Q2/hackday-2017-06-23/examples/graphdb)

[Tech recipe: Exploring SciGraph data using JSON-LD, Elastic Search and Kibana](http://www.michelepasin.org/blog/2017/04/06/exploring-scigraph-data-using-elastic-search-and-kibana/)

> Note: this datasets are only available as RDF (N-Triples) downloads. They requires a triplestore (e.g. http://graphdb.ontotext.com is freely available) to load the data before processing.

### `Fulltext (xmldata) API`

Provides metadata and full-text content where available for almost 12 million online documents. It contains Springer Journals and Books (including BMC), Palgrave Books and Journals

[Sign-up](https://dev.springer.com/)

Example:

[http://api.springer.com/xmldata/app?q=book:%22Advances%20in%20Cryogenic%20Engineering%22&api_key=<your_key>&s=1&p=3](http://api.springer.com/xmldata/app?q=book:%22Advances%20in%20Cryogenic%20Engineering%22&api_key=<your_key>&s=1&p=3)

### `Springer Metadata API`

Provides metadata for almost 12 million online documents (e.g., journal articles, book chapters, protocols). It contains Springer Journals and Books (including BMC).

[Sign-up](https://dev.springer.com/)

Example:

[http://api.springer.com/metadata/json?q=doi:10.1007/s10404-009-0428-3&p=2&api_key=<your_key>](http://api.springer.com/metadata/json?q=doi:10.1007/s10404-009-0428-3&p=2&api_key=<your_key>)

### `Springer Meta API` 
Provides new versioned metadata for almost 12 million online documents (e.g., journal articles, book chapters, protocols). It contains Springer Journals and Books (including BMC).

[Sign-up](https://dev.springer.com/)

Example:

[http://api.springer.com/meta/v1/json?q=doi:10.1007/s10404-009-0428-3&p=2&api_key=<your_key>](http://api.springer.com/meta/v1/json?q=doi:10.1007/s10404-009-0428-3&p=2&api_key=<your_key>)

### `Springer Open Access API`

Provides metadata and full-text content where available for more than 460,000 online documents. It contains Springer Journals and Books (including BMC). 

[Sign-up](https://dev.springer.com/)

Example:

[http://api.springer.com/openaccess/app?q=doi:10.1007/s40204-015-0036-0&api_key=<your_key>](http://api.springer.com/openaccess/app?q=doi:10.1007/s40204-015-0036-0&api_key=<your_key>)

### `Integro API`

Provides a means to access information about Springer’s journals (e.g., Information about the journal’s title, publisher, DOI, subject groups, dates of publication).

[Sign-up](https://dev.springer.com/)

Example:

[http://api.springer.com/integro/v1/journaltitlesheet/10288?api_key=<your_key>](http://api.springer.com/integro/v1/journaltitlesheet/10288?api_key=<your_key>)

### `Datacite REST API`

The DataCite REST API allows users to retrieve, query and browse DataCite DOI metadata records. The API is generally RESTFUL and returns results in JSON, and the API follows the JSONAPI specification. 

[Access API](https://api.datacite.org/)

### `Figshare API`

Item and collection-level metadata for all data in figshare, including Springer Nature reseach data.

[More](https://docs.figshare.com/#figshare_documentation_api_description)

Examples:
https://drive.google.com/file/d/1BvimvODkWZ34boqf1PpFgeiHTJh99MBQ/view?usp=sharing

### `Crossref API`

Crossref REST API exposes the metadata that publishers provide Crossref when they register their content with us. And it’s not just the bibliographic metadata either. Funding data, license information, full-text links, ORCID iDs, abstracts, and Crossmark updates, are all available, if included in the publishers’ metadata.

[More](https://www.crossref.org/services/metadata-delivery/rest-api/)

### `EU PubMed Central OAI`

The Europe PMC OAI service, (Europe PMC-OAI) provides access to metadata of all items in the Europe PMC archive, as well as to the full text of a large subset of these items.

[More](https://europepmc.org/OaiService)

### `EU PubMed Central Open Access subset`

The PMC Open Access Subset is a part of the total collection of articles in PMC. The articles in the OA Subset are made available under a Creative Commons or similar license that generally allows more liberal redistribution and reuse than a traditional copyrighted work. Automated (or bulk) retrievals of article data (XML for full text, images, PDF, and supplementary data files) are possible from the OA Subset.

[More](https://www.ncbi.nlm.nih.gov/pmc/tools/openftlist/)

### `Registry of Research Data Repositories (re3data) API`

re3data.org supports the retrievial of its content about repositories via API. Currently the platform offers a simple open search implementation as well as a first version of a RESTful interface.

[Access API](https://www.re3data.org/api/doc)

### `Academic Knowledge API | Microsoft Azure`

Tap into the wealth of academic content in the Microsoft Academic Graph using the Academic Knowledge API.

[More](https://azure.microsoft.com/en-gb/services/cognitive-services/academic-knowledge/)

