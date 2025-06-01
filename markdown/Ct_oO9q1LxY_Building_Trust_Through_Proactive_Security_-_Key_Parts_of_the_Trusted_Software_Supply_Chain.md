# Building Trust Through Proactive Security - Key Parts of the Trusted Software Supply Chain

**Video URL:** [https://www.youtube.com/watch?v=Ct_oO9q1LxY](https://www.youtube.com/watch?v=Ct_oO9q1LxY)
**Video ID:** Ct_oO9q1LxY

---

**SUMMARY**
Premaruski (Rogue), Red Hat security engineer, discusses proactive security in the software supply chain.

**IDEAS**
* Proactive security tests and verifies product components before release to customers.
* Shift-left approach emphasizes deep software testing and verification before product release.
* Proactive security should be integrated into the build and release process, not a side process.
* Conflux, Red Hat's new pipeline, is open-source and prioritizes supply chain security.
* Conflux meets Salsa Level 3 requirements and produces necessary artifacts.
* Tecton Chains, a Kubernetes custom resource definition controller, manages supply chain security.
* Conform validates predefined policy rules for builds.
* Proactive vulnerability management helps identify and address weaknesses before release.
* Combining SAS scanning results with CVE data can reveal patterns and improve prioritization.
* Prioritizing weaknesses based on patterns can reduce vulnerabilities and improve customer experience.
* Data standardization is crucial for combining SAS results and CVE data for analysis.
* AI-based analysis can identify patterns and improve weakness identification.
* Prioritizing repeating weaknesses, even without past CVEs, can prevent future vulnerabilities.
* Addressing root causes of vulnerabilities is more effective than just fixing individual instances.
* Focusing on weakness classes, rather than individual IDs, provides a broader perspective.
* Considering exploitability and EPSS scores can enhance prioritization.
* Precise root cause information in CVE records is essential for effective analysis.
* Focusing on CWE categories, not just IDs, helps identify broader patterns.
* Addressing patterns within weakness classes can prevent similar vulnerabilities in the future.
* Proactive security aims to prevent vulnerabilities, not just react to them.
* Integrating security into the SDLC is crucial for building secure software.
* Automation and gating based on findings can improve security.
* Proactive security requires collaboration between development and security teams.
* Continuous improvement and data analysis are key to effective security.
* Proactive security reduces the need for reactive responses.

**INSIGHTS**
* Proactive security shifts the focus from reaction to prevention in the SDLC.
* Integrating security testing within the build pipeline ensures early vulnerability detection.
* Automating security checks and gating builds based on results strengthens the supply chain.
* Combining proactive and reactive vulnerability management provides a comprehensive approach.
* Data standardization and AI analysis enable pattern identification for better prioritization.
* Addressing root causes and weakness classes, not just individual CVEs, leads to more secure code.
* Prioritizing repeating weaknesses, even without prior CVEs, is crucial for proactive security.
* Continuous improvement through data analysis and pattern recognition enhances security posture.
* Open-source tools and collaboration are essential for building a secure software ecosystem.
* Proactive security improves customer experience by reducing vulnerabilities in released products.

**QUOTES**
* "Proactive security work plays a key role in the trusted supply chain." - Premaruski
* "We want to collect as much as possible information from the build process." - Premaruski
* "All that work is to make sure that everyone understands and follow the real risk-based security, not a security checkboxing." - Premaruski
* "Security is built in in a software supply chain." - Premaruski
* "Conflux is built around software supply chain security by default." - Premaruski
* "There's no task that is just executed and there is no evidence what happened." - Premaruski
* "We can use this information from the build time to improve what is on the other side when the product is already released." - Premaruski
* "Many times owners of the product instead of trying to find what is the problem, real problem, what is the root cause, they just want to, okay, let's just fix it." - Premaruski
* "That's what I'm trying to show here that, okay, we see that problems and patterns. So let's just prioritize some of them." - Premaruski
* "If something is repeating again and again in SAS results, if I address the top priority, I can get back and find another patterns, what is repeating again." - Premaruski

**HABITS**
* Tests and verifies product components before release to customers.
* Collects information from the build process to ensure correctness.
* Follows risk-based security practices, not just checkboxing.
* Integrates security into the software supply chain by default.
* Maintains evidence of all executed tasks in the pipeline.
* Uses information from build time to improve released products.
* Analyzes patterns and prioritizes security work accordingly.
* Addresses root causes of problems, not just surface-level fixes.
* Uses data standardization for combining different data sources.
* Employs AI-based analysis to find patterns and prioritize work.
* Focuses on weakness classes rather than individual IDs.
* Considers various metrics like EPSS scores for prioritization.
* Cleans and analyzes CVE records data for pattern identification.
* Participates in CWE root cause mapping working groups.
* Continuously improves prioritization models based on new data.

**FACTS**
* Red Hat is actively working on a new pipeline called Conflux.
* Conflux is an open-source build, test, and release factory.
* Conflux is based on Tecton, a cloud-native CI/CD solution.
* Conflux meets Salsa Level 3 requirements.
* Tecton Chains manages supply chain security in Tecton.
* Conform validates predefined policy rules for builds.
* SAS scanning results often contain many false positives.
* Many vulnerabilities are reported every single day.
* CVE records contain information about associated weaknesses.
* CWE root cause mapping is being strongly pushed by working groups.

**REFERENCES**
* Conflux
* Tecton
* Tecton Chains
* Conform
* Salsa
* CVE
* CWE
* SAS
* Sbombs
* Cysaf
* Vex
* Open UX
* Red Hat
* ROCV data
* Red Hat CVE database
* Metasloit
* Exploit DB
* EPSS

**ONE-SENTENCE TAKEAWAY**
Prioritize fixing recurring weakness patterns in software to prevent future vulnerabilities and improve security.

**RECOMMENDATIONS**
* Integrate proactive security testing into the build pipeline.
* Use data analysis and AI to identify recurring weakness patterns.
* Prioritize remediation based on patterns, not just individual CVEs.
* Address root causes of vulnerabilities, not just symptoms.
* Collaborate and share information to improve security practices.
* Focus on weakness classes, not just individual weakness IDs.
* Consider exploitability and EPSS scores for prioritization.
* Ensure precise root cause information in CVE records.
* Use data standardization for combining different data sources.
* Continuously improve prioritization models based on new data.
* Participate in CWE root cause mapping working groups.
* Use open-source tools like Conflux and Tecton for security.
* Collect information from the build process for analysis.
* Follow risk-based security practices, not just checkboxes.
* Maintain evidence of all executed tasks in the pipeline.
