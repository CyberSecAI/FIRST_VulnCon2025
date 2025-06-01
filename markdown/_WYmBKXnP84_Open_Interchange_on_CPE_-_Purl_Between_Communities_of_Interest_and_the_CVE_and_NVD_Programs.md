# Open Interchange on CPE - Purl Between Communities of Interest and the CVE and NVD Programs

**Video URL:** [https://www.youtube.com/watch?v=_WYmBKXnP84](https://www.youtube.com/watch?v=_WYmBKXnP84)
**Video ID:** _WYmBKXnP84

---

SUMMARY
Pete, Chris, and others discuss software identification, focusing on CPE, Pearl, and data consumer needs.

IDEAS
* Standardizing software identification helps consumers understand vulnerabilities.
* CPE and Pearl can be combined for comprehensive software identification.
* Data consumers need easily accessible and accurate vulnerability information.
* CNAs should provide standardized software identification in CVE records.
* Vulnerability scanners struggle with inconsistent software names and versions.
* A single, authoritative source of truth for software identification is needed.
* Temporal scoring is crucial for accurate vulnerability assessment.
* Collaboration between vendors, CNAs, and consumers is essential.
* Clear guidance for CNAs on providing software identification is needed.
* The CPE dictionary needs improvement and standardization.
* VEX files can provide detailed component-level vulnerability information.
* A hierarchical approach to software identification is necessary.
* Namespacing can help manage complex software hierarchies.
* Controlled ontologies can improve the consistency of software names.
* The CVE program should consider tiering CNAs based on data quality.
* Open-source collaboration can help improve software identification tools.
* Security teams should be responsible for software identification within companies.
* Clear definitions of "component" and "product" are needed.
* Automation can improve the efficiency of software identification.
* Transparency and open communication are crucial for progress.
* Data sharing is essential for accurate vulnerability assessment.
* Regulation may be necessary to improve data sharing.
* The CVE record format should support more detailed product information.
* The parent-child problem of nested components needs to be addressed.
* SPDX has limitations in tracking hierarchical relationships.
* Alias services are necessary for mapping different software names.
* The vendor and product fields in CVE records are often inconsistent.
* Vendors should provide authoritative lists of their product names.
* Many third-party vendors have informal or unclear names.

INSIGHTS
* Accurate software identification is crucial for effective vulnerability management.
* Collaboration and standardization are key to solving software identification challenges.
* Data consumers need clear, consistent, and easily accessible vulnerability data.
* The CVE program needs to evolve to address the changing software landscape.
* A hierarchical approach is necessary for managing complex software dependencies.
* Temporal scoring and exploitability should be considered in vulnerability assessment.
* Clear guidance and requirements for CNAs can improve data quality.
* Open-source collaboration and data sharing can accelerate progress.
* The CPE dictionary needs to be more than just a list of identifiers.
* Controlled ontologies and alias services can improve naming consistency.

QUOTES
* "The next big thing that we're looking towards is Pearl." - Kind
* "We have a data classification problem." - Pete
* "It's their dictionary." - Pete
* "We're trying to contribute to the dictionary." - Pete
* "If you can't identify the components, you're really in a creek." - Pete
* "We just don't have it well accounted for." - Pete
* "There's no single source of truth." - Andrew
* "Surely CNAs should know the most about their own vulnerabilities." - Andrew
* "They're the ones that know the products best." - Kind
* "The CNA is authoritative source." - Pete
* "Every vulnerability gets an identifier." - Pete
* "That's the crux of the problem." - Pete
* "We use them." - Orca Security
* "MVD is struggling with bone enrichment." - Orca Security
* "The single source of truth for a long time." - Orca Security
* "We need a single source of truth." - Orca Security
* "They do all add CPE data to their CVE records." - Cisco
* "They pretend like they're NVD." - Cisco
* "They don't follow the versioning very well." - Cisco
* "We have a data issue." - Pete
* "You want accuracy." - Pete
* "How the hell you fill up your data pool?" - B
* "We need whatever we can get now." - Orca Security
* "That's a hard truth." - Pete
* "Commercial and open source are different." - Kind
* "It depends on some government agency that has four letters." - Kind
* "We all have to modify it." - Kind

HABITS
* Pete and Kind put tons of planning into their discussions.
* Pete focuses on understanding the consumer's perspective.
* Kind focuses on data producers and their workflows.
* Andrew analyzes vulnerability data and identifies inconsistencies.
* Orca Security uses CPEs for product identification.
* Cisco tests various SCA tools and analyzes their CPE data.
* Red Hat provides security advisories and VEX data.
* Pete advocates for using temporal scores in vulnerability assessment.
* Kind emphasizes the importance of collaboration in the industry.
* Bruce collects data from various sources.
* Martin works with scanning vendors on data consumption.
* Fung develops ideas for nesting data in JSON structures.
* Ed analyzes CVE records and vendor websites for consistency.
* Christina focuses on the parent-child problem of components.
* Lisa assigns CPEs based on NVD's practices.
* Pete mandates the use of SBOMs and VEX files.
* Bruce focuses on getting accurate vendor names.
* Jonathan hates alias services.
* Alec works on software identity issues.
* Megazin advocates for CNAs providing their own data.
* Tom questions the consistency of product names within companies.

FACTS
* MVD has the CVE dictionary.
* CVE JSON files are issued by CNAs.
* The CVE program federated the publication of CVE records since 2016.
* Anchor pulls in RHSAs and security notices.
* Red Hat provides VEX files with CPE and Pearl data.
* EPSS has difficulty reading open source.
* Kernel 731 had numerous CVEs affecting many organizations.
* Microsoft includes CPEs in their CVEEs.
* The MVD CPE dictionary hasn't been updated recently.
* CISA will be an ISO standard.
* Red Hat rescores vulnerabilities based on product usage.
* Red Hat uses a severity score for prioritizing fixes.
* CVSS is not always used for determining fixes.
* CVSS was designed with base, temporal, and environmental scores.
* The security industry primarily uses the base score.
* Red Hat uses CPE at the application level and Pearl at the component level.
* NVD moved from CPE strings to JSON workarounds for versions.
* CPE 2.3 is considered outdated and unusable.
* SIFT creates CPEs on the spot based on observed attributes.
* Pearl is more package-module specific than CPE.
* NVD claims to enrich 80% of CVE records.
* Less than one-third of CVEs have a CPE assigned.
* Many third-party vendors have informal names.
* SPDX allows tracking relationships between components.

REFERENCES
* CPE
* Pearl
* CVE
* MVD
* SBOM
* VEX
* RHSAs
* Debian Security Notices
* Ubuntu Security Notices
* Omnivore
* Anchor
* BlackDuck
* Net Rise
* SIFT
* Guac
* SPDX
* EOX
* MVBE
* ADP
* CISA
* ISO
* CVSS
* CWE
* JSON
* OpenShift
* RHEL

ONE-SENTENCE TAKEAWAY
Standardize software identification using CPE and Pearl, focusing on consumer needs and collaboration.

RECOMMENDATIONS
* CNAs should provide consistent and accurate CPE and Pearl data in CVE records.
* Develop a single, authoritative source of truth for software identification.
* Create clear guidance for CNAs on providing software identification data.
* Improve the CPE dictionary with mappings to products and vendors.
* Encourage the use of VEX files for detailed component-level information.
* Develop a standardized approach for handling the parent-child problem.
* Promote open-source collaboration and data sharing in the industry.
* Implement namespacing and controlled ontologies for consistent naming.
* Consider tiering CNAs based on the quality of their data.
* Educate security vendors on using CPE, Pearl, and VEX data effectively.
* Encourage vendors to provide authoritative lists of their product names.
* Develop a system for resolving different names for the same product.
* Use a hierarchical approach to track CVEs through software layers.
* Implement temporal scoring and exploitability in vulnerability assessment.
* Ensure transparency and open communication between all stakeholders.
* Explore the use of a name service-like lookup for software identification.
* Consider regulation to improve data sharing and transparency.
* Standardize the definition of "component" and "product" across the industry.
* Automate the process of software identification and vulnerability mapping.
* Focus on the needs of data consumers and provide easily accessible information.
* Encourage the use of the ADP technology for adding relevant data to records.
* Allow distros and package managers to provide relevant information.
* Develop a common language for describing software components and packages.
* Design open-source tools for managing software identification and vulnerabilities.
