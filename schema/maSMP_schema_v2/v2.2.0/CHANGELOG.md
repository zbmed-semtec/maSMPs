# maSMP metadata schema vr 2.2.0

In this new version of the maSMP metadata schema we use schema:Action to link questions to expected metadata statements in maSMP:OutputManagementPlan (and by extension maSMP:SoftwareManagementPlan). To achieve this, we need to modify the property ```schema:pattern``` in ```schema:CreativeWork``` to include ```schema:Action``` as part of its range.

It also changes MD links to HTML links in the type and property descriptions.
