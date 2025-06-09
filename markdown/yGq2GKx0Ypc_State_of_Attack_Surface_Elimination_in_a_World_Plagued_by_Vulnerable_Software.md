# State of Attack Surface Elimination in a World Plagued by Vulnerable Software

**Video URL:** [https://www.youtube.com/watch?v=yGq2GKx0Ypc](https://www.youtube.com/watch?v=yGq2GKx0Ypc)
**Video ID:** yGq2GKx0Ypc

---

SUMMARY
Mayur and Goro from Qualys discuss Veda, a vulnerability elimination system using deep analysis and mitigation.

IDEAS
* Attack surface discovery methods are not all created equal, leading to inconsistencies.
* Vulnerabilities without CVEs pose a significant challenge for detection and remediation.
* The number of discovered vulnerabilities is increasing exponentially, outpacing solutions.
* Log4j exemplifies the difficulty of detecting and mitigating shared library vulnerabilities.
* Traditional tools struggle to find vulnerabilities in shared libraries and applications.
* The XZ supply chain vulnerability highlights the vast attack surface of small changes.
* Package managers, installations, and compilations introduce variability in vulnerability types.
* Undetected vulnerabilities lead to increased mean time to patch and detect issues.
* Vendors may not patch all vulnerabilities, leaving systems exposed to known threats.
* Veda uses feature extraction from multiple sources, including security bulletins and binaries.
* Veda correlates security bulletins with binary information to pinpoint vulnerabilities.
* Veda extracts over 1300 features from both patched and vulnerable binaries.
* Veda uses supervised machine learning-based topic modeling for analysis.
* Veda considers CPE, CWE, CVSS, and other factors for comprehensive vulnerability assessment.
* Veda extracts code blocks from binaries and analyzes system calls and register movements.
* Veda uses a trained classifier to identify vulnerabilities based on extracted features.
* Veda's deep learning method uses auto feature extraction and labeling with CVE/CWE data.
* Veda uses offline LLMs like Code Llama, CodeGen 2, and Mistral for embedding generation.
* Embeddings are vectorized and labeled with CVE, CWE, and CVSS information for classification.
* Veda maps binaries to CPEs to identify the associated vendor and potential vulnerabilities.
* Code context is crucial for understanding and mitigating vulnerabilities effectively.
* Mitigations are stateless, resource-efficient ways to eliminate attack surfaces.
* Veda's mitigations aim to prevent exploitation regardless of specific exploits.
* Veda's approach is version-independent, reducing reliance on software updates.
* Veda addresses repackaged applications and bundled libraries, like Log4j and Chrome.
* Mitigations can involve registry changes or configuration adjustments to block exploits.
* Mitigations reduce dependence on software updates, which can be costly and disruptive.
* End-of-life software and hardware pose challenges that mitigations can address.

INSIGHTS
* The increasing number of vulnerabilities necessitates innovative approaches to security.
* Contextual analysis of code is essential for accurate vulnerability identification and mitigation.
* Veda's deep analysis and mitigation strategy offers a proactive approach to vulnerability management.
* Version-independent vulnerability detection reduces reliance on constant software updates.
* Mitigations provide a cost-effective and efficient way to address vulnerabilities.
* Veda's comprehensive approach addresses the challenges of modern software supply chain security.
* Veda's use of deep learning and LLMs represents a cutting-edge approach to vulnerability analysis.
* Focusing on code context allows for payload-agnostic mitigations, covering a wider range of threats.
* Veda's methods enable proactive vulnerability elimination, reducing the mean time to patch.
* Veda's approach offers a more holistic and effective solution to vulnerability management.

QUOTES
* "Attack surface is anything that can be quantified." - Mayur
* "Once an attack surface is quantified, it becomes a vulnerability." - Mayur
* "Not all vulnerabilities or remediation workflows are equal." - Mayur
* "You can't patch what you can't see." - Mayur
* "The number of vulnerabilities being discovered is growing exponentially." - Mayur
* "Log4j was difficult to detect and mitigate." - Mayur
* "Traditional tools find difficulty finding vulnerabilities in shared libraries." - Mayur
* "Veda is vulnerability elimination through deep analysis." - Mayur
* "We use feature extraction from multiple locations, multiple sources." - Mayur
* "We correlate security bulletins with binary information to pinpoint vulnerabilities." - Mayur
* "We extract over 1300 features from binaries." - Mayur
* "We use classic supervised machine learning-based topic modeling." - Mayur
* "Vulnerabilities require context and code has context." - Goro
* "Mitigations are small pieces of code or configuration that you can apply." - Goro
* "Mitigations are totally stateless." - Goro
* "Mitigations eliminate the attack surface." - Goro
* "Mitigations will make sure that vulnerabilities cannot be exploited." - Goro
* "Major benefits: we don't have to worry about the version of the software anymore." - Goro
* "It's comprehensive vulnerability mitigation." - Goro
* "We have reduced dependency on software updates." - Goro
* "Veda hunts vulnerabilities within the code." - Goro
* "It becomes version independent detection." - Goro
* "We're also looking at repackaged applications." - Goro
* "To find whether something is vulnerable, we have to go inside the code." - Goro
* "We apply a payload agnostic mitigation." - Goro
* "Software updates can sometimes be expensive." - Goro
* "Mitigations help more." - Goro

HABITS
* Correlating security bulletins with binary data for analysis.
* Using supervised machine learning for vulnerability detection.
* Extracting features from binaries for vulnerability analysis.
* Reverse engineering binaries to understand code context.
* Applying stateless mitigations to eliminate attack surfaces.
* Focusing on code context for payload-agnostic mitigation.
* Prioritizing vulnerability mitigation over software updates.
* Using offline LLMs for data privacy and security.
* Continuously improving and refining vulnerability detection systems.
* Collecting data from diverse sources like NVD and GitHub.
* Considering CPE, CWE, and CVSS for vulnerability assessment.
* Analyzing system calls and register movements in binaries.
* Using a trained classifier for vulnerability identification.
* Mapping binaries to CPEs for vendor identification.
* Fine-tuning LLMs for improved accuracy in vulnerability detection.

FACTS
* The number of CVEs is growing exponentially year over year.
* Log4j is a well-known and difficult-to-mitigate vulnerability.
* XZ supply chain vulnerability demonstrated a large attack surface.
* Software updates can be expensive and include breaking changes.
* Hardware devices can go end of life and become unsupported.
* Some vulnerabilities don't have a CVE identifier assigned.
* Attack surface discovery scans can yield different results.
* Every organization has its own vulnerability remediation process.
* Shared libraries can exist in multiple locations on a system.
* Different installation methods create variability in vulnerability types.
* Undetected vulnerabilities increase mean time to patch and detect.
* Vendors may only patch certain classes of vulnerabilities.
* Qualys was founded in 1999 and has discovered many vulnerabilities.
* Shell shock is a known vulnerability with many variants.
* MITER publishes a yearly list of CPEs.

REFERENCES
* Qualys Guard platform
* Veda (Vulnerability Elimination through Deep Analysis)
* NVD (National Vulnerability Database)
* GitHub Advisories
* Nuclei Templates
* CPE (Common Platform Enumeration)
* CWE (Common Weakness Enumeration)
* CVSS (Common Vulnerability Scoring System)
* MITER
* CVE (Common Vulnerabilities and Exposures)
* Log4j vulnerability
* XZ supply chain vulnerability
* Google Chrome
* Electron application
* Qualys Threat Research Unit
* Code Llama
* CodeGen 2
* Mistral
* TruRisk Eliminate

ONE-SENTENCE TAKEAWAY
Veda uses deep learning and code context analysis to mitigate vulnerabilities, reducing reliance on patches.

RECOMMENDATIONS
* Prioritize code context analysis for comprehensive vulnerability understanding.
* Implement payload-agnostic mitigations to cover a broader range of exploits.
* Reduce reliance on software updates by using version-independent detection.
* Utilize deep learning and LLMs for advanced vulnerability analysis.
* Consider mitigations as a cost-effective alternative to patching.
* Address end-of-life software/hardware vulnerabilities with mitigations.
* Explore Veda and TruRisk Eliminate for proactive vulnerability management.
* Correlate security bulletins with binary data for precise vulnerability identification.
* Extract features from binaries to analyze and understand vulnerabilities.
* Reverse engineer binaries to gain valuable code context for mitigation.
* Apply stateless mitigations to efficiently eliminate attack surfaces.
* Focus on code context to develop payload-agnostic mitigation strategies.
* Prioritize vulnerability mitigation over costly and disruptive software updates.
* Use offline LLMs to ensure data privacy and security during analysis.
* Continuously improve vulnerability detection systems for better accuracy.
* Collect data from various sources to enhance vulnerability detection capabilities.
* Consider CPE, CWE, and CVSS for comprehensive vulnerability assessment.
* Analyze system calls and register movements to understand binary behavior.
