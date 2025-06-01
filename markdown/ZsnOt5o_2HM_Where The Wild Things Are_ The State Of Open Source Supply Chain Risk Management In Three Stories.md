# Where The Wild Things Are_ The State Of Open Source Supply Chain Risk Management In Three Stories

**Video URL:** [https://www.youtube.com/watch?v=ZsnOt5o_2HM](https://www.youtube.com/watch?v=ZsnOt5o_2HM)
**Video ID:** ZsnOt5o_2HM

---

SUMMARY
Maui discusses supply chain security, focusing on proactive vulnerability detection and mitigation strategies.

IDEAS
* Open-source software dependencies introduce transitive risk, creating backdoors for vulnerabilities.
* Software Composition Analysis (SCA) tools are reactive, detecting bugs long after introduction.
* Proactive vulnerability scanning in supply chains can provide years of lead time.
* Static analysis tools struggle with false positives, hindering scalability in dependency analysis.
* Intelligent Code Repair (ICR) enables scalable, accurate bug detection in dependencies.
* Collaborating with maintainers for bug fixes ensures higher adoption rates and faster remediation.
* The "six Fs" framework (fix, flip, forge, fork, forget, forego) guides mitigation strategies.
* Prioritizing high-severity bugs and risky artifacts streamlines remediation efforts.
* Actionable advice and patches facilitate efficient vulnerability mitigation in dependencies.
* Proactive assessment of open-source packages before ingestion enhances security.
* Human factors, such as project activity and bug-fixing capabilities, inform risk assessment.
* Visualizing historical vulnerability trends reveals a project's security posture.
* Reachability analysis determines if vulnerabilities actually impact downstream applications.
* VEX documents reduce noise and toil in vulnerability management, but are hard to generate.
* Automating VEX document generation within 72 hours of CVE release provides timely intel.
* Integrating with maintainers and using GitHub actions streamlines VEX document creation.
* Prioritizing data over dashboards empowers users to integrate insights into their workflows.
* Compassionate bug reporting and contributing to upstream projects strengthens the community.
* Investing in proactive security measures reduces long-term toil and costs.
* Manual reachability analysis doesn't scale; automated tools provide faster, more accurate results.
* Open-source maintainers often lack resources for comprehensive VEX document generation.
* Proactive vulnerability scanning and mitigation are crucial for robust supply chain security.
* The project "Clean Beach" provides a data feed for known and unknown vulnerabilities.
* The project "Clean Beach" focuses on the specific dependencies of a given project.
* The project "Clean Beach" also considers risks stemming from human factors.
* The project "Clean Beach" provides better incident response and fewer shipped bugs.
* The project "Clean Beach" offers code provenance information for better dependency management.

INSIGHTS
* Proactive security, through early bug detection and collaboration, minimizes long-term risks.
* Shifting from reactive to proactive vulnerability management significantly reduces toil and costs.
* Human factors and historical trends provide valuable context for open-source risk assessment.
* Automating VEX document generation is crucial for timely and scalable vulnerability mitigation.
* Prioritizing data and actionable insights empowers users to manage risk effectively.
* Supporting open-source maintainers is essential for a healthy and secure software ecosystem.
* Open-source software, like public beaches, requires collective responsibility for maintenance.
* Effective supply chain security requires a combination of automated tools and human collaboration.
* The "six Fs" framework provides a practical guide for prioritizing and addressing vulnerabilities.
* Reachability analysis clarifies the actual impact of vulnerabilities on downstream applications.

QUOTES
* "Most of our software isn't ours; we build on tons of open-source code." - Maui
* "The actual bug might have happened a long time ago." - Maui
* "What if we have an approach where we proactively look for vulnerabilities?" - Maui
* "As an industry, we struggle looking for bugs in our proprietary code." - Maui
* "The reporting is done from an actual human handle." - Maui
* "We are also working with the maintainers very closely in order to fix the problem." - Maui
* "We found two times more risky artifacts, stuff that you need to look into." - Maui
* "There's already a solution available, and so you can just move to that." - Maui
* "Having a tugboat go and try to find any amount of garbage from there is not going to be possible." - Maui
* "Open-source software, just like your public beaches. It's messy." - Maui
* "We provide you information about known bugs as well as risk that is coming from human factors." - Maui
* "We uniquely provide is the risk that is coming from previously undetected bugs." - Maui
* "We need more data and not more dashboards." - Maui
* "Bug fixing security. This is a very human activity." - Maui
* "Be compassionate about this bug reporting thing." - Maui
* "All of those upstream software that you're using, they don't come for free." - Maui

HABITS
* Maui uses AI tools to generate images for presentations and understanding concepts.
* Maui collaborates closely with open-source maintainers to fix identified bugs.
* Maui prioritizes reporting bugs from a human handle for better communication.
* Maui provides patches and actionable advice alongside vulnerability reports.
* Maui analyzes software dependencies to identify unused or risky artifacts.
* Maui uses the "six Fs" framework to categorize and prioritize mitigation actions.
* Maui conducts reachability analysis to determine the actual impact of vulnerabilities.
* Maui aims to generate VEX documents within 72 hours of CVE release.
* Maui prioritizes providing data and actionable intel over dashboards.
* Maui encourages compassionate bug reporting and contributing to upstream projects.

FACTS
* 74% of codebases contain high-risk open-source vulnerabilities.
* Heartbleed vulnerability was present in code for two years before discovery.
* Log4Shell vulnerability existed in source code for eight years before discovery.
* Windows PrintNightmare vulnerability was present in code for 24 years.
* Top 2000 Python projects have about 14,000 dependencies.
* 350 bugs, including 150 security bugs, were found in top 2000 Python projects.
* 65% of reported bugs in the study have been fixed.
* The Pacific garbage patch is one-fifth the size of the United States.
* Apache Airflow has 719 dependencies.
* 97% of SCA reports can be eliminated with proper VEX documents.
* Apache Solar has 522 dependencies and an estimated 300 CVEs.
* Generating VEX documents for Apache Solar manually would take 0.9 person-years.

REFERENCES
* Sora, Gemini (AI image generation tools)
* Coarity (bug detection company)
* Alpha Omega (funding organization)
* PyPI (Python Package Index)
* GitHub
* Trellis (security research company)
* Vincent Dan's presentation on VEX
* Michael Windsor (Alpha Omega)
* Yar Patuk (Apache Airflow)
* OpenSSF
* Anaconda
* Red Hat
* Kubernetes
* CodeQL, Semgrep, Snyk, SonarCloud (static analysis tools)
* ICR (Intelligent Code Repair)
* Apache Kafka
* Log4j
* Jackson Databind
* SnakeYAML
* Jenkins
* Dependabot
* Apache Solar
* CVE (Common Vulnerabilities and Exposures)
* VEX (Vulnerability Exploitability eXchange)
* SCA (Software Composition Analysis)
* SBOM (Software Bill of Materials)
* CWE (Common Weakness Enumeration)

ONE-SENTENCE TAKEAWAY
Proactively find and fix open-source vulnerabilities through collaboration and automated VEX documents.

RECOMMENDATIONS
* Proactively scan open-source dependencies for vulnerabilities to mitigate risks early.
* Collaborate with maintainers to fix bugs and improve open-source software security.
* Prioritize high-severity vulnerabilities and risky artifacts for efficient remediation.
* Use the "six Fs" framework to guide vulnerability mitigation strategies.
* Generate VEX documents to reduce noise and toil in vulnerability management.
* Automate VEX document generation for timely and scalable vulnerability response.
* Integrate VEX document generation into development workflows using GitHub actions.
* Prioritize data and actionable insights over dashboards for effective risk management.
* Contribute to upstream open-source projects to improve the overall software ecosystem.
* Be compassionate when reporting bugs and work with maintainers to find solutions.
