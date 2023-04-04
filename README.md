# Metadata model for machine-actionable Software Management Plans

<table><tr><td valign="top">

<h3>About</h3>

This project corresponds to an extension of the Research Data Alliance (RDA) [machine-actionable Data Management Plan (maDMP)](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard) application profile and its corresponding DMP Common Standard ontology (DCSO) in order to cover the case of [ELIXIR Software Management Plans (SMPs)](https://doi.org/10.37044/osf.io/k8znb). Similar to DMPs, SMPs help formalize a set of structures and goals that ensure the software is accessible and reusable in the short, medium and long term. Although targeting the life sciences community, most of the elements of the ELIXIR SMPs are domain agnostic and could be used by other communities as well. DMPs and SMPs can be presented as text-based documents, sometimes guided by a set of questions corresponding to key points related to the lifecycle of either data or software. The RDA DMP Common Standards working group defined a maDMP to overcome limitations of text-based documents. We propose a similar path for the ELIXIR SMPs so they turn into machine-actionable SMPs (maSMPs).

## Acknowledgements
This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 101017536 and is part of the Research Data Alliance and European Open Science Cloud Future call 2022. This project has been supported by the Good Practices Focus Group part of the ELIXIR Tools Platform. The work presented in this poster was part of Project 17 at the BioHackathon Europe 2022.

# Relevant sources
* [RDA machine-actionable Data Management Plan (maDMP)](https://github.com/RDA-DMP-Common/RDA-DMP-Common-Standard)
* [ELIXIR Software Management Plans (SMPs)](https://doi.org/10.37044/osf.io/k8znb)
* [Practical guide to Software Management Plans](https://zenodo.org/record/7248877#.Y4XeHXaZOUk)
</td>

</td><td valign="top"><h3>Structure</h3><ul><li id="smp_tree"><a href="#smp_table">SMP</a></li><ul><li id="smp_contact_tree"><a href="#smp_contact_table">contact</a></li></ul><ul><li id="smp_contributor_tree"><a href="#smp_contributor_table">contributor</a></li></ul><ul><li id="smp_funding_tree"><a href="#smp_funding_table">funding</a></li></ul><ul><li id="smp_maintenance_tree"><a href="#smp_maintenance_table">maintenance</a></li><ul><li id="maintenance_retirement_tree"><a href="#maintenance_retirement_table">retirement</a></li></ul></ul><ul><li id="smp_project_timeline_tree"><a href="#smp_project_timeline_table">project_timeline</a></li></ul><ul><li id="smp_purpose_tree"><a href="#smp_purpose_table">purpose</a></li></ul><ul><li id="smp_reliability_strategy_tree"><a href="#smp_reliability_strategy_table">reliability_strategy</a></li></ul><ul><li id="smp_software_tree"><a href="#smp_software_table">software</a></li><ul><li id="smp_software_data_storage_tree"><a href="#smp_software_data_storage_table">data_storage</a></li><ul><li id="smp_software_security_and_privacy_tree"><a href="#smp_software_security_and_privacy_table">security_and_privacy</a></li></ul></ul><ul><li id="smp_software_distribution_tree"><a href="#smp_software_distribution_table">distribution</a></li><ul><li id="smp_software_distribution_license_tree"><a href="#smp_software_distribution_license_table">license</a></li><li id="smp_software_distribution_production_tree"><a href="#smp_software_distribution_production_table">production</a></li></ul></ul><ul><li id="smp_software_documentation_tree"><a href="#smp_software_documentation_table">documentation</a></li><ul><li id="smp_software_documentation_citation_tree"><a href="#smp_software_documentation_citation_table">citation</a></li><li id="smp_software_documentation_deployment_documentation_tree"><a href="#smp_software_documentation_deployment_documentation_table">deployment_documentation</a></li><li id="smp_software_documentation_developer_documentation_tree"><a href="#smp_software_documentation_developer_documentation_table">developer_documentation</a></li><li id="smp_software_documentation_user_documentation_tree"><a href="#smp_software_documentation_user_documentation_table">user_documentation</a></li></ul></ul><ul><li id="smp_software_repository_tree"><a href="#smp_software_repository_table">repository</a></li><ul><li id="smp_software_repository_license_tree"><a href="#smp_software_repository_license_table">license </a></li></ul></ul><ul><li id="smp_software_testing_tree"><a href="#smp_software_testing_table">testing</a></li></ul><ul><li id="smp_software_version_control_tree"><a href="#smp_software_version_control_table">version_control</a></li></ul></ul><ul><li id="smp_software_engineering_quality_tree"><a href="#smp_software_engineering_quality_table">software_engineering_quality</a></li></ul></td></tr></table>

<h2 id="smp_contact_table">Properties in 'contact'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_contact_table" href="#smp_contact_tree">contact</a></td><td valign="top">Contact person for the SMP</td><td valign="top">1</td><td valign="top">Elizabeth Smith contact@example.com</td></tr>
</tbody></table>

<h2 id="smp_contributor_table">Properties in 'contributor'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_contributor_table" href="#smp_contributor_tree">contributor</a></td><td valign="top">The contributers of code, planning and data involved in the software project</td><td valign="top">0..*</td><td valign="top">Elizabeth Smith, Adam Miller</td></tr>
</tbody></table>

<h2 id="smp_funding_table">Properties in 'funding'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_funding_table" href="#smp_funding_tree">funding</a></td><td valign="top">Who is funding the project</td><td valign="top">0..*</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_maintenance_table">Properties in 'maintenance'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_maintenance_table" href="#smp_maintenance_tree">maintenance</a></td><td valign="top">Running post-production modifications on the software to improve user functionaility or resolve technical issues</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="maintenance_retirement_table" href="#maintenance_retirement_tree">retirement</a></td><td valign="top">The strategy that will be used to put an end to the use of the software project</td><td valign="top">0..1</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_project_timeline_table">Properties in 'project timeline'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_project_timeline_table" href="#smp_project_timeline_tree">project_timeline</a></td><td valign="top">Establish the keydates of project development</td><td valign="top">0..*</td><td valign="top">Development start: "Apr 9, 2020", Development end: "Jul 24, 2023"</td></tr>
</tbody></table>

<h2 id="smp_purpose_table">Properties in 'purpose'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_purpose_table" href="#smp_purpose_tree">purpose</a></td><td valign="top">A brief description of the software stating its purpose and intended audience</td><td valign="top">1..*</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_reliability_strategy_table">Properties in 'reliability strategy'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_reliability_strategy_table" href="#smp_reliability_strategy_tree">reliability_strategy</a></td><td valign="top">How can it be ensured that the software will keep running</td><td valign="top">0..*</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_software_table">Properties in 'software'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_testing_table" href="#smp_software_testing_tree">testing</a></td><td valign="top">Code testing strategies and its pipeline to successful testing results covering a broad range of testing-categories</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="smp_software_version_control_table" href="#smp_software_version_control_tree">version_control</a></td><td valign="top">The system used to manage changes in code shared across all developers</td><td valign="top">1..*</td><td valign="top">git</td></tr>
</tbody></table>

<h2 id="smp_software_data_storage_table">Properties in 'data storage'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_data_storage_table" href="#smp_software_data_storage_tree">data_storage</a></td><td valign="top">The location and type of storage solutions for data used or created by the software.</td><td valign="top">0..*</td><td valign="top">SQLite</td></tr>
<tr><td valign="top"><a id="smp_software_security_and_privacy_table" href="#smp_software_security_and_privacy_tree">security_and_privacy</a></td><td valign="top">What measures will be taken to ensure the security and privacy of the users data and the data generated by the app?</td><td valign="top">0..*</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_software_distribution_table">Properties in 'distribution'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_distribution_table" href="#smp_software_distribution_tree">distribution</a></td><td valign="top">To provide technical information on a specific instance of the software like the link to access it, the byte size, description, format</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="smp_software_distribution_license_table" href="#smp_software_distribution_license_tree">license</a></td><td valign="top">The license of the software regarding the rights distribution</td><td valign="top">0..*</td><td valign="top">MIT license</td></tr>
<tr><td valign="top"><a id="smp_software_distribution_production_table" href="#smp_software_distribution_production_tree">production</a></td><td valign="top">The resulting active running instance of the software which is either publically or internally accessible</td><td valign="top">0..1</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_software_documentation_table">Properties in 'documentation'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_documentation_citation_table" href="#smp_software_documentation_citation_tree">citation</a></td><td valign="top">Method to cite the software in form of a citation file (CFF)</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="smp_software_documentation_deployment_documentation_table" href="#smp_software_documentation_deployment_documentation_tree">deployment_documentation</a></td><td valign="top">Deployment documentation guiding how the software project is being deployed into production</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="smp_software_documentation_developer_documentation_table" href="#smp_software_documentation_developer_documentation_tree">developer_documentation</a></td><td valign="top">Documentation regarding the code-components of the software</td><td valign="top">0..*</td><td valign="top"></td></tr>
<tr><td valign="top"><a id="smp_software_documentation_user_documentation_table" href="#smp_software_documentation_user_documentation_tree">user_documentation</a></td><td valign="top">Software documentation regarding the user, instructing how the application is being used from a non-developer perspective</td><td valign="top">0..*</td><td valign="top"></td></tr>
</tbody></table>

<h2 id="smp_software_repository_table">Properties in 'repository'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_repository_table" href="#smp_software_repository_tree">repository</a></td><td valign="top">Name the platforms that are going to be used to store the source files</td><td valign="top">0..*</td><td valign="top">github.com/maSPMs</td></tr>
<tr><td valign="top"><a id="smp_software_repository_license_table" href="#smp_software_repository_license_tree">license</a></td><td valign="top">The license of the software regarding the rights distribution</td><td valign="top">0..*</td><td valign="top">MIT license</td></tr>
</tbody></table>

<h2 id="smp_software_engineering_quality_table">Properties in 'software engineering quality'</h2>

<table style="width: 99%;"><thead><tr><th>Name</th><th>Description</th><th>Cardinality</th><th>Example Value</th></tr></thead><tbody>
<tr><td valign="top"><a id="smp_software_engineering_quality_table" href="#smp_software_engineering_quality_tree">software_engineering_quality</a></td><td valign="top">Guidelines shared across the softwares to provide standardized documentation, testing or code structure</td><td valign="top">0..*</td><td valign="top"></td></tr>
</tbody></table>
