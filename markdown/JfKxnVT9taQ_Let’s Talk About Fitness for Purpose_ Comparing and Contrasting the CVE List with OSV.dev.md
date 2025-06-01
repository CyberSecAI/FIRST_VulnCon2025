# Let’s Talk About Fitness for Purpose_ Comparing and Contrasting the CVE List with OSV.dev

**Video URL:** [https://www.youtube.com/watch?v=JfKxnVT9taQ](https://www.youtube.com/watch?v=JfKxnVT9taQ)
**Video ID:** JfKxnVT9taQ

---

SUMMARY
Andrew discusses the challenges of vulnerability metadata quality in the CVE program and contrasts it with OSV.

IDEAS
* Vulnerability metadata helps defenders know they are impacted and how to fix the problem.
* The CVE program's mission statement has remained unchanged for 25 years.
* The lack of an explicit "why" in the CVE mission statement is problematic.
* OSV's mission is more clearly focused on risk reduction for open source.
* The CVE list has grown significantly over 25 years, creating scaling challenges.
* OSV has more vulnerabilities than CVE, but with a narrower scope.
* The increasing number of vulnerabilities is difficult for everyone involved.
* Automation is necessary to manage vulnerabilities at scale effectively.
* Inconsistent use of CVE record format undermines machine readability.
* Remediation at scale requires accurate and automated detection.
* The CVE program federated to scale, but consistency suffers.
* It's difficult to fix inconsistencies retrospectively while still federating.
* The growing number of CNAs makes it hard to maintain per-CNA heuristics.
* The CISA secure by design pledge is a good start but entirely voluntary.
* The ERL provides positive reinforcement but may lack motivating factors.
* OSV capitalized on its youth and existing data quality.
* OSV defines minimum properties for high-quality records.
* A precise record has correctly ordered versions and verifiable references.
* Misaligned incentives contribute to tension in CVE data quality.
* CNAs are incentivized to focus on human-readable descriptions.
* Customers need automation-friendly data to manage vulnerabilities.
* Open source CNAs often operate similarly to vendor CNAs.
* Bug bounty providers operate at arm's length from other parties.
* Researcher CNAs face similar challenges as bug bounty providers.
* There's no programmatic way to validate CNA scope.
* Vendor CNA growth may lead to a decline in bug bounty/researcher CNAs.
* Clarify the CVE program's mission statement for the modern era.
* Set a target standard for CVE record capability and enforce it.
* Hold new CNAs to a higher standard from the outset.
* Bring existing CNAs up to the new standard incrementally.
* Focus on the top 15 CNAs initially for the biggest impact.
* Use a use case-based approach to ensure CVE usefulness.
* Strong leadership is needed to drive these changes.
* SISA has leverage to influence change through funding conditions.
* Downstream consumers can demand higher quality CVE data.

INSIGHTS
* The purpose of vulnerability metadata is to enable effective remediation.
* The CVE program needs to adapt its mission to the current scale of vulnerabilities.
* Automation and consistency are key for effective vulnerability management at scale.
* Misaligned incentives hinder the creation of high-quality CVE records.
* Different CNA types face unique challenges in providing complete data.
* A multi-faceted approach is needed to improve CVE data quality.
* Strong leadership, stakeholder collaboration, and consumer pressure are crucial.
* The focus should shift from CNA growth to data quality and usability.
* Voluntary pledges and positive reinforcement alone are insufficient.
* Clear standards, enforcement, and use case-driven development are essential.

QUOTES
* "Just because it can doesn't mean it is." - Andrew
* "The only thing worse than tantalizingly machine readable data is when it's inconsistently used." - Andrew
* "There is no remediation at scale without first detection at scale." - Andrew
* "What got you here won't get you there." - Andrew
* "It's just a matter of getting the CNAs to do it right." - Andrew

HABITS
* Andrew gets up early for working group meetings.
* Andrew actively engages with the QWG.
* Andrew thinks about the "why" behind activities.
* Andrew evaluates if activities are on mission.
* Andrew uses mission statements to guide actions.
* Andrew analyzes data and identifies trends.
* Andrew writes code and contributes to open source projects.
* Andrew attends conferences and engages in discussions.
* Andrew uses visualizations to communicate data.
* Andrew advocates for higher standards in data quality.

FACTS
* The CVE program's mission has been unchanged for 25 years.
* In 1999, the CVE list had about 1500 vulnerabilities.
* In 2024, the CVE list had over 37,000 vulnerabilities.
* OSV has over 82,000 vulnerabilities.
* There are over 447 CNAs as of the end of 2024.
* OSV has 22 home databases.
* 15% of CVEs in 2024 had no usable data in the affected field.
* The CISA secure by design pledge covers 16% of the 2024 CVE list.
* Bug bounty providers contributed to about 80% of CVEs in 2024.
* Vendor CNAs contributed the largest share of CVEs in 2024.

REFERENCES
* OpenSSF
* BonCon
* OSV
* osc.dev blog
* CVE
* NVD
* CPE dictionary
* CVE JSON 5 schema
* CISA secure by design pledge
* ERL (Enrichment Recognition List)
* Chromium
* Linux kernel
* GitHub advisory database
* OSV schema JSON schema syntax spec
* CVE lint

ONE-SENTENCE TAKEAWAY
Demand high-quality, actionable vulnerability data for effective remediation at scale.

RECOMMENDATIONS
* Clarify the CVE program's mission and focus on automation.
* Set and enforce standards for CVE record completeness and accuracy.
* Prioritize bringing top CNAs up to the new standards.
* Encourage vendors to prioritize high-quality CVE data.
* Include vulnerability management track records in purchasing decisions.
* Vulnerability researchers should ensure complete CVE information.
* Use bug bounties to incentivize best practices and data disclosure.
* Develop tools for automated validation and linting of CVE records.
* Foster competition among vendors on vulnerability management quality.
* Promote a shift from focusing on CVE counts to data quality.
