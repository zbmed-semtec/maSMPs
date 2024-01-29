# machine-actionable Software Management Plan Ontology (maSMP Ontology)

## About

We have defined a metadata schema in the form of an ontology representing the necessary metadata elements for a maSMP. The metadata schema includes entities involved in software management planning; such as an SMP itself, software source code, software release, documentation, authors and their relations. We are reusing terms mainly from [schema.org](https://schema.org/) and from the [RDA-DMP-Common-Standard maDMP application profile](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard), with some few additions of our own. 

## Current version

The [current version is 2.1.0](./maSMP_schema_v2/maSMP_v2.jsonld) with [corresponding usage profiles/guidelines](./maSMP_schema_v2/v2.1.0/profiles/). We have use the [Data Discovery Engine (DDE)](https://discovery.biothings.io/) to create types and properties, merging them all in one file corresponding to v2.1.0.

[maSMP types](https://discovery.biothings.io/ns/maSMP) and [maSMP profiles](https://discovery.biothings.io/ns/maSMPProfiles) can be visualized in the DDE platform. Follow the links and you will get a summary of types and properties, and the corresponding profiles with usage guidelines (e.g., minimum, recommended and optional properties with cardinality).

Future versions will be released based on new or improved crosswalks to SMP platforms such as [SMW](https://smw.ds-wizard.org) and [RDMO](https://rdmorganiser.github.io/).

### How to use version 2.1.0
[schema.org](https://schema.org) and its extensions are meant to be used to add sematically structured markup to web pages. We have two very minimalistic and incomplete examples, [one  including maSMP in the context](./maSMP_schema_v2/v2.1.0/example_with_context.jsonld) and [another using the full maSMP schema link](./maSMP_schema_v2/v2.1.0/example_with_url.jsonld). Both examples will validate using the [Validator Schema](https://validator.schema.org/); however, any type or property defined in maSMP metadata schema will be ignored as only schema.org properties are validated. 

Our aim is integrating our maSMP metadata schema to [Bioschemas](http://bioschemas.org) so users can benefit from the community including documentation, examples, live adoption and validators. By now, users can directly use the schema and look at the [profiles](./maSMP_schema_v2/v2.1.0/profiles/) for a guideline on expected properties. 

## Credits

This ontology/metadata schema has been developed by Leyla Jael Castro, Olga Giraldo, Lukas Geist, Nelson Quiñones, Dhwani Solanki, and Dietrich Rebholz-Schuhmann. More information can be found at the [maSMP GitHub pages](https://zbmed-semtec.github.io/maSMPs/) and the [maSMP metadata pages](https://w3id.org/zbmed-semtec/projects/2022_maSMP).

The schema is based on:
* [schema.org v23](https://schema.org/docs/releases.html#v23.0)
* [Codemeta](https://codemeta.github.io/)
* [Bioschemas](https://bioschemas.org)
* [ELIXIR SMP](https://doi.org/10.37044/osf.io/k8znb)
* SMP metadata crosswalks from [May 2023](https://doi.org/10.5281/zenodo.8087356) and [December 2023](https://doi.org/10.5281/zenodo.10275894)
* [RDA-DMP-Common-Standard maDMP application profile](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard)

The maSMP project is part of the [NFDI4DataScience](https://www.nfdi4datascience.de/) project funded by the [German Research Foundation (DFG)](https://www.dfg.de/), project number [460234259](https://gepris.dfg.de/gepris/projekt/460234259). 

This project received funding (December 2022 to May 2023) from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 101017536 which is part of the Research Data Alliance and European Open Science Cloud Future call 2022. [More info](https://eoscfuture-grants.eu/node/275).

