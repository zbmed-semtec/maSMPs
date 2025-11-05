<h1>SoftwareTestActionProfile</h1>

SoftwareTestActionProfile is profile for <a href='../../Types/SoftwareTestAction'>maSMP:SoftwareTestAction</a>

The act of testing a software according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

## Minimum properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
<tr><td>maSMP:softwareTested</td>                <td><a href='http://schema.org/SoftwareSourceCode' target='_blank'>SoftwareSourceCode</a> or <a href='http://schema.org/SoftwareApplication' target='_blank'>SoftwareApplication</a></td>          <td>Link to the software tested by this action.</td> <td>one</td></tr>
      <tr><td>maSMP:testType</td> <td><a href='http://schema.org/Text' target='_blank'>Text</a> or <a href='http://schema.org/URL' target='_blank'>URL</a> or <a href='http://schema.org/DefinedTerm' target='_blank'>DefinedTerm</a></td> <td>The type of test that it is performed on the object.</td> <td>one</td></tr></table>

## Recommended properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
          <tr><td><a href='http://schema.org/result' target='_blank'>result</a></td>           <td>See range for <a href='http://schema.org/result' target='_blank'>result</a> in schema.org</td>                                                                                                  <td>The result produced in the action. e.g. John wrote *a book*.</td> <td>many</td></tr>
<tr><td><a href='http://schema.org/description' target='_blank'>description</a></td> <td>See range for <a href='http://schema.org/description' target='_blank'>description</a> in schema.org</td>                                                                                                                                    <td>A description of the item.</td>  <td>one</td></tr>
          <tr><td><a href='http://schema.org/sameAs' target='_blank'>sameAs</a></td>           <td>See range for <a href='http://schema.org/sameAs' target='_blank'>sameAs</a> in schema.org</td> <td>URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.</td> <td>many</td></tr></table>

## Optional properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
                                              <tr><td>maSMP:testInput</td> <td><a href='http://schema.org/Thing' target='_blank'>Thing</a> or <a href='http://schema.org/ListItem' target='_blank'>ListItem</a></td> <td>Input used to performed the test. Some tests may not require any input, some may require multiple ones. If order or grouping is important in the case of multiple inputs, a ListItem could help.</td> <td>many</td></tr>
<tr><td><a href='http://schema.org/target' target='_blank'>target</a></td>                                        <td>See range for <a href='http://schema.org/target' target='_blank'>target</a> in schema.org</td>                                                                                                                                                     <td>Indicates a target EntryPoint for an Action.</td> <td>many</td></tr></table>

