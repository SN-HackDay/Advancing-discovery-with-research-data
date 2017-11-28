
# **Themes, use cases and ideas for hacks**

*You can also find the information in this section in this Google doc (feel free to edit):* https://docs.google.com/document/d/1A9IAjBqXZQjrPdwnrDC3DjLWs-mdkUrB8lbvmVGdY0E/edit?usp=sharing

## `General themes`

* Data linking
  * Identify links and associations between articles and datasets
  * Monitor impact of and compliance with data publishing policies
  * Infer new research insights from published data
  * Make it easier to share or link to research data
* Data curation
  * Enhance discoverability and reuse of published datasets
  * Create tools or systems that help users curate research datasets to enable reuse
  * Improve handling of data and creation of metadata
* Data visualisation
  * Create visualizations of datasets and their relationships
  * Improve the ability to understand and communicate data
  * Infer new research insights from published data

## `Some potential use cases`

| Use case      | Themes        | Resources     |
| ------------- | ------------- | ------------- |
| Mine datasets and match them with discipline taxonomies | Data linking, Data curation | Free taxonomies e.g. subject ontology in SciGraph, fields of research codes |
| Mine datasets and match them with institutions. E.g. what institutes produce or cite data more frequently? | Data linking, Data curation (metadata enhancement) | GRID IDs |
| Compliance monitoring - which grant awards have shared their data publicly? | Data linking, Data visualisation | Sci Graph, CrossRef, Dimensions |  
| Link published articles and research data | Data linking (data citation) | Full text sources, DataCite, repository APIs (e.g. figshare) |
| Combine dataset metadata with knowledge representations to create a visualisation | Data visualisation | Repository and DataCite APIs; existing knowledge resources e.g. evolutionary tree | 
| Create a visualisation or tool to explore dataset metadata e.g. [scientificdata.isa-explorer.org](scientificdata.isa-explorer.org) | Data visualisation (tool/application) | Dataset metadata such as Sci Data’s ISA-tab, DataCite API, repository APIs |
| Harvest data availability statements to monitor policy compliance, occurrence of links | Data linking (data citation) | Full text APIs, lists of data identifier types, Scholix/DLI |
| Create a repository selection tool | Data linking (tool/application) | Subject ontologies/Sci Graph, repository lists and catalogues e.g. re3data.org |
| Identify if updates are available for published datasets | Data linking (tool/application) | DataCite API, full text APIs |
| Automatically generate metadata for submitted datasets | Data curation (tool/application for data publishing) | Repository APIs e.g. figshare, subject taxonomies |
| Create focused resources from general repositories for specific types of data/files/disciplines e.g. image files in medicine | Data linking, Data curation (tool/application) | Repository APIs e.g. figshare, subject taxonomies |
| Develop machine learning techniques for image files | Data curation (machine learning/AI) | Repository APIs e.g. figshare, subject taxonomies |
| Find most commonly used and referenced repository software platforms (DSpace, Fedora etc) | Data curation, Data linking | Repository list APIs, article full texts |
| Mining data citations from conference proceedings | Data linking, Data visualisation | DataCite API, Sci Graph, full text APIs, metadata APIs |

## `User stories and related ideas for hacks`
- A **journal editor** who wants to encourage data sharing by recommending specific data repositories to authors submitting to their journal might benefit from a data repository identification and selection tool. Lists of research data repositories, research disciplines from the latest SN SciGraph along with publication data might help with this tool.
- Could data from publications, subject ontologies and data repository APIs help a **researcher or data librarian**, who wants to make research data management more efficient, automatically generate research data metadata? And, could machine learning techniques be applied to particular types of data file (e.g. images) to aid data curation, such as classification of image files?
- **Publishers, researchers, editors, librarians and infrastructure providers** can all benefit (more readership, more citations, improved reader experience) from improved data-article linking. A simple approach more publishers could take is using the DataCite - DataCite mint DOIs for datasets - API to identify datasets linking to their DOIs.
- **Funding agencies and institutions** are increasingly interested in research data policy compliance monitoring but the outputs of particular grants - which can potentially be tracked through grant identifiers - can be hard to find consistently and comprehensively. One could leverage a shared requirement of many journals - requiring authors to provide data availability statements in journal articles, like an Acknowledgement for data - from publisher full text to mine and classify these statements. This would achieve better compliance monitoring and reporting, and understand the impact of journal data policies on researcher behaviour.
