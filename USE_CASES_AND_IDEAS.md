
# **Use cases and ideas for potential hacks**

## `Some potential use cases`

| Use case      | Themes        | Resources     |
| ------------- | ------------- | ------------- |
| Mine datasets and match them with discipline taxonomies | Data linking, Data curation | Free taxonomies e.g. subject ontology in SciGraph, fields of research codes |
| Mine datasets and match them with institutions. E.g. what institutes produce or cite data more frequently? | Data linking, Data curation (metadata enhancement)  | GRID IDs |
| Compliance monitoring - which grant awards have shared their data publicly? | Data linking, Data visualisation  | Sci Graph, CrossRef, Dimensions |  
| Link published articles and research data | Data linking (data citation)  | Full text sources, DataCite, repository APIs (e.g. figshare) |
| Combine dataset metadata with knowledge representations to create a visualisation | Data visualisation  | Repository and DataCite APIs; existing knowledge resources e.g. evolutionary tree | 
| Create a visualisation or tool to explore dataset metadata e.g. scientificdata.isa-explorer.org | Data visualisation (tool/application)  | Dataset metadata such as Sci Data’s ISA-tab, DataCite API, repository APIs |
| Harvest data availability statements to monitor policy compliance, occurrence of links | Data linking (data citation)  | Full text APIs, lists of data identifier types, Scholix/DLI |
| Create a repository selection tool | Data linking (tool/application)  | Subject ontologies/Sci Graph, repository lists and catalogues e.g. re3data.org |
| Identify if updates are available for published datasets | Data linking (tool/application)  | DataCite API, full text APIs |
| Automatically generate metadata for submitted datasets | Data curation (tool/application for data publishing) | Repository APIs e.g. figshare, subject taxonomies |
| Create focused resources from general repositories for specific types of data/files/disciplines e.g. image files in medicine | Data linking, Data curation (tool/application)  | Repository APIs e.g. figshare, subject taxonomies |
| Develop machine learning techniques for image files | Data curation (machine learning/AI)  | Repository APIs e.g. figshare, subject taxonomies |

## `Some specific ideas for hacks`
- A journal editor who wants to encourage data sharing by recommending specific data repositories to authors submitting to their journal might benefit from a data repository identification and selection tool. Lists of research data repositories, research disciplines from the latest SN SciGraph along with publication data might help with this tool.
- Could data from publications, subject ontologies and data repository APIs help a researcher or data librarian, who wants to make research data management more efficient, automatically generate research data metadata? And, could machine learning techniques be applied to particular types of data file (e.g. images) to aid data curation, such as classification of image files?
- Publishers, researchers, editors, librarians and infrastructure providers can all benefit (more readership, more citations, improved reader experience) from improved data-article linking. A simple approach more publishers could take is using the DataCite - DataCite mint DOIs for datasets - API to identify datasets linking to their DOIs. But research data identification is complex, with thousands of publicly available datasets not having DOIs but other types of identifier. We’re also preparing a curated list of repositories and identifier types, such as accession codes, that could accelerate creation of discipline specific linking solutions.
- Funding agencies and institutions are increasingly interested in research data policy compliance monitoring but the outputs of particular grants - which can potentially be tracked through grant identifiers - can be hard to find consistently and comprehensively. One could leverage a shared requirement of many journals - requiring authors to provide data availability statements in journal articles, like an Acknowledgement for data - from publisher full text to mine and classify these statements. This would achieve better compliance monitoring and reporting, and understand the impact of journal data policies on researcher behaviour.
