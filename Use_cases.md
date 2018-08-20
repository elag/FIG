# Fix Language Use Cases

### Full text indexation of library metadata

This is a scenario where metadata records are available in a database, or
a flat file and need to be transformed into a format suitable for search
indexes such as Solr, ElasticSearch.

Programmers and librarians should be able to understand the mapping rules
from the know library format to the full text indexation format.

### Creation of linked data resources

In the scenario a library wants to make resources available as Linked Data.
Metadata needs to be mapped into a new Schema. Values need to be cleaned, transformed,
made uniform. It should be possible that some field are matched to an external
database (endpoint) or import data from external sources.

The mapping and lookup should be able to cope with the complexities of the
input data.

The language should be in a format that is easy to understand for non-programmers.

## Command line throw away scripts for reporting

It should be possible to have a create small throw away scripts to transform
library metadata in to reports. Such as:

- Counts of records which contain some field/values
- (Unique) lists of field values

## Processing of exports of XML files and XML-based protocols such as OAI-PMH, ORE

In this scenario it should be possible to extract information out of XML files.
Which doesn't require the complexity of XSLT transformations. Based on XPaths
it should be possible to create simple reports of fields in XML files or XML
streams into CSV , Excel reports
