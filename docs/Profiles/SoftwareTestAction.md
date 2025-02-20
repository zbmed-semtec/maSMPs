<h1>SoftwareTestActionProfile</h1>

SoftwareTestActionProfile is profile for <a href='../../Types/SoftwareTestAction'>maSMP:SoftwareTestAction</a>

The act of testing a software according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

## Minimum properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
<tr><td>softwareTested</td> <td></td>          <td>Link to the software tested by this action.</td> <td>one</td></tr>
      <tr><td>testType</td> <td></td> <td>The type of test that it is performed on the object.</td> <td>one</td></tr></table>

## Recommended properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
     <tr><td>result</td> <td></td>                                                                                                  <td>The result produced in the action. e.g. John wrote *a book*.</td> <td>many</td></tr>
<tr><td>description</td> <td></td>                                                                                                                                    <td>A description of the item.</td>  <td>one</td></tr>
     <tr><td>sameAs</td> <td></td> <td>URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.</td> <td>many</td></tr></table>

## Optional properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
<tr><td>testInput</td> <td></td> <td>Input used to performed the test. Some tests may not require any input, some may require multiple ones. If order or grouping is important in the case of multiple inputs, a ListItem could help.</td> <td>many</td></tr>
   <tr><td>target</td> <td></td>                                                                                                                                                     <td>Indicates a target EntryPoint for an Action.</td> <td>many</td></tr></table>
