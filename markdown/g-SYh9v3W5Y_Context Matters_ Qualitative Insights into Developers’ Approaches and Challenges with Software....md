# Context Matters_ Qualitative Insights into Developers’ Approaches and Challenges with Software...

**Video URL:** [https://www.youtube.com/watch?v=g-SYh9v3W5Y](https://www.youtube.com/watch?v=g-SYh9v3W5Y)
**Video ID:** g-SYh9v3W5Y

---

SUMMARY
Elizabeth, a PhD student at NC State, discusses software composition analysis (SCA) tools, user challenges, and potential improvements.

IDEAS
* SCA tools focus on external libraries and imported code, identifying risks and vulnerabilities.
* The Log4Shell incident highlighted the importance of SCA tools in dependency analysis.
* An ideal SCA tool should deploy smoothly, identify components and vulnerabilities correctly.
* Overwhelming alerts, unclear vulnerability information, and complex dependency paths confuse users.
* Multiple ecosystems and legacy languages pose integration challenges for SCA tools.
* Integrating SCA scans into CI pipelines can cause pauses and stops due to noisy alerts.
* Determining the impact and exploitability of vulnerabilities requires additional context.
* Updating vulnerable libraries can break software, requiring custom fixes or patches.
* Sometimes, vulnerabilities are not fixed due to lack of impact, business risk, or alternatives.
* Small organizations struggle with limited resources, while large ones build custom tooling.
* SCA tools need more context, including static function reachability and infrastructure details.
* Combining SCA with static analysis and infrastructure context improves prioritization.
* SCA tools should learn from user input to improve accuracy and reduce noise.
* Choosing the right SCA tool depends on the application, team workflows, and deployment styles.
* Effective communication between teams and customers is crucial for fixing vulnerabilities.
* SCA tools should provide more context for accurate risk assessment and efficient remediation.
* Different deployment styles have trade-offs, and communication across parties can be challenging.
* SCA tools should analyze interactions between binaries for a comprehensive ecosystem view.
* SCA vendors have shown interest in the research but haven't provided extensive feedback yet.
* Users should consider application compatibility and team workflows when selecting SCA tools.
* Maintaining custom scripts for integrating multiple SCA tools can be costly.
* Prioritizing vulnerabilities based on CVSS scores, effort, and impact is common.
* Mitigating vulnerabilities involves isolating components or removing network access.
* SCA tools sometimes struggle with binaries due to fingerprinting and hashing issues.
* SCA tools can be used for mergers and acquisitions, identifying a company's software stack.
* Export control regulations can be addressed using SCA tools to analyze software components.
* SCA tools can help determine if software components comply with export restrictions.
* Integrating SCA tools requires understanding trade-offs and setting developer expectations.
* Communicating SCA results across teams requires considering different workflows and tools.
* SCA tools can be used to identify vulnerabilities in acquired binaries from suppliers.
* SCA tools can help determine if vulnerabilities are reachable and exploitable in an application.
* SCA tools can help prioritize vulnerabilities based on their potential impact and exploitability.

INSIGHTS
* Context is crucial throughout the SCA process for accurate vulnerability assessment and remediation.
* SCA tools need to provide more specific, actionable information beyond generic CVE data.
* Integrating SCA tools requires careful consideration of deployment methods and potential trade-offs.
* Collaboration and communication are essential for effective SCA implementation in organizations.
* SCA tools should evolve to consider the broader application context and infrastructure.
* User feedback loops can help improve SCA tool accuracy and effectiveness over time.
* Choosing the right SCA tool and integration strategy depends on organizational context.
* SCA tools should analyze interactions between software components for a holistic view.
* SCA tools should provide actionable remediation advice that considers the application context.
* SCA tools should support a wider range of languages and ecosystems for broader applicability.

QUOTES
* "Binaries, because they use fingerprinting or hashing, so if you change a single line of code or a single variable, the entire output could be different." - Elizabeth
* "Interpreting how a vulnerability impacts the application can be a challenge." - Participant
* "If you combine SCA tools with SAS, that would be very helpful." - Participant

HABITS
* Conduct semi-structured interviews to gather user experiences and challenges with SCA tools.
* Prioritize vulnerabilities based on CVSS scores, time effort, and impact assessment.
* Communicate SCA results effectively across different teams and stakeholders.
* Continuously improve SCA tools by incorporating user feedback and addressing identified issues.
* Evaluate SCA tools based on ease of deployment, accuracy, and compatibility with existing workflows.

FACTS
* The Log4Shell incident in 2021 highlighted the widespread impact of software vulnerabilities.
* SCA tools can identify vulnerabilities in direct and transitive dependencies within a software project.
* Different SCA tools have varying strengths and weaknesses across different ecosystems.
* Some SCA tools require access to source code, while others can work with metadata or binaries.
* Integrating SCA scans into CI/CD pipelines can automate vulnerability detection.
* Some organizations use SCA tools for mergers and acquisitions and export control compliance.
* Large organizations often develop custom tooling to manage and process SCA alerts.

REFERENCES
* Log4j library
* Babel Traverse
* React Scripts
* Black Duck tools
* GitHub Dependabot
* Static Analysis (SAS) tools

ONE-SENTENCE TAKEAWAY
Prioritize SCA tool context, user feedback, and communication for effective vulnerability management.

RECOMMENDATIONS
* Provide more context in vulnerability alerts, including reachability and exploitability information.
* Incorporate infrastructure context, such as network reachability and firewall configurations.
* Consider data flow and sanitization when assessing the impact of vulnerabilities.
* Offer actionable fix suggestions that consider potential breaking changes and alternative solutions.
* Implement user feedback mechanisms to continuously improve SCA tool accuracy and effectiveness.
* Evaluate SCA tools based on their compatibility with different ecosystems and languages.
* Tailor SCA tool deployment strategies to specific organizational workflows and pipelines.
* Facilitate communication and collaboration between security and engineering teams.
* Develop custom tooling or scripts to pre-process and manage large volumes of SCA alerts.
* Prioritize vulnerabilities based on a combination of CVSS scores, effort, and impact.
* Explore integrating SCA tools with static analysis and other security testing methods.
* Communicate SCA results clearly and concisely to different stakeholders, including legal teams.
* Consider mitigating vulnerabilities through isolation, network access removal, or other techniques.
* Investigate SCA tools that can analyze interactions between binaries in an ecosystem.
* Choose SCA tools that align with organizational needs and development practices.
* Understand the trade-offs of different SCA tool deployment methods, such as automated vs. manual scans.
* Establish clear communication channels and processes for addressing SCA results across teams.
* Use SCA tools to assess the security posture of acquired companies during mergers and acquisitions.
* Leverage SCA tools to ensure compliance with export control regulations and licensing requirements.
* Educate developers about the potential impact of SCA scans on CI/CD pipelines and build processes.
