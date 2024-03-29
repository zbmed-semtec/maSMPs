## maSMP - Metadata schema representation

![maSMP and maDMP](masmp_and_dmp.png 'maSMP and maDMP')<br><br>

<p style="text-align:justify">We have defined a metadata schema in the form of an ontology representing metadata elements for a maSMP. The metadata schema includes entities (colored boxes), involved in software management planning; such as an SMP itself, software source code, software release, documentation, authors and their relations. We are reusing terms mainly from <a href=https://schema.org>Schema.org</a>, <a href=https://bioschemas.org>Bioschemas</a> and from <a href=https://semantics.id/dcso/ns/core/>DCSO </a>, with some few additions of our own.</p><p style="text-align:justify">Software Source Code and Software Release share most of the object properties (i.e., those that point to another object rather than to a simple type such as a number) but they correspond to different software concepts. While the source code reflects the current status of a software and can be continuously changing, a software release corresponds to a frozen copy of a particular version. As the source code evolves, shared elements can differ, e.g., new authors can get involved. This changing nature of source code together with the release cycle are important aspects captured by the maSMPs that otherwise might not be evident in text-based questionnaires. An overview of concepts used in the metadata schema for maSMPs is depicted in above schema representation.</p><br> 

## maSMP Types and namespace

All types and properties for the maSMP metadata schema can be found at the [maSMP DDE namespace](https://discovery.biothings.io/ns/maSMP). The [Data Discovery Engine (DDE) platform](https://discovery.biothings.io/) promotes FAIR data-sharing best practices by facilitating the creation and hosting of metadata schemas based on schema.org. We also provide embedded pages for types and profiles (i.e., usage recommendation on properties from the parent types). 

Note of caution: We intend to push types and profiles to [Bioschemas](https://bioschemas.org) so a broader community can provide feedback and adopt the maSMP approach. We use these pages, the [GitHub repository](https://github.com/zbmed-semtec/maSMPs) and the [DDE namespace](https://discovery.biothings.io/ns/maSMP) as staging areas for development. We will keep here the latest version and history of previous versions. We will also maintain the [DDE namespace](https://discovery.biothings.io/ns/maSMP) up-to-date. Using one or the other should be equivalent but we suggest using the version hosted at Bioschemas.

The current list of maSMP types and location within the schema.org hierarchy is shown below:
* schema:Thing -> schema:CreativeWork -> [maSMP:OutputManagemenPlan](../Types/OutputManagementPlan) (new type with properties): This type aims at representing output management plans, e.g., software management plans
* schema:Thing -> schema:CreativeWork -> maSMP:OutputManagemenPlan -> [maSMP:SoftwareManagementPlan](../Types/SoftwareManagementPlan) (new type with properties): Output management plan we are most interested in, i.e., Software Management Plans
* schema:Thing -> schema:Action -> [maSMP:SoftwareRunAction](../Types/SoftwareRunAction) (new type with properties): This type aims at representing executions of a software handled by a maSMP:SoftwareManagementPlan. The execution we are most interested in is the one provided by the own developers, showcasing how to use the software with a particular input to obtain a particular known output. Third-party developers and users should ideally use this execution together with corresonding documentation to use the software as intended by its developers.
* schema:Thing -> schema:Action -> [maSMP:SoftwareTestAction](../Types/SoftwareTestAction) (new type with properties): This type aims at representing testing done on a software. From the maSMP perspective, depending on how much information about testing should be collected, naming the tests done as schema:Text (or even better as schema:DefinedTerm using a controlled vocabulary on software testing --Wikidata have a good collection) may be enough

We also add some new properties to types in schema.org
* schema:Thing -> schema:CreativeWork, e.g., intendedUse and ethicalLegalSocial
* schema:Thing -> schema:CreativeWork -> SoftwareApplication
* schema:Thing -> schema:CreativeWork -> SoftwareSourceCode

The maSMP profiles provide some guidance on what properties are more relevant and how to use them
* [maSMPProfiles:SoftwareManagementPlanProfile](../Profiles/SoftwareManagementPlan)
* [maSMPProfiles:SoftwareRunActionProfile](../Profiles/SoftwareRunAction)
* [maSMPProfiles:SoftwareTestActionProfile](../Profiles/SoftwareTestAction)
* [maSMPProfiles:SoftwareApplicationProfile](../Profiles/SoftwareApplication)
* [maSMPProfiles:SoftwareSourceCodeProfile](../Profiles/SoftwareSourceCode)
