Markdown documentation created by [pyLODE](http://github.com/rdflib/pyLODE) 2.4

# DIN 276 Bulding Costs - Cost Group Classification

## Metadata
* **IRI**
  * `https://www.dinmedia.de/en/standard/din-276`
* **Creators(s)**
  * [Katja Sigalov](https://orcid.org/0000-0002-3070-0759)
    [[ORCID]](https://orcid.org/0000-0002-3070-0759)
    (<katharina.sigalov@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/katharina_sigalov.html.en)
  * [Philipp Hagedorn](https://orcid.org/0000-0002-6249-243X)
    [[ORCID]](https://orcid.org/0000-0002-6249-243X)
    (<philipp.hagedorn-n6v@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/philipp_hagedorn.html.en)
* **Created**
  * 2024-11-26
* **Version Information**
  * Created with TopBraid Composer
* **License**
  * [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
* **Ontology RDF**
  * RDF ([din-276.ttl](turtle))

## Table of Contents
1. [Classes](#classes)
1. [Object Properties](#objectproperties)
1. [Named Individuals](#namedindividuals)
1. [Namespaces](#namespaces)
1. [Legend](#legend)


## Classes
[Classification](#Classification),
[Level1](#Level1),
[Level2](#Level2),
[Level3](#Level3),
### Classification
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#Classification`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
Sub-classes |[din-276:Level1](Level1) (c)<br />[din-276:Level3](Level3) (c)<br />[din-276:Level2](Level2) (c)<br />
In domain of |[owl:hasSubLevel](http://www.w3.org/2002/07/owl#hasSubLevel) (op)<br />
In range of |[owl:hasSubLevel](http://www.w3.org/2002/07/owl#hasSubLevel) (op)<br />
### Level1
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#Level1`
Super-classes |[din-276:Classification](Classification) (c)<br />
### Level2
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#Level2`
Super-classes |[din-276:Classification](Classification) (c)<br />
### Level3
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#Level3`
Super-classes |[din-276:Classification](Classification) (c)<br />

## Object Properties
[has sub level](#hassublevel),
[](hassublevel)
### has sub level
Property | Value
--- | ---
IRI | `http://www.w3.org/2002/07/owl#hasSubLevel`
Domain(s) |[din-276:Classification](Classification) (c)<br />
Range(s) |[din-276:Classification](Classification) (c)<br />

## Named Individuals
[KG300](#KG300),
[KG320](#KG320),
[KG322](#KG322),
### KG300 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#KG300`
* **Contributor(s)**
  * [din-276:Level1](https://www.dinmedia.de/en/standard/din-276#Level1)
Description | Bauwerk � Baukonstruktionen
### KG320 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#KG320`
* **Contributor(s)**
  * [din-276:Level2](https://www.dinmedia.de/en/standard/din-276#Level2)
Description | Fondazione, sottostruttura
### KG322 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://www.dinmedia.de/en/standard/din-276#KG322`
* **Contributor(s)**
  * [din-276:Level3](https://www.dinmedia.de/en/standard/din-276#Level3)
Description | Fondazioni poco profonde e solette
## Namespaces
* **default (:)**
  * `https://www.dinmedia.de/en/standard/din-276#`
* **dc**
  * `http://purl.org/dc/terms/`
* **din-276**
  * `https://www.dinmedia.de/en/standard/din-276#`
* **owl**
  * `http://www.w3.org/2002/07/owl#`
* **prov**
  * `http://www.w3.org/ns/prov#`
* **rdf**
  * `http://www.w3.org/1999/02/22-rdf-syntax-ns#`
* **rdfs**
  * `http://www.w3.org/2000/01/rdf-schema#`
* **sdo**
  * `https://schema.org/`
* **skos**
  * `http://www.w3.org/2004/02/skos/core#`
* **vann**
  * `http://purl.org/vocab/vann/`
* **xml**
  * `http://www.w3.org/XML/1998/namespace`
* **xsd**
  * `http://www.w3.org/2001/XMLSchema#`

## Legend
* Classes: c
* Object Properties: op
* Functional Properties: fp
* Data Properties: dp
* Annotation Properties: dp
* Properties: p
* Named Individuals: ni