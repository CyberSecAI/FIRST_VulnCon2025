# Unlocking the Power of SBOMs_ A Deep Dive into Risk Management and Cybersecurity Posture

**Video URL:** [https://www.youtube.com/watch?v=ubkslIonQDg](https://www.youtube.com/watch?v=ubkslIonQDg)
**Video ID:** ubkslIonQDg

---

SUMMARY
John Bergland and Zardia Alden discuss IBM's ESBOM analysis program, focusing on its use, challenges, trends, and automation.

IDEAS
* ESBOMs reveal software ingredients, dependencies, and libraries, crucial for security management.
* Organizations may want ESBOMs for procurement, but they are useless without proper analysis.
* ESBOM analysis reveals security posture, software practices, and vulnerability management.
* IBM emphasizes latest release levels, back-level packages, and unread percentages in ESBOMs.
* Latest open-source libraries have the latest security patches, crucial for vulnerability management.
* Back-level libraries may not be scanned for newer vulnerabilities, creating a security gap.
* Unread percentages may indicate missing identifiers like PURLs, CPEs, requiring examination.
* 80% of identified vulnerabilities could be addressed by updating open-source libraries.
* Log4j vulnerability analysis includes pervasiveness and risk assessment for remediation.
* ESBOM analysis considers severity, age, KEV association, and version of vulnerabilities.
* Old CVEs may indicate unfixed issues, legacy vulnerabilities, or require special attention.
* KEV association indicates real-world exploits, requiring immediate attention and remediation.
* Back-level versions may indicate deprecated or unsupported libraries, posing security risks.
* New standards will validate out-of-support open-source libraries and define support status.
* Automation is key to scaling ESBOM analysis and keeping up with the increasing volume.
* Securely and efficiently sharing ESBOM information with vendors is a growing challenge.
* Iterative remediation requires evidence of fixes and reprocessing of ESBOMs.
* Platforms like Sibes and Fossa address secure information sharing and remediation challenges.
* ESBOM noise includes non-production code, scanning issues, and vulnerability data problems.
* Non-production code in ESBOMs can distract development efforts from critical areas.
* Go.sum files can be used for both development and production dependencies, causing confusion.
* Scanning configuration issues can lead to test and development code in production ESBOMs.
* Different scanners produce different results, highlighting blind spots and awareness gaps.
* Poor housekeeping, like including end-of-life products, adds noise to ESBOMs.
* Vulnerability data issues include reporting CVEs for unaffected versions and unknown CVEs.
* NVD backlog and analysis states can cause discrepancies between vendor and IBM data.
* Improving ESBOM accuracy involves package manager cleanup, VEX adoption, and data refinement.
* Continuous reviews of ESBOMs are essential due to continuous development and releases.

INSIGHTS
* ESBOM analysis is crucial for understanding and managing software supply chain risks.
* Effective ESBOM utilization requires analysis, automation, and secure information sharing.
* Keeping open-source libraries up-to-date significantly reduces vulnerabilities.
* Analyzing CVE age, KEV association, and version helps prioritize remediation efforts.
* ESBOM noise hinders accurate analysis and requires addressing underlying issues.
* Automating ESBOM analysis significantly improves efficiency and reduces processing time.
* Collaboration and information sharing with vendors are crucial for effective remediation.
* Contributing to open-source tools like Dependency Track enhances the overall ecosystem.
* Continuous ESBOM reviews are necessary to keep up with evolving software landscapes.
* Addressing versionless components requires direct engagement with development teams.

QUOTES
* "An SBOM in a bucket is completely useless." - Ian from Lockheed Martin and Michael from Kusari
* "80% of the vulnerabilities identified could be immediately addressed if all of the open-source libraries being used were simply up to the latest level." - John Bergland
* "It's pretty tricky navigating ESBOMs right now in the corporate environment." - John Bergland
* "CVSS score should absolutely be a required field." - Jerry
* "So, how to do that iterative remediation effectively and still be able to continue to scale?" - John Bergland
* "So, what we're doing by this VEX template, we're laying it out very clearly." - John Bergland
* "This is obviously super confidential information from both vendors and our analysis." - John Bergland
* "So, it's components that make it they make their way into the SBOM that actually don't make up the production code." - Zardia Alden
* "Unfortunately, we can't make that blanket exclusion because actually we're seeing some development teams using that for their production dependencies." - Zardia Alden
* "So, if you like, it's a little bit of a pre-alert to those development teams that that may well land on their dashboard." - Zardia Alden
* "So, encouraging teams to run the go tidy commands mpm proom so that actually what we see in their package manager files are actually the dependencies that are being used." - Zardia Alden
* "So, we should be continuously reviewing what's in our SBOMs." - Zardia Alden
* "95% reduction in the time it takes to assess the yes bombs which is much needed if that trend continues." - Zardia Alden
* "So, that constant thinking about how can we give back to the open source community." - John Bergland

HABITS
* Analyze ESBOMs for vulnerabilities, open-source packages, and dependencies.
* Focus on critical and high severity vulnerabilities for immediate remediation.
* Consult multiple sources for vulnerability information due to unassigned severities.
* Investigate the age of CVEs to understand vulnerability history and potential risks.
* Prioritize remediation based on severity, age, KEV association, and version of CVEs.
* Flag and identify back-level or unsupported libraries for potential security risks.
* Automate ESBOM analysis to scale with increasing volume and improve efficiency.
* Share ESBOM information securely and efficiently with vendors for collaboration.
* Perform iterative remediation with evidence of fixes and ESBOM reprocessing.
* Engage with development teams to understand and address versionless components.
* Encourage package manager cleanup to ensure accurate dependency tracking.
* Promote VEX adoption for standardized vulnerability information exchange.
* Continuously review ESBOMs to stay updated on evolving software components.
* Contribute to open-source projects like Dependency Track to improve the ecosystem.

FACTS
* 80% of identified vulnerabilities are addressable by updating open-source libraries.
* Unassigned vulnerabilities are an increasing challenge due to NVD backlog.
* CVSS score is not always a required field, creating ambiguity in severity assessment.
* KEV association indicates a real-world exploit of a vulnerability.
* ESBOM analysis volume has seen exponential growth, requiring automation for scaling.
* Secure transport of ESBOM information is crucial due to its confidential nature.
* Spreadsheets are preferred by many vendors for visualizing vulnerability information.
* VEX templates can help standardize vulnerability data while maintaining visual clarity.
* Different scanners can yield different results, highlighting potential blind spots.
* NVD analysis states can cause discrepancies in vulnerability data.
* 22% of analyzed ESBOMs contain non-production code.
* 27% of analyzed ESBOMs show scanning and configuration issues.
* 40% of analyzed ESBOMs have issues with vulnerability data.
* Automation has reduced ESBOM assessment time by 95%.

REFERENCES
* ESBOM
* VEX
* PURL
* CPE
* NVD
* CVE
* CWE
* KEV
* Dependency Track
* OASP Foundation
* Biden Executive Order (May 2021)
* NIS Directive
* CRA
* Lockheed Martin
* Kusari
* Prisma Cloud
* Twistlock
* Log4j
* Sibes
* Fossa
* Go.sum
* Requirements.ext
* pom.xml
* Cargo.lock
* Cargo.toml
* Mend
* Dependabot
* Cyber Beats
* GitHub
* Discord

ONE-SENTENCE TAKEAWAY
Automate ESBOM analysis, address noise, and collaborate with vendors for effective vulnerability management.

RECOMMENDATIONS
* Implement ESBOM analysis to gain insights into software composition and security.
* Automate ESBOM processing and reporting to improve efficiency and scale.
* Prioritize remediation based on vulnerability severity, age, and exploit status.
* Address ESBOM noise by cleaning up package managers and improving scanning.
* Encourage vendors to adopt VEX for standardized vulnerability communication.
* Use multiple vulnerability data sources to mitigate NVD backlog limitations.
* Engage with development teams to resolve versionless components and data gaps.
* Continuously review and update ESBOMs to reflect evolving software landscapes.
* Contribute to open-source tools and initiatives to enhance the ecosystem.
* Foster collaboration and secure information sharing with vendors for remediation.
