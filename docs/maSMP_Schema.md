## maSMP - Metadata schema representation

![maSMP and maDMP](masmp_and_dmp.png 'maSMP and maDMP')<br><br>

<p style="text-align:justify">We have defined a metadata schema representing metadata elements for a maSMP. The metadata schema includes entities (colored boxes), involved in software management planning; such as an SMP itself, software source code, software release, documentation, authors and their relations. We are reusing terms mainly from <a href=https://schema.org>Schema.org</a>, <a href=https://bioschemas.org>Bioschemas</a> and from <a href=https://semantics.id/dcso/ns/core/>DCSO </a>, with some few additions of our own.</p><p style="text-align:justify">Software Source Code and Software Release share most of the object properties (i.e., those that point to another object rather than to a simple type such as a number) but they correspond to different software concepts. While the source code reflects the current status of a software and can be continuously changing, a software release corresponds to a frozen copy of a particular version. As the source code evolves, shared elements can differ, e.g., new authors can get involved. This changing nature of source code together with the release cycle are important aspects captured by the maSMPs that otherwise might not be evident in text-based questionnaires. An overview of concepts used in the metadata schema for maSMPs is depicted in above schema representation.</p><br> 

## maSMP Types and namespace

[maSMP types](./Types/index.md) are extensions to the schema.org vocabulary while [maSMP profiles](./Profiles/index.md) are recommendations of use of maSMP types.

All types and properties for the maSMP metadata schema can be found at the [maSMP DDE namespace](https://discovery.biothings.io/ns/maSMP) while the profiles are located under the [maSMPProfiles DDE namespace](https://discovery.biothings.io/ns/maSMPProfiles). The [Data Discovery Engine (DDE) platform](https://discovery.biothings.io/) promotes FAIR data-sharing best practices by facilitating the creation and hosting of metadata schemas based on schema.org. 

Note of caution: We intend to push types and profiles to [Bioschemas](https://bioschemas.org) so a broader community can provide feedback and adopt the maSMP approach. We use these pages, the [GitHub repository](https://github.com/zbmed-semtec/maSMPs) and the [DDE namespace](https://discovery.biothings.io/ns/maSMP) as staging areas for development. We will keep here the latest version and history of previous versions. We will also maintain the [DDE namespace](https://discovery.biothings.io/ns/maSMP) up-to-date. Using one or the other should be equivalent but we suggest using the version hosted at Bioschemas.

