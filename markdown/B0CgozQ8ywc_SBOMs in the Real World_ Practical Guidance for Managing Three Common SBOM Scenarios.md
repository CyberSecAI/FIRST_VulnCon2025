# SBOMs in the Real World_ Practical Guidance for Managing Three Common SBOM Scenarios

**Video URL:** [https://www.youtube.com/watch?v=B0CgozQ8ywc](https://www.youtube.com/watch?v=B0CgozQ8ywc)
**Video ID:** B0CgozQ8ywc

---

**SUMMARY**
Cortez Fraser Jr. discusses ESBOMs, focusing on generation, vulnerability management, supplier enforcement, and workflows.

**IDEAS**
* Generate SBOMs regularly, ideally per build, commit, deployment, and release cycle.
* Prioritize full dependency graphs, including transitive dependencies and labels.
* Use unique identifiers like Package URL for accurate component identification.
* Avoid CPEs due to inaccuracies and focus on asset identification.
* Centralize vulnerability management for enterprise-wide decisions.
* Prioritize fixes based on risk reduction, not elimination.
* Use SSVC or a custom decision tree for vulnerability prioritization.
* Group fixes and vulnerabilities to maximize remediation efficiency.
* Consider exploitability and breaking changes when prioritizing fixes.
* Enforce ESBOM standards on external suppliers for transparency.
* Validate supplier compliance with vulnerability and license requirements.
* Use unique identifiers to enrich supplier SBOM data.
* Maintain continuous communication with suppliers about new vulnerabilities.
* Combine internal and external SBOMs for a final artifact.
* Automate SBOM validation and policy enforcement.
* Generate SBOMs at every SDLC stage for comprehensive analysis.
* Diff SBOMs across stages to identify package introduction points.
* Tag packages with labels for better tracking and analysis.
* Don't block builds with SBOM generation; run scans separately.
* Scan all components, including container dependencies.
* Share SBOMs transparently to improve industry security.
* Consumers must improve SBOM import and monitoring capabilities.
* Continuous communication is better than delayed, "complete" SBOMs.
* Generate SBOMs at build time for accurate dependency graphs.
* Runtime relationships are unreliable; prioritize build-time analysis.
* SBOMs are vehicles for communicating software supply chain risk.
* Transparency is crucial for improving overall industry security.
* Commercial pressure will drive SBOM adoption, not just government.

**INSIGHTS**
* Comprehensive SBOMs are crucial for managing software supply chain risk.
* Effective vulnerability management requires centralized oversight and prioritization.
* Collaboration and transparency with suppliers are key for security.
* Automation is essential for efficient SBOM generation and analysis.
* Continuous monitoring and communication are vital for addressing new vulnerabilities.
* Accurate component identification and dependency graphs are fundamental.
* Shift focus from risk elimination to risk reduction for practical remediation.
* SBOMs are evolving from ad-hoc documentation to standardized data exchange.
* Industry-wide adoption of SBOMs requires both supplier and consumer maturity.
* Transparency and communication are essential for maximizing SBOM value.
* Build-time SBOM generation offers the most accurate dependency information.
* Effective SBOM utilization requires integration into vulnerability management programs.
* Supplier enforcement of SBOM standards is crucial for supply chain security.
* Unique identifiers like Package URL are essential for accurate SBOM analysis.
* The future of SBOMs involves multi-stage generation and diff analysis.

**QUOTES**
* "Oftentimes people really get this confused literally just these two lines here. What is my state? Am I affected, not affected, under investigation or has it been fixed? And then what's the justification and detailed information surrounding that?" - Cortez Fraser Jr.
* "Oftentimes people call VEX, and I apologize, I know the gradient's probably not the easiest for you to see." - Cortez Fraser Jr.
* "How you choose to distribute your ESBOM is very, very important." - Cortez Fraser Jr.
* "A kind of guiding tagline that I want you to think about for this scenario two is how do I have the greatest overall reduction in my security posture with the least amount of refactor effort." - Cortez Fraser Jr.
* "Pearl's a thousand times better than CPE. Don't at me." - Cortez Fraser Jr.
* "I imagine this future where every organization has no problems publicly sharing asbombs." - Cortez Fraser Jr.
* "I'm giving away my IP." - Audience Member
* "If organizations do not intend to import an SBOM and actually do something with it, then they should not ask for them in the first place." - Cortez Fraser Jr.
* "The cat's out of the bag now." - Cortez Fraser Jr.
* "I view sbombs as essentially various vehicles for you to communicate software supply chain risk." - Cortez Fraser Jr.
* "You pick up a bottle of ketchup, you know what's in it, right?" - Cortez Fraser Jr.
* "I think we're at the very beginning of the sbomb maturity adoption uptake sort of style." - Audience Member
* "If someone says they can get accurate relationships in runtime, they are lying to you." - Cortez Fraser Jr.

**HABITS**
* Cortez Fraser Jr. challenges opinions to foster vigorous conversation.
* Cortez Fraser Jr. advocates for proactive vulnerability disclosure.
* Cortez Fraser Jr. prioritizes risk reduction over elimination.
* Cortez Fraser Jr. recommends pinning specific commits or releases.
* Cortez Fraser Jr. emphasizes continuous SBOM monitoring.
* Cortez Fraser Jr. advocates for automated SBOM generation and analysis.
* Cortez Fraser Jr. recommends using data sources like EPSS and VEX.
* Cortez Fraser Jr. emphasizes clear communication with suppliers.
* Cortez Fraser Jr. recommends enriching supplier SBOM data when possible.
* Cortez Fraser Jr. advocates for secure SBOM transmission methods.
* Cortez Fraser Jr. recommends combining internal and external SBOMs.

**FACTS**
* Approximately 27,000 CVEs were published in the previous year.
* The SolarWinds attack originated in a developer environment.
* SBOM regulation has intensified in the last 12-18 months.
* PCI 4.0 DSS requires an inventory of bespoke assets (ESBOM).
* FDA requirements impact medical device manufacturers significantly.
* UNR 155 indirectly mandates SBOMs in the automotive industry.
* SPDX and CycloneDX are the leading SBOM standards.
* An SBOM can be as simple as an Excel sheet (though JSON is preferred).
* VEX and VDR are distinct but related concepts.
* CPEs are created only after a vulnerability is discovered.
* Package URL provides specific namespaces for packages and versions.
* The number of vulnerabilities continues to increase annually.
* Most development teams use similar boilerplate tech stacks.
* Dependency confusion attacks exploit third-party code vulnerabilities.
* Threat actors typically use broad, not targeted, attacks.
* SBOMs do not give threat actors a significant advantage.
* Most organizations cannot currently import and monitor SBOMs.
* The Biden executive order drove SBOM momentum.

**REFERENCES**
* CycloneDX
* SPDX
* VEX
* VDR
* Package URL
* CPE
* Omnibore ID
* CESAF
* OpenVEX
* Dependency Track
* Faucet
* CNCF Portal
* Red Hat ESBOM Portal
* SSVC (Stakeholder Specific Vulnerability Categorization)
* EPSS
* EBSS
* Bone Check
* MVD++
* YTO
* Buildroot
* UNR 155
* PCI 4.0 DSS
* FDA Requirements
* Biden Executive Order on Supply Chain Security

**ONE-SENTENCE TAKEAWAY**
Implement robust ESBOM practices across your organization and with suppliers for enhanced software supply chain security.

**RECOMMENDATIONS**
* Generate and distribute SBOMs regularly for each build and release.
* Use Package URL for accurate component identification, avoiding CPEs.
* Centralize vulnerability management and prioritize risk reduction.
* Implement a clear vulnerability prioritization process using SSVC or a custom framework.
* Group vulnerability fixes to maximize remediation efficiency and minimize refactoring.
* Enforce ESBOM standards on suppliers and validate their compliance.
* Use unique identifiers to enrich supplier data and ensure data quality.
* Establish continuous communication with suppliers regarding new vulnerabilities.
* Combine internal and external SBOMs for a complete artifact overview.
* Automate SBOM validation and policy enforcement to streamline processes.
* Consider generating SBOMs at every SDLC stage for comprehensive analysis.
* Diff SBOMs across stages to pinpoint package introduction points and track changes.
* Tag packages with labels to enhance tracking and analysis capabilities.
* Decouple SBOM generation from build pipelines to avoid blocking deployments.
* Scan all components, including container dependencies, for complete coverage.
* Promote transparency by sharing SBOMs and fostering industry collaboration.
* Encourage consumers to improve SBOM import and monitoring capabilities.
* Prioritize continuous communication over delayed, "perfect" SBOM delivery.
* Generate SBOMs at build time for the most accurate dependency relationships.
