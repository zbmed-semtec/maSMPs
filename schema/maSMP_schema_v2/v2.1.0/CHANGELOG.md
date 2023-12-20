# maSMP metadata schema vr 2.1.0

In this new version of the maSMP metadata schema we added the following properties
| Property                   | Description                                             | Range                                    |
|----------------------------|---------------------------------------------------------|------------------------------------------|
| codemeta:buildInstructions | Link to installation instructions/documentation         | Text or URL                              |
| codemeta:issueTracker      | Link to software bug reporting or issue tracking system | URL                                      |
| maSMP:changelog            | Link to CHANGELOG file                                  | URL                                      |
| maSMP:intendedUse          | Purpose and intended use of this software               | Text or URL                              |
| maSMP:deployInstructions   | Text or link to deployment instructions/documentation   | Text or URL                              |
| maSMP:installInstructions  | Text or link to installation instructions/documentation | Text or URL                              |
| maSMP:testInstructions     | Text or link to testing instructions/documentation      | Text or URL                              |
| maSMP:softwareTested       | Link to the software tested by this action              | SofwareSourceCode or SoftwareApplication |

And also added two new types maSMP:OutputManagementPlan and maSMP:SoftwareManagementPlan

[Crosswalks supporting this version](https://doi.org/10.5281/zenodo.10275895) are publicly available.
