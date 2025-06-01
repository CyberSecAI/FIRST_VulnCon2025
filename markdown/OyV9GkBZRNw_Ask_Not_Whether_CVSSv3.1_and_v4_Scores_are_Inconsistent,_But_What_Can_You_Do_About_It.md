# Ask Not Whether CVSSv3.1 and v4 Scores are Inconsistent, But What Can You Do About It

**Video URL:** [https://www.youtube.com/watch?v=OyV9GkBZRNw](https://www.youtube.com/watch?v=OyV9GkBZRNw)
**Video ID:** OyV9GkBZRNw

---


**SUMMARY**
Muan and Chisan from VU Amsterdam discuss inconsistencies between CVSS V3.1 and V4 vulnerability ratings, proposing consistency rules and knowledge-based approaches to improve rating accuracy.

**IDEAS:**
* Human involvement in vulnerability rating processes introduces subjectivity, leading to discrepancies and inconsistencies across different versions of CVSS scoring systems.
* Insufficient information during vulnerability assessment can lead to varying interpretations and ratings, highlighting the need for comprehensive and standardized descriptions.
* Mapping vulnerabilities to severity levels can worsen inconsistencies, impacting vulnerability management and prioritization efforts due to differing interpretations.
* Sequence proximity of CVE IDs may lead to rating biases, where previous descriptions influence the assessment of subsequent vulnerabilities, causing inaccuracies.
* Disagreements on the necessity of user interaction in vulnerability exploitation demonstrate the subjective nature of vulnerability assessment and its impact.
* CVSS V4.0 aims to refine vulnerability scoring with more detailed guidance, prompting questions about consistency with previous versions like V3.1.
* Advanced LLMs like ChatGPT can generate CVSS metric vectors, but inconsistencies arise, particularly in attack vector, privileges required, and impact metrics.
* Inconsistencies in combined metric values across CVSS versions may stem from differing interpretations and evolving standards, affecting the accuracy of AI-driven ratings.
* Scope changes in CVSS V4, separating vulnerable system impact from subsequent system impact, introduce complexity in maintaining consistent vulnerability ratings.
* Consistency rules, rating both CVSS versions simultaneously, can save time and avoid inconsistencies, enabling quick identification and correction of discrepancies.
* One-to-one metric mappings between CVSS versions ensure consistent evaluation when definitions and values remain unchanged, simplifying vulnerability assessment processes.
* One-to-many metric mappings address complexities in user interaction and attack complexity, providing guidelines for consistent ratings across different CVSS versions.
* Many-to-many metric mappings handle scope property changes, separating vulnerable system impact from subsequent system impact, ensuring comprehensive vulnerability assessment.
* Applying consistency rules to public datasets reveals that most metrics remain consistent across CVSS versions, except for user interaction, which shows high inconsistency.
* Analyzing private datasets highlights inconsistencies even in straightforward metrics, emphasizing the need for continuous improvement in vulnerability assessment processes.
* Integrating hidden agreement rules with consistency rules can further detect inconsistencies, improving the accuracy and reliability of vulnerability ratings across organizations.
* Severity level shifts between CVSS versions raise questions about which version to trust for patching and prioritization, impacting vulnerability management strategies.
* The formula used to calculate CVSS V4 severity levels may need refinement to align with V3.1, reducing discrepancies and improving overall consistency.
* Timeframe differences in vulnerability rating can introduce inconsistencies, emphasizing the need for concurrent assessments to maintain accuracy and reliability.
* GitHub advisories offer a wealth of data for vulnerability analysis, providing opportunities to improve CVSS scoring and address inconsistencies across versions.
* Intel Seammens produces both CVSS V3.1 and V4 scores, offering potential data sources for analysis and improvement of vulnerability assessment processes.
* Applying consistency rules can help detect inconsistent entries, even when companies apply hidden agreement rules, improving the accuracy of vulnerability ratings.
* The removal of the scope property in V4 requires a separation into vulnerable system impact and subsequent system impact for accurate vulnerability assessment.
* Attack complexity in V3.1 does not reflect the significant difference between conditions, leading to changes in V4 to address this issue.
* The high value of attack complexity in V3.1 is split into attack complexity and attack requirements in V4 to provide more clarity.

**INSIGHTS:**
* Human subjectivity significantly impacts vulnerability scoring, necessitating standardized guidelines and tools to enhance consistency across different CVSS versions.
* Inconsistencies in vulnerability ratings can lead to flawed prioritization and management, emphasizing the need for robust consistency checks and validation processes.
* Evolving vulnerability scoring systems require continuous refinement and adaptation to address emerging threats and maintain accurate risk assessments.
* Consistency rules and knowledge-based approaches can mitigate discrepancies in vulnerability ratings, improving the reliability of security assessments and prioritization.
* Data analysis and collaborative efforts are essential for identifying and addressing inconsistencies in vulnerability scoring, enhancing overall cybersecurity practices.
* The shift from CVSS V3.1 to V4 introduces complexities that require careful consideration to ensure consistent and accurate vulnerability assessments.
* Leveraging diverse data sources, including GitHub advisories and industry reports, can improve the comprehensiveness and accuracy of vulnerability analysis.
* Addressing inconsistencies in user interaction ratings is crucial for enhancing the reliability of vulnerability assessments and prioritization efforts.
* The time frame in which vulnerabilities are rated can impact consistency, highlighting the need for concurrent assessments and standardized processes.
* Continuous improvement and refinement of vulnerability scoring formulas are essential for aligning different CVSS versions and reducing severity level shifts.
* Splitting attack complexity into attack complexity and attack requirements in V4 provides more clarity and addresses limitations in V3.1.
* The removal of the scope property in V4 requires a separation into vulnerable system impact and subsequent system impact for accurate vulnerability assessment.
* Integrating hidden agreement rules with consistency rules can further detect inconsistencies, improving the accuracy of vulnerability ratings across organizations.
* The high value of attack complexity in V3.1 is split into attack complexity and attack requirements in V4 to provide more clarity.
* Advanced LLMs like ChatGPT can generate CVSS metric vectors, but inconsistencies arise, particularly in attack vector, privileges required, and impact metrics.

**QUOTES:**
* "Inconsistency has been talked and researched and also in academic works we see like people working on missing information inconsistencies."
* "Scientifically we would like to see that what why what's the reason behind this kind of inconsistency."
* "If you assume that someone else could assume something else and we can see there isn't a real example."
* "If we map to severity level, it gets even worse. Something is critical, high or median."
* "CVSS v3.1 is still the premier scoring versions used by most organizations while V4 remains in its early adoption phase."
* "Proposing using consistency rules and rating both versions at the same time."
* "If you first read V3.1 and consider it is required, then you should consider V4 is passive or active."
* "By reviewing the first official documentation we defined three types of mapping relationship between V3.1 and V4 metrics."
* "If the definition of a metric and the metric value do not change between versions. So the evaluation should remain the same across versions."
* "The high value of AC in V3.1 do not reflect the significant difference between conditions currently compressed in the definition."
* "CV SSV4 is still in its early adoption phase. So due to limited data available, our NLS is based on what we collected."
* "Integrating them with our consistency rules can still help detect inconsistent um entries."
* "Which version should then trust it for patching or preoritization when both are available?"
* "Does the formula used to calculate V4 severity level still have room to improvement?"
* "We wish this is why we say that okay use this rule. If you you rate it okay."
* "There's a wealth of data. They're the largest data source that I've looked at both their reviewed."

**HABITS**
* Researchers analyze data from multiple sources, including public datasets and private company data, to identify inconsistencies.
* They develop and apply consistency rules to vulnerability ratings to improve accuracy and reduce discrepancies across different CVSS versions.
* Researchers continuously seek more data to support their studies and improve their consistency rules for vulnerability assessment.
* They collaborate with companies and industry experts to validate their findings and refine their methodologies for vulnerability analysis.
* Researchers review official documentation and technical specifications to define mapping relationships between different CVSS versions.
* They examine the impact of individual metrics on the overall vulnerability score to understand the factors contributing to inconsistencies.
* Researchers use advanced LLMs like ChatGPT to generate CVSS metric vectors and assess their consistency with human-generated ratings.
* They present their findings at conferences and publish their research to share knowledge and contribute to the improvement of vulnerability assessment practices.
* Researchers investigate the root causes of inconsistencies in vulnerability ratings to develop targeted solutions and mitigation strategies.
* They prioritize the development of practical tools and guidelines to help analysts and organizations improve the consistency of their vulnerability assessments.
* Researchers maintain open communication channels with data providers and industry partners to facilitate data sharing and collaborative research efforts.
* They regularly update their methodologies and tools to incorporate new data and address emerging challenges in vulnerability assessment.
* Researchers focus on actionable insights and practical recommendations to help organizations improve their vulnerability management and prioritization processes.
* They conduct thorough data analysis to identify patterns and trends in vulnerability ratings, informing the development of targeted interventions.
* Researchers actively seek feedback from users and stakeholders to improve the usability and effectiveness of their consistency rules and tools.

**FACTS:**
* CVSS V4.0 was released in November 2023, building upon previous versions with more refined and detailed guidance for vulnerability scoring.
* Red Hat had low vulnerabilities in 2022, while NVD showed inconsistencies, highlighting variations among different CNAs in vulnerability assessment.
* CVSS V3 is associated with lower scores, with a 20% difference between different CNAs, indicating inconsistencies in vulnerability rating practices.
* Human involvement in rating processes can cause errors and subjective understandings, leading to discrepancies in vulnerability assessments.
* A single sentence in a vulnerability description can lead to different interpretations, resulting in varying severity levels and prioritization outcomes.
* There have been five versions of CVSS, with each new version generally built upon the previous one, offering more refined guidance.
* Bond DB has started providing CVSS version 4 ratings alongside V3.1, but inconsistencies can arise when versions are rated at different times.
* The scope property in CVSS V3.1 has been removed in V4, separating into vulnerable system impact and subsequent system impact.
* Applying consistency rules to public datasets reveals that user interaction shows relatively high inconsistency across CVSS versions.
* Analyzing private datasets highlights inconsistencies even in straightforward metrics like AV and PR, emphasizing the need for continuous improvement.
* Even with hidden agreement rules, inconsistencies related to impact can persist, indicating the complexity of achieving consistent vulnerability ratings.
* GitHub advisories offer a wealth of data for vulnerability analysis, providing opportunities to improve CVSS scoring and address inconsistencies.
* Intel Seammens produces both CVSS V3.1 and V4 scores, offering potential data sources for analysis and improvement of vulnerability assessment processes.
* Attack complexity in V3.1 does not reflect the significant difference between conditions, leading to changes in V4 to address this issue.
* The high value of attack complexity in V3.1 is split into attack complexity and attack requirements in V4 to provide more clarity.

**REFERENCES:**
* CVSS V3.1
* CVSS V4.0
* NVD (National Vulnerability Database)
* CNA (CVE Numbering Authority)
* CVE (Common Vulnerabilities and Exposures)
* CVE ID sequence
* ChatGPT
* Bond DB
* cv.org
* GitHub advisories
* Intel Seammens
* VU Amsterdam
* Dutch Research Council NWO
* Vancheek research
* Red Hat
* CVSS V3
* CVSS V4
* Attack Vector (AV)
* Privileges Required (PR)
* User Interaction (UI)
* Attack Complexity (AC)
* Attack Requirements (AT)
* Scope
* CIA (Confidentiality, Integrity, Availability)
* Website
* LinkedIn

**ONE-SENTENCE TAKEAWAY**
Standardizing vulnerability rating through consistency rules and continuous data analysis is crucial for accurate risk assessment and effective cybersecurity practices.

**RECOMMENDATIONS:**
* Implement consistency rules to rate both CVSS versions simultaneously, ensuring that vulnerability assessments are consistent and discrepancies are quickly identified.
* Prioritize concurrent vulnerability assessments to minimize timeframe-related inconsistencies, ensuring that ratings reflect the most current understanding of the vulnerabilities.
* Refine the formula used to calculate CVSS V4 severity levels, aligning it with V3.1 to reduce discrepancies and improve overall consistency in scoring.
* Leverage diverse data sources, including GitHub advisories and industry reports, to enhance the comprehensiveness and accuracy of vulnerability analysis efforts.
* Focus on addressing inconsistencies in user interaction ratings, as this metric shows relatively high variability across CVSS versions, improving assessment reliability.
* Integrate hidden agreement rules with consistency rules to further detect inconsistencies, improving the accuracy and reliability of vulnerability ratings across organizations.
* Continuously seek more data to support vulnerability studies, improving consistency rules and enhancing the overall accuracy of vulnerability assessment processes.
* Collaborate with companies and industry experts to validate findings and refine methodologies, ensuring that vulnerability analysis practices are robust and effective.
* Develop practical tools and guidelines to help analysts and organizations improve the consistency of their vulnerability assessments, promoting standardized practices.
* Maintain open communication channels with data providers and industry partners to facilitate data sharing and collaborative research efforts, enhancing vulnerability analysis.
* Regularly update methodologies and tools to incorporate new data and address emerging challenges, ensuring that vulnerability assessment practices remain current.
* Prioritize actionable insights and practical recommendations to help organizations improve their vulnerability management and prioritization processes effectively.
* Conduct thorough data analysis to identify patterns and trends in vulnerability ratings, informing the development of targeted interventions and improvements.
* Actively seek feedback from users and stakeholders to improve the usability and effectiveness of consistency rules and tools for vulnerability assessment.
* Standardize vulnerability descriptions to minimize subjective interpretations, ensuring that assessments are based on comprehensive and consistent information.
