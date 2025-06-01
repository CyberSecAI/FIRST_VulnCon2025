# CVE Record Format - Past, Present, and Future

**Video URL:** [https://www.youtube.com/watch?v=ds6mf0SfjV4](https://www.youtube.com/watch?v=ds6mf0SfjV4)
**Video ID:** ds6mf0SfjV4

---

SUMMARY
Chris Coffin and MZ discuss the CVE record format, recent updates, future plans, and community involvement.

IDEAS
* CVE record format is a JSON schema for ingesting and displaying vulnerability records.
* Minimum requirements for CVE submissions are currently minimal and under debate.
* Focus is shifting from helping CNAs define data to focusing on consumer needs.
* A consumer working group is being considered for gathering feedback.
* Version 5.1.0 added CVSS4 and tightened validations.
* Version 5.1.1 improved CPE data handling with applicability statements.
* Documentation and examples were updated for clarity and consistency.
* The next release will further tighten the schema and improve validation.
* SemVer version type will be added with validation for improved data quality.
* Pearl support is being considered as a software identifier.
* A generic, abstracted software identifier representation is also being explored.
* Official support for SSVC (Stakeholder Specific Vulnerability Classification) is planned.
* Removing obsolete properties from the schema is a future consideration.
* Community input is encouraged through the CVE-S schema GitHub repository.
* A phased approach with warnings will be used for deprecating schema elements.
* API versioning changes may be used for major schema updates.
* The quality working group (QWG) welcomes participation from consumers and CNAs.
* Narrative fields in CVE records are important for human readability and API consumption.
* Minimum requirements for narrative fields may be increased to improve data quality.
* CNAs use different approaches for writing descriptions, with varying levels of detail.
* ADPs (Authorized Data Publishers) provide additional information to CVE records.
* CNAs do not have control over ADP additions to their CVE records.
* ADPs operate within a defined scope and can be removed for exceeding it.
* A maturity level rating system for ADPs is under consideration.
* ADPs are not expected to replace CNA security advisories.
* Including CNA VEX documents in CVE records has not been discussed.
* VEX documents often reference CVE records, but not vice-versa.
* Product information from VEX could potentially be incorporated into CVE records.
* All CVE records from version 4.0 have been migrated to version 5.0.
* ADPs could potentially enhance older CVE records with new information.


INSIGHTS
* The CVE record format is evolving to meet the needs of both suppliers and consumers.
* Data quality is a major focus, with ongoing efforts to improve validation and consistency.
* Community involvement is crucial for shaping the future of the CVE program.
* SemVer adoption will improve automation and data analysis capabilities.
* The ADP program expands the CVE ecosystem, but raises questions about control and quality.
* Balancing standardization with flexibility is a key challenge for the CVE program.
* Clear communication and a phased approach are essential for managing schema changes.
* Richer narrative descriptions are needed for both human and machine consumption.
* The role of ADPs is still evolving, with potential for both enrichment and conflict.
* Integrating data from other sources like VEX could further enhance CVE records.


QUOTES
* "We are all about communicating and helping drive things forward." - Chris Coffin
* "I very much strongly believe we have a lot of input from the supply side right now." - MZ
* "The minimum requirements are very much the minimum requirements right now." - MZ
* "We want to do that as fast as possible." - Chris Coffin
* "We need to serve both our consumer audience and the supply audience." - MZ
* "There is a using CPE and CVE quick start guide on the cve.org resources page." - Chris Coffin
* "There's been a lot of criticism about quality data quality in CVE program." - MZ
* "Sometimes you think the spec was clear and then you see the real world." - MZ
* "We totally recognize and acknowledge there are improvements we need to make." - MZ
* "The CVE program's responsibility isn't really to force the global adoption of any one software identifier." - Chris Coffin
* "There is no universally accepted software identifier right now." - Chris Coffin
* "We're looking at allowing Purl." - Chris Coffin
* "We don't require the match criteria ID because that is assigned by NIST." - Chris Coffin
* "There's a pull request in right now." - Chris Coffin
* "Any input from the community is great and we want more participation on the QWG." - Chris Coffin
* "We're talking right now about standing up a consumer working group." - Chris Coffin
* "We're trying to tighten some things up." - MZ
* "We're working in that direction, but kind of at a steady pace." - MZ
* "Pull requests are kind of how these ideas are floated." - MZ
* "We're looking at adding SSVC." - MZ
* "There's going to be times where we're going to have to remove properties." - Chris Coffin
* "We need a way if there's something in the schema that's no one's using." - MZ
* "We've had to make minor changes and CNAs have had to clean up some stuff." - Chris Coffin
* "Usually a phased approach should look something more like an API versioning change." - Audience Member
* "There has to probably be a phased approach." - MZ
* "We'd love input on." - Chris Coffin


HABITS
* Chris Coffin actively drives CVE record format improvements.
* MZ advocates for consumer feedback and data quality.
* They collaborate closely with other CVE working groups.
* They use GitHub for managing schema changes and discussions.
* They prioritize community input and encourage participation.
* They aim for a steady pace of improvement and change.
* They use a phased approach for deprecating schema elements.
* They value clear communication and documentation.
* They recognize the importance of human-readable narratives.
* They strive for good quality data for consumers.


FACTS
* CVE record format is currently at version 5.1.1.
* CVSS4 was added in version 5.1.0.
* CPE applicability statements were improved in version 5.1.1.
* The CVE-S schema is hosted on GitHub.
* SemVer is a standardized versioning system.
* Purl is a software identifier.
* SSVC is being used by CISA ADP.
* All 4.0 CVE records have been migrated to 5.0.
* NVD enriches CVE records.
* ADPs have a defined scope.


REFERENCES
* CVE record format
* JSON schema
* CVSS4
* CPE
* cve.org
* GitHub (CVE-S schema repository)
* SemVer
* Purl
* SSVC
* NVD
* ADP
* VEX


ONE-SENTENCE TAKEAWAY
Evolve the CVE record format through community collaboration, focusing on data quality and consumer needs.


RECOMMENDATIONS
* Join the quality working group (QWG) to contribute to the CVE record format.
* Provide feedback on the CVE-S schema through the GitHub repository.
* Use the updated CPE applicability statements for better data quality.
* Adopt SemVer for versioning to improve automation and data analysis.
* Consider using Purl as a software identifier in CVE records.
* Familiarize yourself with SSVC for stakeholder-specific vulnerability classification.
* Review the CVE quick start guide on cve.org for CPE usage.
* Participate in discussions about removing obsolete schema properties.
* Provide detailed narrative descriptions in CVE records for improved usability.
* Consider the impact of schema changes on existing tools and processes.
* Explore the use of API versioning for managing major schema updates.
* Advocate for increased minimum requirements for narrative fields.
* Share your approach to writing CVE descriptions with the community.
* Learn about the ADP program and its implications for the CVE ecosystem.
* Consider becoming an ADP to contribute additional information to CVE records.
* Research the potential for integrating VEX data into CVE records.
* Review existing CVE records for opportunities to enhance with ADP information.
