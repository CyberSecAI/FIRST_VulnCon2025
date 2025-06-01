# When it Comes to Managing Risk, Context is King

**Video URL:** [https://www.youtube.com/watch?v=Hwyv9WHVyjg](https://www.youtube.com/watch?v=Hwyv9WHVyjg)
**Video ID:** Hwyv9WHVyjg

---

SUMMARY
Lucas Maidar from Tenable Research discusses vulnerability management, focusing on risk assessment and prioritization beyond CVSS.

IDEAS
* Vulnerability management requires managing risk, not just patching vulnerabilities.
* CVSS scores don't accurately reflect real-world risk and can be misleading.
* Focusing on known exploited vulnerabilities is more effective than chasing CVSS scores.
* EPSS provides a better measure of exploitation likelihood but has limitations.
* Contextual prioritization is crucial for effective vulnerability management.
* Consider scope, ease of exploitation, remediation, and proof of concept availability.
* Prioritize externally facing and remotely exploitable vulnerabilities.
* Develop a defensible strategy with clear SLAs and planned responses.
* Automate patching for low-risk software and prioritize known exploits.
* Build trust with stakeholders by making informed decisions, not panicking.
* Track remediation efforts by focusing on specific vulnerability categories.
* Use compensating controls and asset tagging to refine risk assessments.
* Prioritize confirmed vulnerabilities aggressively and triage potential ones.
* Weigh the cost of downtime against the risk of exploitation.
* Obtain buy-in from stakeholders for prioritization decisions.
* Focus on vulnerabilities known to be exploited, not just high CVSS scores.
* Consider the scope and impact of a vulnerability, not just its severity.
* Evaluate the ease of exploitation and remediation when assessing risk.
* Monitor for proof of concept code and exploitation in the wild.
* Don't panic about every new vulnerability; focus on real threats.
* Use data and context to make informed decisions about remediation.
* Develop a playbook for responding to emerging risk vulnerabilities.
* Consider the popularity and deployment of affected software.
* Prioritize vulnerabilities in internet-facing and trusted services.
* Don't load untrusted files and be cautious of social engineering.
* Be aware of zero-day exploits and their potential impact.
* Focus on persistently exploited vulnerabilities and recently exploited ones.
* Track remediation progress and report on risk reduction.
* Use tagging and tracking to manage vulnerabilities effectively.
* Consider the reputational impact of vulnerabilities in addition to technical risks.
* Focus on users with broad access, not just privileged devices.
* Automate temporal and environmental calculations for efficient risk assessment.
* Balance the need for patching with the cost of downtime.

INSIGHTS
* True vulnerability management involves understanding and mitigating real-world risks.
* Relying solely on CVSS or EPSS for prioritization can lead to misallocation of resources.
* Context, including exploit availability and asset importance, is crucial for accurate risk assessment.
* A defensible vulnerability management strategy requires data-driven decisions and clear communication.
* Building trust with stakeholders is essential for effective remediation efforts.
* Automation and tagging can significantly improve the efficiency of vulnerability management.
* Balancing the cost of downtime with the risk of exploitation is a key challenge.
* Focusing on known exploited vulnerabilities is a practical and effective approach.
* Considering the human element, such as social engineering, is crucial for comprehensive security.
* Continuous monitoring and adaptation are essential in the ever-evolving threat landscape.

QUOTES
* "The only way to guarantee security of a system in the face of a truly motivated attacker, bury it in a bunker, cut it off from the internet, and you're in good shape." - Professor in college
* "The reality is everything we do is managing risk." - Lucas Maidar
* "CVSS...was never intended to measure risk." - Lucas Maidar
* "A vulnerability that's never exploited, it's a potential risk." - Lucas Maidar
* "Developing reliable exploits, even with AI, even with all the tooling out there, it's still hard." - Lucas Maidar
* "EPSS is to show the likelihood of vulnerability being exploited in the next 28 days." - Lucas Maidar
* "Numbers alone can't kind of give us a day." - Lucas Maidar
* "Your vulnerability management program, number one thing is it has to be defensible." - Lucas Maidar
* "Remediating high and critical vulnerabilities does not guarantee you're reducing risk." - Lucas Maidar
* "Context is really useful to help explain why that number is bad." - Lucas Maidar
* "Attackers are racing the us. If we patch it before they get to it, then it's useless." - Lucas Maidar
* "The context is what helps you do that." - Lucas Maidar
* "Trust is really important in our industry." - Lucas Maidar
* "I think compensating controls are a useful mechanism." - Wulcom from Picos Security
* "The environmental parameters are underutilized." - Wulcom from Picos Security

HABITS
* Plan for known patching events like Patch Tuesday and Oracle CPU.
* Automate patching for low-risk software like browsers.
* Implement aggressive SLAs for known exploited vulnerabilities (e.g., 7 days).
* Develop a playbook for responding to emerging vulnerabilities.
* Continuously monitor for proof of concept code and active exploitation.
* Track and report on remediation progress for specific vulnerability categories.
* Tag assets based on risk factors and compensating controls.
* Triage potential vulnerabilities based on real-world risk.
* Communicate clearly with stakeholders about prioritization decisions.
* Avoid panicking about every new vulnerability; focus on real threats.

FACTS
* Over 285,000 CVEs have been published through the CVE program.
* Over 50% of published CVEs are high or critical severity.
* Most organizations have about 500 high/critical vulnerabilities on average.
* PCI requires remediation of medium vulnerabilities (CVSS 4+) within three months.
* Less than 1% of 2024 CVEs have known active exploitation.
* 80% of CVEs with EPSS > 0.9 have no known exploitation.
* 50% of CVEs with known exploitation have EPSS < 0.1.
* 72,000 CVEs have proof of concept code and EPSS < 0.2.
* CISA tracks about 1300 CVEs with known exploitation.
* Tenable tracks about 1549 CVEs with known exploitation.
* Tenable tracks 381 CVEs associated with ransomware.

REFERENCES
* CVSS (Common Vulnerability Scoring System)
* EPSS (Exploit Prediction Scoring System)
* CVE (Common Vulnerabilities and Exposures)
* PCI (Payment Card Industry)
* CISA (Cybersecurity and Infrastructure Security Agency)
* Tenable
* Nessus
* Log4Shell
* Heartbleed
* Mousejack
* CUPS vulnerability
* Ivanti Secure Connect vulnerability
* Apache Parquet vulnerability

ONE-SENTENCE TAKEAWAY
Prioritize patching known exploited vulnerabilities and use context for effective risk management.

RECOMMENDATIONS
* Focus on patching vulnerabilities with known exploits, not just high CVSS.
* Use EPSS to assess exploitation likelihood, but consider its limitations.
* Incorporate contextual factors like asset importance and exploit availability.
* Develop a defensible vulnerability management strategy with clear SLAs.
* Automate patching for low-risk software and prioritize known exploits.
* Track remediation efforts and report on risk reduction, not just CVSS scores.
* Use compensating controls and asset tagging to refine risk assessments.
* Prioritize confirmed vulnerabilities aggressively and triage potential ones.
* Communicate clearly with stakeholders and build trust through informed decisions.
* Don't panic about every new vulnerability; focus on real-world threats.
* Continuously monitor for proof of concept code and active exploitation.
* Consider the scope and impact of vulnerabilities, not just their severity.
* Evaluate the ease of exploitation and remediation when assessing risk.
* Use CISA's Known Exploited Vulnerabilities Catalog as a valuable resource.
* Leverage Tenable's capabilities for risk-based vulnerability management.
* Balance the need for patching with the cost of downtime and business impact.
