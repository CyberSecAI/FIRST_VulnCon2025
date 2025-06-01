# CPE Metadata_ Know IT ALL

**Video URL:** [https://www.youtube.com/watch?v=0RRqHIx5gsQ](https://www.youtube.com/watch?v=0RRqHIx5gsQ)
**Video ID:** 0RRqHIx5gsQ

---

SUMMARY
Infosc engineer at MongoDB discusses the importance of CPE metadata in vulnerability management and encourages CNAs to self-enrich.

IDEAS
* CPE metadata helps build robust vulnerability management processes.
* CPE is a standardized naming system for software and hardware.
* Standardized naming enables organizations in security management.
* CPEs provide consistency in naming within and between organizations.
* Standardized identifiers help automate security alert processing.
* NVD maintains a CPE dictionary of all known CPEs.
* CVEs contain title, description, and essential characteristics.
* CVSS score quantifies vulnerability severity and impact.
* CWE describes the weakness leading to the vulnerability.
* NVD slowed down enriching CVEs with crucial metadata.
* Slowdown can lead to miscategorized vulnerabilities.
* CNAs are not required to apply metadata when issuing CVEs.
* Only 13.3% of CVEs issued contain CPEs.
* The number of CVEs issued per year is increasing rapidly.
* The number of CNAs mirrors the trend of CVE issuance.
* Billions of products may have undocumented vulnerabilities.
* CNAs can publish CVEs via JSON files.
* NVD manually adds CPEs for many CVEs.
* Percentage of CPE inclusion spiked in 2023 and 2024.
* MVD and CISA are struggling with vulnerability enrichment.
* Many CNAs are already self-enriching their CVEs.
* Adding CPEs can be labor-intensive, requiring research.
* Inconsistent CPE inclusion is due to manual work involved.
* Increased awareness of CPEs is needed among CNAs.
* Widespread CPE integration prioritizes security.
* MongoDB has a long history of CVE self-enrichment.
* MongoDB now includes CPEs to better serve customers.
* CNAs can issue CVEs using JSON files with CPEs.
* MongoDB maintains its own CPE database in a Google Sheet.
* CPE version is important for maintaining consistency.
* Understanding CPE structure enables effective use.
* NVD is not a CNA or authorized data publisher.
* CNAs should add their own details to their CVEs.
* Managing CPEs internally is crucial for accuracy.
* Self-enriching improves vulnerability handling.

INSIGHTS
* CPEs are crucial for effective vulnerability management and automation.
* NVD's slowdown necessitates CNAs taking ownership of CPE enrichment.
* Self-enrichment by CNAs improves CVE quality and customer experience.
* Standardized naming with CPEs enables consistent vulnerability identification.
* The growing number of CVEs requires improved metadata practices.
* CPE inclusion in CVEs is low, highlighting a need for greater awareness.
* Automation relies on standardized identifiers like CPEs.
* CNAs have the ability and responsibility to enrich their own CVEs.
* Manual CPE addition is a bottleneck, driving the need for automation.
* Proactive CPE management by CNAs is essential for robust security.

QUOTES
* "Knowing a little bit more about CP metadata could help you build a more robust vulnerability management process." - Speaker
* "It's a standardized naming system uh for a software or hardware down to the specific version um or the configuration of that product." - Speaker
* "CPEs are a very easy way to enable organizations in security management." - Speaker
* "So with these standardized identifiers, automated systems can process security alerts more efficiently." - Speaker
* "So all CVES when they get published at some point um they get analyzed by an MVD analyst and those analysts they add metadata." - Speaker
* "So a lot of people actually depend on this data and historically MVD has been a key provider of uh enriched CDEs." - Speaker
* "But the kicker is that only 13% of 13.3% of all CBES issued contain CPEs." - Speaker
* "But here's something quite interesting. Uh CNAs are not required to apply metadata when issuing CVEes." - Speaker
* "Now this gap highlights an area of improvement uh definitely when it comes to bone enrichment." - Speaker
* "So as MVD continues to refine its processes, it's crucial to address the potential widening gap." - Speaker
* "And actually in a talk yesterday by Andrew um one of the very first talks in the morning yesterday he mentioned that the MVD and even CISA they're struggling with vone enrichment." - Speaker
* "Now it's also important to mention that although CNAs might have a history of adding CPEs uh they might not be able to do so for all the CBEEs that they issue." - Speaker
* "So besides spreading awareness, we encourage that all CNAs include CPEs in their CVEEs." - Speaker
* "MongoDB has had a long history of self-enrichment in CVEEs." - Speaker
* "So the initial setup is quite manual because you have to parse through the CPE dictionary." - Speaker
* "So the version is quite important so we can maintain consistency across um across systems." - Speaker
* "But yeah understanding the structure allows you to effectively use CPEs um in security management." - Speaker
* "But MVD has played a huge role in the CV system and the broader vulnerability management field." - Speaker
* "So when you're working on CPEs, first you have to make sure that there's not already a scheme present for your product." - Speaker
* "The recent slowdown with NVD showed us again why it's important to manage this process ourselves." - Speaker
* "I hope this message is quite going through like I'm drilling it quite a bit." - Speaker
* "CNA should be self-enriching." - Audience Member
* "what is the benefit to the CNA to do this and more because again I'm sure there's a cost in manpower, time, etc." - Audience Member

HABITS
* Maintains a CPE database updated with product releases.
* Uses a Google Sheet for CPE database management.
* Actively uses vulnerability scanners with contracts.
* Researches and creates CPEs for specific products.
* Communicates with customers about CVE discrepancies.
* Analyzes CVE JSON files for CPE inclusion.
* Reaches out to vulnerability scanner providers.
* Explains the CVE process to customers.
* Monitors NVD announcements and industry trends.
* Attends security conferences and talks.
* Prioritizes customer experience in security practices.
* Focuses on providing complete CVEs from the start.
* Encourages CNAs to include CPEs in CVEs.
* Strives for accurate vulnerability identification.
* Emphasizes self-enrichment for better vulnerability handling.
* Maintains consistent CPE versioning for compatibility.

FACTS
* CVE stands for Common Vulnerabilities and Exposures.
* CVSS stands for Common Vulnerability Scoring System.
* CWE stands for Common Weakness Enumeration.
* CNA stands for CVE Numbering Authority.
* CPE stands for Common Platform Enumeration.
* NVD stands for National Vulnerability Database.
* NVD is a supporting body of the CVE program.
* NVD maintains the CPE dictionary.
* NVD announced a slowdown in CVE enrichment in 2024.
* Over 50% of CVEs include CVSS and CWE.
* Only 13.3% of CVEs issued contain CPEs.
* Number of CVEs issued per year has been growing rapidly.
* In 2024, there was a 38% increase in CVEs issued.
* There are 447 CNAs as of data collection in 2025.
* NVD and CISA are struggling with vulnerability enrichment.
* 288 CNAs are issuing CVEs with CPEs.
* Adding CPEs to CVEs can be labor-intensive.
* MongoDB is a CNA.
* NVD is not a CNA or authorized data publisher.

REFERENCES
* CPE Dictionary
* NVD APIs
* CVE JSON schema
* CVE program GitHub public repo
* Google Sheet (for CPE database)
* MongoDB bug bounty program
* CVE disclosure process

ONE-SENTENCE TAKEAWAY
CNAs should self-enrich CVEs with CPEs for improved vulnerability management and customer experience.

RECOMMENDATIONS
* Include CPEs in CVEs to improve vulnerability management.
* Maintain a CPE database and update it with releases.
* Use the CPE dictionary to ensure consistency in naming.
* Understand the CPE structure for effective utilization.
* Spread awareness of CPE metadata among stakeholders.
* Encourage CNAs to include CPEs in their CVE submissions.
* Prioritize security by integrating CPEs widely.
* Provide complete CVEs from the beginning with CPEs.
* Manage the CPE enrichment process internally.
* Address potential gaps in CPE inclusion proactively.
* Automate CPE creation and addition to CVEs.
* Monitor NVD and industry trends for changes.
* Communicate CVE discrepancies clearly to customers.
* Use standardized identifiers for automation.
* Strive for accurate product identification with CPEs.
* Ensure consistent CPE versioning across systems.
