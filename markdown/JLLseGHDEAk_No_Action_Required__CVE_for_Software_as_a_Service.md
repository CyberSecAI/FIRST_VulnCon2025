# No Action Required: CVE for Software as a Service

**Video URL:** [https://www.youtube.com/watch?v=JLLseGHDEAk](https://www.youtube.com/watch?v=JLLseGHDEAk)
**Video ID:** JLLseGHDEAk

---


**SUMMARY**
The panel discusses CVE assignment for cloud vulnerabilities, focusing on the changes in CVE CNA rules, the challenges of determining necessary actions, and customer protection.

**IDEAS:**
* Software as a service can be patched very quickly with awesome coverage, reducing the need for individual patching efforts.
* New CVE CNA rules technically changed in August 2024, impacting how cloud service providers assign and publish CVE IDs.
* Under the 3.0 rules, only the cloud service provider CNA could assign and publish CVE IDs for their service.
* The 4.0 rules dictate that CNAs should publish and disclose if vulnerabilities cause significant harm or require action.
* CNAs must not declare they will never assign CVEs for specific technologies like cloud, AI, or hardware vulnerabilities.
* A CVE record tag called "exclusively hosted service" is used narrowly when everything in the record is a hosted service.
* AWS helped found their security team 15 years ago, and the founder wrote security bulletins when starting at Amazon.
* Google started publishing CVEs for all critical vulnerabilities in Google Cloud, with the bug bounty team handling assessments.
* Microsoft's MSRC has been running Patch Tuesday for 12 years and participates in CVE board discussions and reporting standards.
* The change from 3.0 to 4.0 CVE rules involved significant effort, simplifying the rules by removing specific cloud references.
* CVE assignment is a natural process for AWS, evaluating concerns and determining if a CVE is required based on analysis.
* Google has been a CNA for years, requiring publication of CVEs for critical vulnerabilities, often requested by researchers.
* Microsoft faces challenges deciding whether to assign CVEs due to the high volume of internal and external researcher reports.
* Cloud vulnerabilities aren't fixed instantly; they require rollout and deployment across all affected cloud environments, which takes work.
* A key criterion for assigning CVEs is ensuring all customers are protected before disclosing the vulnerability to the public.
* If a vulnerability lacks a recognizable product name, assigning a CVE becomes difficult because there's nothing to tell people.
* "No action required" means customers don't need to do anything; the fix is automatically rolled out through normal processes.
* AWS errs on the side of caution, issuing CVEs if a risk assessment is needed by the customer, even with no action.
* Customer agency involves incident response actions, raising the question of whether a truly "no action required" CVE exists.
* Transparency and helping each other are crucial for improving industry safety, requiring action on the back end in a consolidated way.
* Compliance regimes affect CVE assignments, with some mandating direct reporting regardless of CVE issuance timing.
* CVD can be challenging, with external requests sometimes leading to CVE assignments and other times not, causing awkwardness.
* Applying a consistent rubric is essential for CVE assignments to avoid inconsistencies and maintain fairness in the process.
* Providing recognition for researchers is important, but some tie their self-worth to CVE numbers, requiring consideration.
* Amazon's private bug bounty program involves NDAs, raising questions about paying for researcher silence on vulnerabilities.
* NDAs in private bug bounty programs are appropriate for contracted work, offering benefits like paid accounts and training.
* Protecting the customer is paramount, ensuring they take appropriate actions, regardless of how the vulnerability was found.
* Issuing CVEs for cloud products benefits security by alerting competitors and customers to potential risks in similar technologies.
* Moving to SAS doesn't guarantee security; visibility into vulnerabilities within the SAS platform is crucial for paranoid individuals.
* Verifying security through versioning checks, compliance regimes, and independent audits is essential beyond trusting providers.
* Scans can be unreliable due to mitigations, but bug bounty programs offer rewards for proving external exploitability.
* Drawing a line on customer agency is important, allowing customers to assess risk themselves if not directly communicated with.
* The rule change enabling anyone to issue CVEs against AWS led to them owning the conversation and controlling CVE definitions.

**INSIGHTS:**
* Prioritizing customer protection over public recognition is paramount in vulnerability management, ensuring direct engagement and actionable information.
* Transparency through CVEs benefits the broader ecosystem, enabling security partners and vulnerability management services to enhance customer protection.
* The value of CVEs lies in their ability to provide a globally unique identifier for vulnerabilities, facilitating communication and coordination.
* Direct messaging and API accessibility are more effective than CVE databases for delivering actionable security information to customers.
* Compliance regimes and independent audits are crucial for verifying the security of cloud services beyond vendor claims.
* The shift towards cloud services necessitates a reevaluation of security responsibilities and the importance of shared responsibility models.
* Standardizing vulnerability reporting and remediation processes across different cloud providers enhances overall security posture.
* The balance between transparency and customer risk requires careful consideration, especially when disclosing vulnerabilities before fixes are fully deployed.
* The effectiveness of CVEs depends on their integration with vulnerability management tools and the ability to automate remediation actions.
* The evolution of CVE rules reflects the changing landscape of technology and the need for adaptable vulnerability management strategies.
* The human element of vulnerability management, including researcher recognition and customer communication, remains critical.
* The decision to assign a CVE involves weighing various factors, including customer impact, product recognition, and industry standards.
* The role of CNAs extends beyond simply assigning numbers; it involves actively contributing to the security ecosystem and protecting customers.
* The complexity of modern IT environments necessitates a holistic approach to security, considering interdependencies and software contracts.
* The journey to becoming a CNA reflects a growing sense of responsibility and the desire to control the narrative around security vulnerabilities.

**QUOTES:**
* "Software as a service can be patched very very very quickly with awesome coverage."
* "There's a tag for the CVE record that is called exclusively hosted service."
* "I have the dubious honor of being the intern who broke CVE before we launched it." - Beetle
* "No one is ever done with MITER."
* "Appreciate the effort and it led us to simplifying the rules in a way."
* "Cloud vulnerabilities aren't fixed in an instant. They have to be rolled out." - Lisa Olsen
* "Okay, that's fine, but let's make sure that everybody is protected, like every customer is protected before we disclose this vulnerability." - Lisa Olsen
* "If we can't name it, we can't give it a CBE because we have to we have to tell people something." - Lisa Olsen
* "It's great I do nothing I refresh my browser page in Outlook online or Gmail or something is just more secure."
* "When we say no action required, we mean full stop. No action required." - Beetle
* "We like to air on the side of caution in issuing a CVE specifically because we believe that." - Beetle
* "In order for our industry to get safer, we need to be more transparent and help each other."
* "Protecting the customer is the primary thing to do in this situation." - Lisa Olsen
* "We were doing intrusion detection system flyoffs at the time and you could look at, you know, seven different intrusion detection vendors."
* "The data the data shows that that's how they're finding the information." - Beetle
* "I really really do do support the sort of cataloging feature of CVE even if it's hopefully minimal extra effort." - Art

**HABITS:**
* Prioritizing customer protection in vulnerability management processes.
* Consistently applying a rubric when assigning CVEs to ensure fairness.
* Engaging directly with customers to communicate security information.
* Staying informed about compliance regimes and regulatory requirements.
* Participating in bug bounty programs to identify and address vulnerabilities.
* Verifying security claims through independent audits and version checks.
* Maintaining transparency by publishing security bulletins and CVE records.
* Collaborating with security partners to enhance customer protection.
* Continuously evaluating customer feedback to improve security practices.
* Using APIs to deliver actionable security information to customers.
* Automating remediation actions based on vulnerability data.
* Drawing clear lines on customer agency in vulnerability management.
* Reassessing rubrics and processes to ensure they are up to date.
* Weighing the benefits of public recognition against potential risks.
* Separating security compliance from security itself for focused action.
* Documenting vulnerabilities and providing information for industry use.

**FACTS:**
* Software as a service can be patched very quickly, reducing the need for individual patching efforts.
* CVE CNA rules changed in August 2024, impacting how cloud service providers assign and publish CVE IDs.
* Under the 3.0 rules, only the cloud service provider CNA could assign and publish CVE IDs for their service.
* The 4.0 rules dictate that CNAs should publish and disclose if vulnerabilities cause significant harm or require action.
* A CVE record tag called "exclusively hosted service" is used narrowly when everything in the record is a hosted service.
* Google has been a CNA for years, requiring publication of CVEs for critical vulnerabilities, often requested by researchers.
* Cloud vulnerabilities aren't fixed instantly; they require rollout and deployment across all affected cloud environments.
* Compliance regimes affect CVE assignments, with some mandating direct reporting regardless of CVE issuance timing.
* Amazon's private bug bounty program involves NDAs, raising questions about paying for researcher silence on vulnerabilities.
* Direct messaging and API accessibility are more effective than CVE databases for delivering actionable security information.
* Scans can be unreliable due to mitigations, but bug bounty programs offer rewards for proving external exploitability.
* The rule change enabling anyone to issue CVEs against AWS led to them owning the conversation and controlling CVE definitions.
* The number of CVE records tagged as "exclusively hosted service" is either 61 or 51, depending on the counting method.
* Lisa Olsen has been running Patch Tuesday at Microsoft for 12 years and joined the CBE board in 2018.
* Don Bailey (Beetle) helped found the AWS security team and wrote the initial security bulletins at Amazon.
* Mike Cotay leads the Google bug bounty program and started publishing CVEs for Google Cloud vulnerabilities.

**REFERENCES:**
* CVE (Common Vulnerabilities and Exposures)
* CNA (CVE Numbering Authority)
* AWS (Amazon Web Services)
* Google Cloud
* Microsoft
* MSRC (Microsoft Security Response Center)
* Patch Tuesday
* MITER Corporation
* Volcon
* CVSS (Common Vulnerability Scoring System)
* CWEs (Common Weakness Enumeration)
* Fed Ramp
* CVD (Coordinated Vulnerability Disclosure)
* GHSA (GitHub Security Advisory)
* GKE (Google Kubernetes Engine)
* IAS (Infrastructure as a Service)
* PAS (Platform as a Service)
* SAAS (Software as a Service)
* DNR (Detection and Response)
* Discord

**ONE-SENTENCE TAKEAWAY**
Prioritize customer protection through direct communication and actionable insights, leveraging CVEs to enhance ecosystem security and transparency.

**RECOMMENDATIONS:**
* Prioritize customer protection by directly engaging and providing actionable information, ensuring they can take appropriate actions promptly.
* Embrace transparency by publishing security bulletins and CVE records, contributing to the broader security ecosystem and enabling collaboration.
* Verify security claims through independent audits, version checks, and compliance regimes, ensuring trust is coupled with verification.
* Continuously evaluate customer feedback to improve security practices, adapting to evolving needs and enhancing customer satisfaction.
* Use APIs to deliver actionable security information to customers, enabling automated remediation and proactive threat mitigation.
* Automate remediation actions based on vulnerability data, reducing manual effort and improving response times to security incidents.
* Draw clear lines on customer agency in vulnerability management, empowering customers to assess risk and take appropriate actions.
* Reassess rubrics and processes to ensure they are up to date, adapting to the changing landscape of technology and threats.
* Weigh the benefits of public recognition against potential risks, balancing transparency with the need to protect customer data.
* Separate security compliance from security itself for focused action, ensuring that compliance efforts don't overshadow core security practices.
* Document vulnerabilities and provide information for industry use, contributing to the collective knowledge and improving overall security.
* Collaborate with security partners to enhance customer protection, leveraging their expertise and resources to address complex threats.
* Stay informed about compliance regimes and regulatory requirements, ensuring that security practices align with legal and industry standards.
* Participate in bug bounty programs to identify and address vulnerabilities, incentivizing researchers to find and report security flaws.
* Consistently apply a rubric when assigning CVEs to ensure fairness, maintaining objectivity and avoiding inconsistencies in the process.
* Engage directly with customers to communicate security information, providing clear and actionable guidance to mitigate potential risks.
