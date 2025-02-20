(parent type) [Action](http://schema.org/Action){:target='_blank'} - (type) maSMP:SoftwareRunAction

The act of testing an object according to its specifications. For instance, testing a software with a particular testType using a specific testInput and getting a specific testOutput (aka result).

<table>
<tr><th>Property</th><th>Expected Type</th><th>Description</th></tr>
<tr><td><a href='http://schema.org/operatingSystem' target='_blank'>operatingSystem</a></td>
<td><a href='http://schema.org/Text' target='_blank'>Text</a></td>
<td>If the running was done by a direct execution (rather than via a container), indicate the operating system.</td>
</tr>
<tr><td><a href='http://schema.org/processorRequirements' target='_blank'>processorRequirements</a></td>
<td><a href='http://schema.org/Text' target='_blank'>Text</a></td>
<td>If the running was done by a direct execution (rather than via a container), indicate the processor specification.</td>
</tr>
<tr><td><a href='http://schema.org/runtimePlatform' target='_blank'>runtimePlatform</a></td>
<td><a href='http://schema.org/Text' target='_blank'>Text</a></td>
<td>If the running was done by a direct execution (rather than via a container), indicate the runtime platform.</td>
</tr>
<tr><td>maSMP:runContainer</td>
<td><a href='http://schema.org/URL' target='_blank'>URL</a></td>
<td>If the running was done using a container, such container should be pointed to here.</td>
</tr>
<tr><td>maSMP:runInput</td>
<td><a href='http://schema.org/Thing' target='_blank'>Thing</a></td>
<td>Actual input used by this action to run a software.</td>
</tr>
<tr><td>maSMP:softwareRun</td>
<td><a href='http://schema.org/SoftwareSourceCode' target='_blank'>SoftwareSourceCode</a> or <a href='http://schema.org/SoftwareApplication' target='_blank'>SoftwareApplication</a></td>
<td>Software executed by this running action.</td>
</tr>
</table>
