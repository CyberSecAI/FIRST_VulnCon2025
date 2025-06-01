# Modeling Asset Risk Using Grouped EPSS

**Video URL:** [https://www.youtube.com/watch?v=W2UMqkRyBOY](https://www.youtube.com/watch?v=W2UMqkRyBOY)
**Video ID:** W2UMqkRyBOY

---

SUMMARY
Security engineer discusses modeling asset risk using grouped EPSS, focusing on prioritizing vulnerabilities based on likelihood and impact.

IDEAS
* CVEs are increasing, outpacing organizational capacity to patch.
* Grouped EPSS calculates the probability of at least one CVE being exploited on an asset.
* This approach shifts focus from vulnerability land to asset land.
* It helps prioritize remediation efforts based on asset risk.
* The formula considers the cumulative probability of exploitation across all CVEs on an asset.
* It's easy to calculate using Python and Pandas.
* Visualizing grouped EPSS scores reveals areas for investigation.
* Combining grouped EPSS with data classification enhances risk assessment.
* This approach helps bridge the gap between likelihood and impact.
* It facilitates communication with stakeholders about risk reduction.
* Focusing on the riskiest assets optimizes resource allocation.
* This method helps align vulnerability management with business priorities.
* It provides a more nuanced view of risk than simply prioritizing individual CVEs.
* Grouped EPSS allows for continuous monitoring of asset risk posture.
* It enables data-driven decision-making in vulnerability management.
* This approach helps organizations make smarter decisions about remediation.
* It provides a clearer understanding of the overall security posture.
* Grouped EPSS can be used to measure the effectiveness of remediation efforts.
* This approach helps organizations prioritize vulnerabilities that move the needle the most.
* It provides a more comprehensive view of risk than traditional methods.
* Grouped EPSS can be used to identify assets that require additional attention.
* This approach helps organizations make more informed decisions about security.
* It provides a more proactive approach to vulnerability management.
* Grouped EPSS can be used to improve overall security posture.
* This approach helps organizations reduce their overall risk.
* It provides a more data-driven approach to security.
* Grouped EPSS can be used to communicate risk to stakeholders.
* This approach helps organizations make better decisions about security investments.
* It provides a more comprehensive approach to vulnerability management.

INSIGHTS
* Prioritizing asset risk over individual CVEs provides a more holistic view of organizational security.
* Grouped EPSS offers a practical way to quantify and communicate asset-level risk.
* Combining likelihood of exploitation with potential impact leads to more effective risk management.
* This approach empowers organizations to make data-driven decisions about remediation efforts.
* Continuous monitoring of grouped EPSS scores provides valuable insights into risk posture trends.
* This method helps align vulnerability management with business priorities and stakeholder concerns.
* Focusing on the riskiest assets optimizes resource allocation and maximizes risk reduction.
* Grouped EPSS facilitates more informed discussions about security investments and strategies.
* This approach promotes a more proactive and data-driven approach to vulnerability management.
* By understanding asset risk, organizations can better manage and mitigate their overall security posture.

QUOTES
* "Essentially, what we're doing is we have a pipeline of vulnerability data coming into our organization and it is not slowing down." - Speaker
* "As a vulnerability management program, how do we effectively measure and communicate risk and risk reduction if we aren't fixing everything?" - Speaker
* "It's the probability that at least one CVE in a group will be exploited." - Speaker
* "It's actually really easy to calculate." - Speaker
* "We're sort of framing this in asset land rather than vulnerability land." - Speaker
* "It gives us a good avenue of like determining what to look at." - Speaker
* "To me, that's risk, right? It's we're able to quantify likelihood at the asset level." - Speaker
* "It gives us information to further our decision-making process to understand what is going on in our environment." - Speaker
* "It's sort of measuring what your asset risk posture could be on a day-to-day basis." - Speaker
* "More information in vulnerability management means I can make better decisions." - Speaker
* "It's a decision support mechanism where we are looking at the things that are the most risky to the organization." - Speaker
* "This asset is 95% likely to have exploitation activity associated with it in the wild and it also processes our most sensitive information." - Speaker
* "None of what I just said substitutes for good patch management." - Speaker
* "It provides a lens into your vulnerability risk posture." - Speaker
* "It helps to prioritize by riskiest asset or other grouping." - Speaker
* "It indicates which assets or groups require additional effort that you may not have known about beforehand." - Speaker
* "There's a really interesting opportunity of being able to see in an environment how risk can change." - Audience Member

HABITS
* Researches and explores new security concepts in free time.
* Seeks to operationalize theoretical concepts for practical application.
* Analyzes vulnerability data on a daily basis to identify trends.
* Engages in discussions with asset owners to understand risk factors.
* Prioritizes tasks based on risk and potential impact to the organization.
* Uses data visualization to gain insights and identify areas for investigation.
* Continuously monitors asset risk posture to inform decision-making.
* Focuses on understanding the "why" behind security issues.
* Marries technical data with business context for a holistic view of risk.
* Advocates for good patch management as a foundational security practice.
* Uses data to support decision-making and communicate risk effectively.
* Seeks to improve security posture through continuous learning and improvement.
* Collaborates with stakeholders to align security efforts with business priorities.
* Uses Python and Pandas for data analysis and calculation.
* Shares knowledge and insights through presentations and blog posts.
* Encourages others to explore their data and make data-driven decisions.
* Actively participates in security communities and special interest groups.
* Seeks to understand the root causes of vulnerabilities and exploits.
* Uses data to measure the effectiveness of remediation efforts.
* Prioritizes vulnerabilities that have the greatest impact on risk reduction.
* Focuses on making smarter decisions based on data and insights.

FACTS
* CVE numbers have been increasing over the past 25 years.
* The industry averages about 10% vulnerability backlog closure month over month.
* EPSS provides a measure of the probability of exploitation in the wild.
* Grouped EPSS can be applied to assets, network segments, or other groupings.
* The independence of vulnerability exploitation events is a key assumption in the formula.
* Grouped EPSS scores can range from 0 to 1.
* Data classification standards can be used to enrich risk assessment.
* Risk is a function of impact and likelihood.
* Asset inventory is crucial for effective risk management.
* External factors like CVE arrival rate and EPSS score shifts influence risk posture.
* Remediation efforts can shift the distribution of grouped EPSS scores.
* Grouped EPSS can be used to measure the effectiveness of remediation actions.
* Tolerance thresholds can be set at the CVE, EPSS, or asset level.
* Grouped EPSS provides a window into the reality of an organization's risk posture.
* Vulnerability management programs can use grouped EPSS to align with CISO priorities.
* Grouped EPSS can help identify assets requiring additional effort.

REFERENCES
* Blog post on grouped EPSS
* EPSS special interest group
* First.org user guide on scaling EPSS
* Scientia and Kenna prioritization of prediction volume 3
* Python
* Pandas library
* CSV files
* Data frames
* Lambda functions
* Data classification standards
* Asset inventory data
* Risk scoring products

ONE-SENTENCE TAKEAWAY
Grouped EPSS helps prioritize vulnerability remediation by quantifying asset risk based on likelihood and impact.

RECOMMENDATIONS
* Calculate grouped EPSS scores for your assets to understand their overall risk.
* Visualize the distribution of scores to identify areas needing investigation.
* Incorporate data classification to enrich your risk assessment process.
* Prioritize remediation efforts based on the riskiest assets.
* Use grouped EPSS to communicate risk effectively to stakeholders.
* Monitor grouped EPSS scores over time to track risk posture trends.
* Use this approach to align vulnerability management with business priorities.
* Focus on understanding the root causes of high-risk assets.
* Use grouped EPSS to measure the effectiveness of your remediation efforts.
* Set tolerance thresholds for grouped EPSS scores at different levels.
* Consider the potential impact of compromise when assessing risk.
* Investigate the business purposes of high-risk assets.
* Explore how removing specific CVEs impacts overall asset risk.
* Use grouped EPSS as a decision support mechanism for vulnerability management.
* Share your findings and insights with your team and stakeholders.
* Continuously learn and improve your approach to vulnerability management.
* Engage with the security community to share and learn best practices.
* Consider the independence of vulnerabilities when applying the formula.
* Use Python and Pandas to automate the calculation of grouped EPSS.
* Explore different groupings beyond assets, such as network segments.
* Use this approach to make more informed decisions about security investments.
