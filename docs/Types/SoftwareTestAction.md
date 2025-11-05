(parent type) [Action](http://schema.org/Action){:target='_blank'} - (type) maSMP:SoftwareTestAction

The act of testing an object according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

<table>
<tr><th>Property</th><th>Expected Type</th><th>Description</th></tr>
<tr><td>maSMP:softwareTested</td>
<td><a href='http://schema.org/SoftwareSourceCode' target='_blank'>SoftwareSourceCode</a> or <a href='http://schema.org/SoftwareApplication' target='_blank'>SoftwareApplication</a></td>
<td>Link to the software tested by this action.</td>
</tr>
<tr><td>maSMP:testInput</td>
<td><a href='http://schema.org/Thing' target='_blank'>Thing</a> or <a href='http://schema.org/ListItem' target='_blank'>ListItem</a></td>
<td>Input used to performed the test. Some tests may not require any input, some may require multiple ones. If order or grouping is important in the case of multiple inputs, a ListItem could help.</td>
</tr>
<tr><td>maSMP:testType</td>
<td><a href='http://schema.org/Text' target='_blank'>Text</a> or <a href='http://schema.org/URL' target='_blank'>URL</a> or <a href='http://schema.org/DefinedTerm' target='_blank'>DefinedTerm</a></td>
<td>The type of test that it is performed on the object.</td>
</tr>
</table>

<hr/>
<table align="center" style="width:100%">
  <tr>
  <td><a href="https://www.zbmed.de/en/legal-notice" target="_blank">Legal notice</a></td>
  <td><a href="https://www.zbmed.de/en/disclaimer" target="_blank">Disclaimer</a></td>
  <td><a href="https://www.zbmed.de/en/privacy-policy" target="_blank">Privacy policy</a></td>
  </tr>
</table> 