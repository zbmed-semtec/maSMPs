# maSMP metadata schema vr 2.0.0

In this new verson of the maSMP metadata schema we:
* Move from an ontology in OWL (not really compatible with [schema.org](htpps://schema.org)) to a medatadata schema using [DDE](https://discovery.biothings.io/) to edit our schemas as it is fully compatible with [schema.org](htpps://schema.org).
* The use of [DDE](https://discovery.biothings.io/) will also ease the integration to [Bioschemas][https.//bioschemas.org] as it is also used there.
* Schemas are now available for exploration in the [NFDI4DS at ZB MED namespace in DDE](https://discovery.biothings.io/ns/NFDI4DSatZBMED).
* We use the namespace `NFDI4DSatZBMED` for schemas in this version.
* Whenever [Codemeta terms](https://codemeta.github.io/terms/) are used, we use their namespace https://w3id.org/codemeta/
* Whenever [Bioschemas](https://bioschemas.org) new types and properties are used, we use their namespace https://bioschemas.org/terms/
* `schema:SoftwareSourceCode` is extended to `NFDI4DSatZBMED:SoftwareSourceCode` and `schema:SoftwareApplication` to `NFDI4DSatZBMED:SoftwareApplication` so we can include our new properties. The new properties remain the same as in version 1 but we make the names more "schema-like" by using nouns, e.g., `documentationAPI` rather than actions `hasAPIDocumentation`. The property mapping between version 1 and version 2 are:
   * `hasAPIDocumentation` = `schema:documentation` as the definition "Further documentation describing the Web API in more detail" fits well
   * `documenation` = `furtherDocumentation`
   * `hasDeveloperDocumentation` = `developerDocumentation`
   * `hasUserDocumentation` = `userDocumentation`
   * `hasVersionControlSystem` = `versionControlSystem`
   * `hasLearningResource` = `learningResource`
* Properties coming from Codemeta (readme) and Bioschemas (input and output) remain the same, no change on the property names
* We add the property `codemeta:referencePublication` but change its range from `schema:ScholarlyArticle` to `schema:CreativeWork`. 
* `schema:Action` is extended to `NFDI4DSatZBMED:TestAction`, a fully new type. We simplify this type wrt version 1. Now it has only two properties: 
   * `NFDI4DSatZBMED:testType`
   * `NFDI4DSatZBMED:testInput`
   * There is no need for `NFDI4DSatZBMED:testOutput` as the exisiting property `schema:results` work for this purpose
* Due to the simplification of `NFDI4DSatZBMED:TestAction`, the extensions to `NFDI4DSatZBMED:testType` (e.g., `endToEndTesting`, `functionalTesting`) are no longer needed. Rather, a profile will recommend the use of a list of possible software test types from, e.g., [Wikidata software testing](https://www.wikidata.org/wiki/Q188522).
* We add a new type `NFDI4DSatZBMED:SoftwareRunAction` to capture an example on how a software can be executed with some sample input to obtain a corresponding sample output (reports of executions by third parties would also be possible).
