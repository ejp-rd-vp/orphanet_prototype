## Online Sparql Endpoint  

http://34.90.29.193/bigdata/#query

# orphanet_prototype

Registries metadata from Orphanet catalog, using Orphanet Rare Disease Ontology (ORDO)
Mixed with RD connnect Registries metadata

## Getting Started

2 blazegraph :
#### BlazeGraphEJP-Orphanet&RDConnect
Mixed metadata between Orphanet and RDConnect, using "diseases" direct links (diseases mapped to the resources, using Orphacodes)


#### BlazeGraphEJP-Orphanet-Inference
Registries metadata from Orphanet only, using "diseases" links based on the ORDO classification (inference) : direct links to diseases plus higher disorder concepts

#### VirtualCatalogue.owl
OWL object properties for sparql queries

#### VirtualPlatformRest.war
Web services with examples

#### UrlREst.txt
Web services urls

#### SparqlHack.txt
Sparql queries examples

### Prerequisites

VirtualPlatformRest.war has been tested with Tomcat 9.+
Java needed to run blazegraph

### Installing

Deploy war files with tomcat
startBlazeGraph.bat to start blazegraph on windows
or CLI
```
java -server -Xmx4g -jar blazegraph.jar
```

