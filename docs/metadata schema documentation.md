## maSMP Ontology
<table><tr><td valign="top"> <h4><u>Structure of Ontology</h4></u>
<h4>Classes</h4>
<ul><li><a href="https://schema.org/Action">Action</a></li></ul>
<ul><li><a href="https://sparontologies.github.io/foaf/current/foaf.html#d4e585">Agent</a></li></ul>
<ul><li><a href="https://schema.org/CreativeWork">CreativeWork</a></li></ul>
<ul><li><a href="https://semantics.id/ns/dcso/index-en.html#http://www.w3.org/ns/dcat#Dataset">Dataset</a>-<a href="https://semantics.id/ns/dcso/index-en.html#DMP">DMP</a></li></ul>
<ul><li><a href="https://schema.org/DataType">DataTye</a></li></ul>
<ul><li><a href="https://semantics.id/ns/dcso/index-en.html#Id">Id</a></li></ul>
<ul><li><a href="https://schema.org/Intangible">Intangible</a></li></ul>
<ul><li><a href="https://semantics.id/ns/dcso/index-en.html#License">License</a></li> </ul>
</td>

</td><td valign="center">
<img src="masmp_schema.png" style="height: 400px; width:500;"/>

</td>
</table>

### Classes & Sub-classes

| Class      | Sub-class/ Types  | 
| ----------- | -----------
| Action      | TestAction  |     
| Agent   | [Organization](https://schema.org/Organization) , [Person](https://schema.org/Person) | 
| CreativeWork| [Dataset-SMP](https://schema.org/Dataset) , Documentation , [LearningResource](https://schema.org/LearningResource) , SMP , [SoftwareApplication](https://schema.org/SoftwareApplication) , [SoftwareSourceCode](https://schema.org/SoftwareSourceCode)|
| Dataset-DMP   | - |
| DataType   | [Boolean](https://schema.org/Boolean) , [Date](https://schema.org/Date) , [Text](https://schema.org/Text)  |
| Id   | - |
| Intangible   | [DefinedTerm](https://schema.org/DefinedTerm) , [FormalParameter](https://bioschemas.org/types/FormalParameter/1.0-RELEASE) , [PropertyValue](https://schema.org/PropertyValue) |
| License   |  - |


More information about classes and its object properties will be found [here](classes.md)


```
Class Hierarchy
│   
└─── Action 
│   └─── TestAction
| 
└─── Agent  
│   └─── Organization
|   └─── Person
|
└─── CreativeWork 
│   └─── Dataset-SMP
|   └─── Documentation
│   └─── LearningResource
|   └─── Documentation
│   └─── SMP
|   └─── SoftwareApplication
|   └─── SMP
|   └─── SoftwareSourceCode
|
└─── Dataset-DMP
|
└─── DataType
|   └─── Boolean
|   └─── Date
|   └─── Text
|
└─── Id
|
└─── Intangible
|   └─── DefinedTerm
|   └─── FormalParameter
|   └─── PropertyValue
|
└─── License

``` 















