# Practical Software Bill of Materials_ From Generation to Distribution Workshop

**Video URL:** [https://www.youtube.com/watch?v=hhq751ELIVw](https://www.youtube.com/watch?v=hhq751ELIVw)
**Video ID:** hhq751ELIVw

---

SUMMARY
Adula Garcia and Mike, from OpenSSF, discuss SBOM generation, sharing, operations, and verification.

IDEAS
* Generate better SBOMs by augmenting and enriching them with key metadata.
* Augmentation adds top-level metadata like copyright and descriptions.
* Enrichment adds metadata to components, such as licenses and authors.
* Verify SBOMs by schema and completeness, including attestations.
* Choose SBOM generation tools based on package manager and language.
* Consider the purpose and audience when deciding how much data to include.
* More data is generally better, as it can be filtered later if needed.
* SPDX has potential for tracking parent-child relationships between packages.
* Tools like guac and deps.dev can help analyze relationships.
* Verify SBOMs using tools like cosign and sbombqs.
* Sign SBOMs using detached signatures or attestations.
* Distribute SBOMs with artifacts, ensuring accessibility via standard protocols.
* Avoid emailing SBOMs; use repositories or dedicated exchanges.
* Verify received SBOMs, checking signatures and identities.
* Use bombl to fetch and push SBOMs in a tree structure.
* Push SBOMs to OCI registries or other exchanges.
* Correlate SBOMs with vulnerability data using tools like OSV scanner.
* Use tools like duct DB or guac to analyze multiple SBOMs.
* Track changes between SBOM versions to identify fixes and regressions.
* Use policy as code to automate actions based on SBOM data.
* Correlate SBOM data with runtime analysis using tools like Cubescape.
* Consider future work like patch planning and attack graph analysis.
* Funding and collaboration are crucial for improving SBOM ecosystem.
* Hardware and infrastructure as code SBOMs are less mature.
* Runtime correlation tools are emerging to address this gap.
* Attend Porco's talk on attested VEX in Kubernetes.
* All workshop materials are available in the provided GitHub repo.

INSIGHTS
* High-quality SBOMs require both automated generation and manual curation.
* The purpose of an SBOM dictates the level of detail and included metadata.
* Verification and signing are essential for ensuring SBOM integrity and trust.
* Sharing SBOMs effectively requires standardized protocols and exchanges.
* Operationalizing SBOMs involves correlation with vulnerability and runtime data.
* Tools like guac and bombl facilitate SBOM management and analysis.
* Collaboration and funding are key to advancing the SBOM ecosystem.
* SBOMs are evolving beyond compliance to support vulnerability management and security analysis.
* Runtime correlation bridges the gap between SBOMs and deployed systems.
* The future of SBOMs involves automation, policy as code, and attack graph integration.

QUOTES
* "Better SBOM generation is like let's fill in those missing fields that actually make these things practical beyond just the list of components." - Mike
* "I really encourage folks to do more than just pull out SIFT, Trivy, some other tool and generate an NSBOM and slap it on a project and send it out." - Mike
* "This is your product. Take credit for it." - Mike
* "You don't really know how your user is going to use your SBOM and so more data is better." - Adula Garcia
* "It's highly dependent on what is the purpose of the SBOM, what are you trying to communicate to whoever is consuming that SBOM." - Mike
* "The more information you have in the SBOM, it's always possible to take like a fully loaded SBOM and distill it to a simpler document that is more fit to the use case." - Mike
* "Verifying the results is at times it can be super subjective." - Porco
* "The documents are supposed to be read by machines. So put them in some place that machines can get them." - Porco
* "Please don't email them." - Porco
* "Right now SBOMs are mostly being used for compliance." - Mike
* "They actually do have a lot of great uses." - Mike
* "You don't necessarily need to use the guac sort of ingestment ingestion system." - Mike
* "You can use curl for a lot of that." - Mike
* "Vulnerabilities are reported and discovered." - Mike
* "Hey, I ran a scan against the SBOM yesterday, no vulnerabilities. Today, vulnerability was discovered." - Mike
* "Am I using 12 different versions of the same log for J right and that actually all of them are vulnerable or half of them are vulnerable?" - Mike
* "The answer is the work is being done." - Mike
* "The challenge again is going to be making sure that the funds are there so that they can hit that because hey we're all in open source, right?" - Mike
* "You need to fix this. No, I don't. You don't pay me, so I don't need to fix anything." - Mike
* "Nobody wants to be unsafe generally." - Mike
* "If you are not tired of seeing attestations and you want to see them in action on how we're using attested VEX in the Kubernetes project to shoot the projects VEX feeds I'm going to do a talk in like an hour from now." - Porco

HABITS
* Automate SBOM generation and augmentation in your build pipeline.
* Regularly verify and sign SBOMs to ensure integrity and trust.
* Share SBOMs via repositories or dedicated exchanges, not email.
* Correlate SBOM data with vulnerability and runtime information.
* Use tools like guac and bombl to manage and analyze SBOMs.
* Continuously monitor for new vulnerabilities and update SBOMs.
* Prioritize vulnerability remediation based on impact and scope.
* Use policy as code to automate security actions based on SBOM data.
* Collaborate with open source maintainers and foundations.
* Consider forking critical single-maintainer projects for greater control.
* Attend conferences and workshops to stay up-to-date on SBOM best practices.
* Follow along with the tutorial in the provided GitHub repository.

FACTS
* SBOMs are increasingly required for compliance purposes.
* Many SBOM generation tools lack key metadata like licenses and authors.
* SPDX and CycloneDX are the two most common SBOM formats.
* Six is an OpenSSF project that simplifies SBOM signing.
* Bombl is an OpenSSF project for fetching and pushing SBOMs.
* OSV scanner utilizes the OSV database for vulnerability information.
* Clearly Defined is an OSI project that analyzes open source licenses.
* Duct DB is an in-memory database suitable for analyzing small sets of SBOMs.
* Guac is an open source tool for tracking SBOM changes over time.
* Cubescape is a CNCF project for runtime security analysis in Kubernetes.
* Alpha Omega is an OpenSSF directed fund supporting SBOM initiatives.
* Pippi is a completely nonprofit package manager.
* The Transparency Exchange API is under development for standardized SBOM exchange.

REFERENCES
* SIFT
* Trivy
* SBOM producer lifecycle
* Interlinks
* sbom-aem
* jQ
* SPDX
* CycloneDX
* Parlay
* Ecosystems
* NTI minimum elements
* Keycloak
* cosign
* sigstore
* sbombqs
* protobom
* bombl
* sbombit
* guac
* deps.dev
* OCI
* SPDX
* CycloneDX
* JSONL
* GitHub
* GitLab
* manifest
* dependency track
* SKID
* Transparency Exchange API
* Adigma
* OpenSSL
* OSV scanner
* OSV database
* GitHub Security Advisories
* npm
* npm audit fix
* dependabot
* OPA
* Cubescape
* CNCF
* YouTube
* Alpha Omega
* OpenSSF
* LF (Linux Foundation)
* OSI (Open Source Initiative)
* Clearly Defined
* MIT license
* AGPL license
* duct DB
* Terraform
* VPC
* Helm chart
* docker-compose

ONE-SENTENCE TAKEAWAY
Generate, enrich, verify, sign, and share SBOMs to improve software supply chain security.

RECOMMENDATIONS
* Augment SBOMs with top-level metadata for better context.
* Enrich SBOMs with component details like licenses and authors.
* Verify SBOMs using schema validation and completeness checks.
* Sign SBOMs using detached signatures or attestations for trust.
* Distribute SBOMs via repositories or exchanges for easy access.
* Use bombl to manage and transfer SBOMs efficiently.
* Correlate SBOMs with vulnerability data for risk assessment.
* Analyze multiple SBOMs using tools like duct DB or guac.
* Track SBOM changes to identify vulnerabilities and fixes.
* Use policy as code to automate actions based on SBOM insights.
* Correlate SBOM data with runtime analysis for actionable insights.
* Explore tools like guac and Cubescape for advanced SBOM operations.
* Contribute to open source SBOM projects and initiatives.
* Support open source maintainers and foundations financially.
* Consider forking critical single-maintainer projects for stability.
* Explore emerging tools for infrastructure as code SBOM management.
