(parent type) [CreativeWork](http://schema.org/CreativeWork){:target='_blank'} - (type) maSMP:OutputManagementPlan

Management plans (e.g., data, software, other research output/outcomes/artifacts) are a tool for researchers and research stewards to organize and plan around research artifacts, from initial ideas to publication. This type builds on top of <a href='https://schema.datacite.org/meta/kernel-4.4/' target='_blank'>DataCite Metadata Schema 4.4</a> and maps it mandatory elements to schema.org to represent research artifact management plans. This type could be extended to cover particularities wrt management plans for specific research outcomes, e.g., data management plans or software management plans.

<table>
<tr><th>Property</th><th>Expected Type</th><th>Description</th></tr>
<tr><td>maSMP:questionnaire</td>
<td><a href='http://schema.org/Question' target='_blank'>Question</a> or <a href='http://schema.org/ItemList' target='_blank'>ItemList</a></td>
<td>Questions asked in this management plan. If the order is important <a href='https://schema.org/ItemList' target='_blank'>ItemList</a> can be used, otherwise an array of <a href='https://schema.org/Question' target='_blank'>Question</a> would work.</td>
</tr>
<tr><td>maSMP:relatedMngPlan</td>
<td>maSMP:OutputManagementPlan</td>
<td>Link to other management plans associated to this one, e.g., an SMP associated to the DMP on the datasets used by the software</td>
</tr>
<tr><td>maSMP:researchProject</td>
<td><a href='http://schema.org/ResearchProject' target='_blank'>ResearchProject</a></td>
<td>Link to the research project this mng plan belongs to</td>
</tr>
</table>

