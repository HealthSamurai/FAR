# FAR
FHIR Artifact Registry

Built on top of  [Canonical Resource](https://build.fhir.org/canonicalresource.html) Management Infrastructure - https://build.fhir.org/ig/HL7/crmi-ig/introduction.html

Responsibilities:
* Check and load all deps
* resolve references
* add package references
* Derivatives -> FHIR Schema, GraphQL


* Introspect FHIR Packages (including IGs)- Search, Read, VRead
* Build FHIR Packages (CRUD/History)
* UI editors for Questionnaire, SearchParams, StructureDefinitions, etc
* Synchronization API
* Publish packages




## Introduction

An “artifact” in this IG means an instance of a canonical resource. The purpose of this IG is to:

Provide a place for universal specification of Shareable/Publishable/Computable/Executable profiles that R4 IGs can use for canonical resources
* Shareable: Shareable profiles set the minimum expectations for including an artifact in a repository or implementation guide
* Computable: Computable profiles deal with authoring and design-time considerations
* Publishable: Publishable profiles describe the expectations for publication and distribution of an artifact, typically as part of an artifact repository
* Executable: Executable profiles deal with run-time behavior and implementation considerations

Provide a space for universally applicable guidance and extensions in support of content management and the content development lifecycle, 
including support for (1) publishing and (2) distributing artifacts. 
Please take a look at the Profiles page for a more detailed description of the Shareable, Publishable, Computable, and Executable profile capabilities.




## Roles

* Authoring System: A system enabling content modifications and publishing
  * Authoring Knowledge Repository
  * Authoring Knowledge Terminology Service
* Publishing: Specifications for publishing artifacts to:
  * FHIR Package Registry
  * Knowledge Repository
  * Knowledge Terminology Service
* Distribution: Specifications for artifact distribution, including the use of NPM (Node Package Manager)
  * Downstream System(s): Systems using distributed content.


