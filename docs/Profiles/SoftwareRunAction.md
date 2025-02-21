<h1>SoftwareRunActionProfile</h1>

SoftwareRunActionProfile is profile for <a href='../../Types/SoftwareRunAction'>maSMP:SoftwareRunAction</a>

The act of testing an object according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

## Minimum properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
<tr><td>softwareRun</td> <td><a href='http://schema.org/SoftwareSourceCode' target='_blank'>SoftwareSourceCode</a> or <a href='http://schema.org/SoftwareApplication' target='_blank'>SoftwareApplication</a></td> <td>Software executed by this running action.</td> <td>one</td></tr></table>

## Recommended properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
<tr><td>result</td> <td>schema.org ranges</td>                                                                                                  <td>The result produced in the action. e.g. John wrote *a book*.</td> <td>many</td></tr>
<tr><td>sameAs</td> <td>schema.org ranges</td> <td>URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.</td> <td>many</td></tr></table>

## Optional properties

<table>
<tr><td>Property</td><td>Expected Type</td><td>Description</td><td>Cardinality</td></tr>
      <tr><td>operatingSystem</td>   <td><a href='http://schema.org/Text' target='_blank'>Text</a></td>        <td>If the running was done by a direct execution (rather than via a container), indicate the operating system.</td>  <td>one</td></tr>
<tr><td>processorRequirements</td>   <td><a href='http://schema.org/Text' target='_blank'>Text</a></td> <td>If the running was done by a direct execution (rather than via a container), indicate the processor specification.</td>  <td>one</td></tr>
      <tr><td>runtimePlatform</td>   <td><a href='http://schema.org/Text' target='_blank'>Text</a></td>        <td>If the running was done by a direct execution (rather than via a container), indicate the runtime platform.</td>  <td>one</td></tr>
         <tr><td>runContainer</td>     <td><a href='http://schema.org/URL' target='_blank'>URL</a></td>                               <td>If the running was done using a container, such container should be pointed to here.</td>  <td>one</td></tr>
             <tr><td>runInput</td> <td><a href='http://schema.org/Thing' target='_blank'>Thing</a></td>                                                                <td>Actual input used by this action to run a software.</td> <td>many</td></tr></table>
