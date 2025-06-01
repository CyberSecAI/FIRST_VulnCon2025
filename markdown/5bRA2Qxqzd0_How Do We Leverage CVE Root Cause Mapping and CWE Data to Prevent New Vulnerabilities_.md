# How Do We Leverage CVE Root Cause Mapping and CWE Data to Prevent New Vulnerabilities_

**Video URL:** [https://www.youtube.com/watch?v=5bRA2Qxqzd0](https://www.youtube.com/watch?v=5bRA2Qxqzd0)
**Video ID:** 5bRA2Qxqzd0

---

SUMMARY
Jeremy and Alex discuss using CWE data to improve product security by mapping vulnerabilities to root causes and tailoring communication.

IDEAS
* CVE volume increases due to carrying underlying weaknesses for extended periods.
* CWE data can be used to improve products by identifying common weaknesses.
* Prioritize information overload for software developers by filtering noise.
* Vulnerability remediation is expensive for customers due to patching time.
* Threat intelligence uses multiple data sources to identify risky components.
* Threat models, static analysis, and root cause mapping can inform CWE IDs.
* CWE taxonomy provides commonality across the vulnerability landscape.
* Blend data from threat models, root cause mapping, and use same identifiers.
* Tailor CWE data granularity based on audience (managers vs. engineers).
* Actionable insights for engineers require specific, lower-level CWE data.
* Higher-level CWEs are suitable for high-level reports and product managers.
* CWE tiering maintains consistency even when discussing at different levels.
* Standardizing language ensures clear communication and avoids misinterpretations.
* Prioritize components based on vulnerability data to focus engineering efforts.
* Provide information to engineering in smaller chunks for manageable tasks.
* Remember upstream contributors when making changes to open-source components.
* Integrate CWE metrics into development pipelines for proactive security.
* Implement guardrails and security practices to minimize underlying weaknesses.
* Training can influence coding practices and reduce vulnerabilities.
* Collecting and structuring data is crucial for presenting it effectively.
* Selling the value of CWE data to developers can free up their bandwidth.
* Provide recommendations based on CWE data, not just reports.
* Predictive use of CWE data is a potential area for future exploration.
* Track CVE labels, CVSS scores, and CWE levels in defect tracking systems.
* High-level CWE data is useful for communicating with executives.
* Champion efforts to adopt safer languages like Rust to eliminate weaknesses.
* Annual top 10 weakness reports can raise awareness and drive action.
* Focus on the presence of weaknesses in the top 10, not their specific rank.
* "Big Bang Day" allows engineers to fix known weaknesses in existing code.
* Fixing weaknesses before they become vulnerabilities is an uphill battle.
* Leverage CWE data from vulnerabilities to prioritize SAS output.

INSIGHTS
* Proactive weakness remediation reduces long-term CVE volume and costs.
* CWE data enables targeted improvements in product security and development.
* Effective communication of CWE data requires tailoring to the audience.
* Integrating CWE data into workflows fosters a proactive security culture.
* Collaboration with upstream contributors is essential for open-source security.
* Threat intelligence combined with CWE data enhances risk prioritization.
* Focusing on high-impact components maximizes engineering efforts.
* Training and guardrails complement code changes for comprehensive security.
* Data-driven prioritization and recommendations are key for CWE effectiveness.
* Addressing weaknesses before exploitation is crucial but challenging.

QUOTES
* "CVEes represent mistakes in design, in my opinion." - Jeremy
* "Vulnerability remediation is expensive." - Jeremy
* "We're always finding ourselves fixing CVEes. It's not really scalable." - Jeremy
* "Dasty is not necessarily a source of weakness." - Jeremy
* "Sometimes we're just collecting data for the sake of collecting data." - Jeremy
* "Is the software secure?" - Jeremy
* "Weaknesses are not an unknown thing." - Jeremy
* "We've got a great taxonomy out there." - Jeremy
* "You have a choice of granularity." - Alex
* "Memory buffer errors on its own isn't necessarily something that's specific enough." - Alex
* "This is where it becomes more actionable at a lower level." - Alex
* "The standardizing common language." - Alex
* "You really need to tailor the results to the audience." - Jeremy
* "Remember your upstream contributors." - Jeremy
* "Integrate those metrics into your development pipelines." - Jeremy
* "It's not just limited to just fixing code." - Jeremy
* "How do you leverage CWE data to address root cause?" - Audience Member
* "The code was working before you screwed around with it." - Jim Duncan
* "It's a weakness, not a vulnerability." - Jim Duncan
* "I wish I'd thought of that." - Jim Duncan
* "It doesn't matter. What matters is that the weaknesses showed up in that list." - Jim Duncan
* "I don't want you reporting any more stuff." - Audience Member

HABITS
* Google and talk to peers to find solutions and best practices.
* Present data in smaller chunks to engineering teams for better focus.
* Integrate security checks into development pipelines for proactive remediation.
* Implement guardrails and security practices beyond just code changes.
* Conduct mandatory secure coding training aligned with job function.
* Flag completed training in internal records for tracking and compliance.
* Champion security champions and reward strong performance in training.
* Exploit opportunities like "Big Bang Day" to fix lingering weaknesses.
* Tailor communication of CWE data to different audiences (executives, engineers).
* Work with upstream contributors to address weaknesses in open-source components.

FACTS
* The volume of CVEs continues to increase year over year.
* New software hits the market every day.
* Underlying weaknesses contribute to CVE volume.
* There is increasing interest in threat intelligence.
* Threat intelligence uses data from multiple sources.
* Vulnerability remediation is expensive for customers.
* CWE has a tiered structure for varying levels of detail.
* Higher-level CWEs map to lower-level CWEs.
* Standardizing language improves communication.
* Developers are under a lot of stress.
* Some weaknesses are due to specific memory management practices.
* Rust can eliminate entire categories of weaknesses.
* Many defect reports are automated and routine.
* It's an uphill battle to convince people to fix weaknesses.

REFERENCES
* Red Hat
* Dasty
* CWE (Common Weakness Enumeration)
* CVE (Common Vulnerabilities and Exposures)
* CVSS (Common Vulnerability Scoring System)
* SAS (Static Application Security Testing)
* WebKit GTK
* Rust
* Junos
* Koala Lumpur First Conference
* Juniper Secure Development Life Cycle
* Big Bang Day

ONE-SENTENCE TAKEAWAY
Use CWE data to prioritize, communicate, and remediate weaknesses proactively, reducing vulnerabilities.

RECOMMENDATIONS
* Tailor CWE data granularity to the specific audience for better understanding.
* Integrate CWE metrics into development pipelines for early detection and prevention.
* Implement guardrails and security practices in addition to code changes.
* Prioritize components based on vulnerability data to focus engineering efforts.
* Collaborate with upstream contributors to fix weaknesses in open source.
* Use threat intelligence and CWE data to identify and prioritize risky components.
* Conduct regular secure coding training and track completion internally.
* Create an annual top 10 weakness report to raise awareness and drive action.
* Encourage developers to fix weaknesses proactively, even before exploitation.
* Leverage CWE data from vulnerabilities to prioritize SAS findings.
* Provide actionable recommendations based on CWE data, not just reports.
* Explore the predictive use of CWE data for proactive vulnerability management.
* Track CVE labels, CVSS scores, and CWE levels in defect tracking systems.
* Champion the adoption of memory-safe languages like Rust to eliminate weaknesses.
* Create opportunities like "Big Bang Day" for focused weakness remediation.
