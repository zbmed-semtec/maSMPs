# machine-actionable Software Management Plan Ontology (maSMP Ontology)

## About

We have defined a metadata schema in the form of an ontology representing the necessary metadata elements for a maSMP. The metadata schema includes entities involved in software management planning; such as an SMP itself, software source code, software release, documentation, authors and their relations. We are reusing terms mainly from [schema.org](https://schema.org/) and from [DCSO](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard), with some few additions of our own. 

## Current version

The [current version is 2.1.0](./maSMP_schema_v2/maSMP_v2.jsonld) with [corresponding usage profiles/guidelines](./maSMP_schema_v2/v2.1.0/profiles/). We have use the [Data Discovery Engine (DDE)](https://discovery.biothings.io/) to create types and properties, merging them all in one file corresponding to v2.1.0.

Future versions will be released based on new or improved crosswalks to SMP platforms such as [SMW](https://smw.ds-wizard.org) and [RDMO](https://rdmorganiser.github.io/).

### How to use version 2.1.0
[schema.org](https://schema.org) and its extensions are meant to be used to add sematically structured markup to web pages. We have two very minimalistic and incomplete examples, [one  including maSMP in the context](./maSMP_schema_v2/v2.1.0/example_with_context.jsonld) and [another using the full maSMP schema link](./maSMP_schema_v2/v2.1.0/example_with_url.jsonld). Both examples will validate using the [Validator Schema](https://validator.schema.org/); however, any type or property defined in maSMP metadata schema will be ignored as only schema.org properties are validated. 

Our aim is integrating our maSMP metadata schema to [Bioschemas](http://bioschemas.org) so users can benefit from the community including documentation, examples, live adoption and validators. By now, users can directly use the schema and look at the [profiles](./maSMP_schema_v2/v2.1.0/profiles/) for a guideline on expected properties. 

## Credits

This ontology/metadata schema has been developed by Leyla Jael Castro, Olga Giraldo, Lukas Geist, Nelson Quiñones, Dhwani Solanki, and Dietrich Rebholz-Schuhmann. More information can be found at the [maSMP GitHub pages](https://zbmed-semtec.github.io/maSMPs/) and the [maSMP metadata pages](https://w3id.org/zbmed-semtec/projects/2022_maSMP).

