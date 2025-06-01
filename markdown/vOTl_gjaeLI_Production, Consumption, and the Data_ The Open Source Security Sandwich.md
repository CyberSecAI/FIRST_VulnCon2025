# Production, Consumption, and the Data_ The Open Source Security Sandwich

**Video URL:** [https://www.youtube.com/watch?v=vOTl_gjaeLI](https://www.youtube.com/watch?v=vOTl_gjaeLI)
**Video ID:** vOTl_gjaeLI

---

SUMMARY
Mike, CTO of Casari, discusses software supply chain security, vulnerabilities, SBOMs, and open-source tools like Guac.

IDEAS
* Software supply chain security is securing the production and consumption of software.
* Vulnerabilities are discovered frequently, requiring constant vigilance.
* Supply chain attacks can target various stages of the software development lifecycle.
* Open-source tools and best practices can improve supply chain security.
* Threat modeling and risk assessment are crucial for effective security.
* Security approaches should be tailored to the specific application and its risks.
* Tracking software throughout its lifecycle is essential for identifying vulnerabilities.
* Open specifications and standards promote interoperability and wider support.
* SBOMs provide a standardized way to communicate software supply chain metadata.
* Overreliance on SBOMs without proper understanding can be ineffective.
* Tools like Guac can help analyze and manage software supply chain metadata.
* Open-source projects need better tools for analyzing and storing SBOMs.
* The "sandwich" model illustrates the layers of software supply chain security.
* Trust foundations are crucial for knowing who is involved in the supply chain.
* Attesting to software origins and build processes helps track vulnerabilities.
* Aggregating and synthesizing data helps identify widespread issues.
* Policy and action based on insights are key to effective remediation.
* Guac helps create a graph of software dependencies and vulnerabilities.
* Observability in the supply chain is crucial for understanding risks.
* Guac enables querying software for vulnerabilities and other metadata.
* An SDLC control plane is needed to manage the software ecosystem.
* This control plane would manage software ingestion and developer access.
* S2C2F provides rules for consuming software securely.
* S2C2F helps determine how to handle software not meeting security baselines.
* OpenSSF provides resources and community for supply chain security.
* Contributing to open-source projects improves the security ecosystem.

INSIGHTS
* Software supply chain security requires a holistic approach, from production to consumption.
* Frequent vulnerabilities necessitate continuous monitoring and proactive security measures.
* Tailoring security measures to specific applications balances safety and progress.
* Tracking software provenance and build processes enables faster vulnerability identification.
* Open standards and tools foster collaboration and wider adoption of best practices.
* SBOMs are valuable but require proper understanding and effective tooling.
* Tools like Guac enhance visibility and analysis of supply chain metadata.
* A comprehensive control plane is needed to manage the complexity of software ecosystems.
* Establishing trust foundations and attesting to software origins are fundamental for security.
* Contributing to open-source projects strengthens the overall security posture.

QUOTES
* "Software supply chain security is just the act of securing the production and consumption of software." - Mike
* "Security can often feel like a dumpster fire." - Mike
* "It's turtles all the way down as they say." - Mike
* "When all you have is a hammer, everything looks like a nail." - Mike
* "S2C2F is a set of rules for consuming software." - Mike

HABITS
* Use open-source tools and best practices for software supply chain security.
* Threat model and assess risks to design appropriate security controls.
* Track software throughout its lifecycle to identify vulnerabilities.
* Use open specifications and standards for better interoperability.
* Generate and analyze SBOMs to understand software composition.
* Contribute to open-source projects to improve security tools.
* Attend open-source community meetings and working groups.
* Open issues and submit pull requests to contribute to projects.

FACTS
* Vulnerabilities are frequently discovered in software, sometimes monthly.
* The XZ utils incident involved malicious code injection into a repository.
* The SolarWinds attack compromised various parts of the SDLC.
* The Debian OpenSSL bug led to OpenSSL being compromised.
* RubyGems was once compromised, allowing malicious software publishing.
* Typosquatting is a common technique for distributing malicious packages.
* Maven Central is backed by a commercial enterprise.
* Many open-source projects are nonprofits.
* Kubernetes has a complex dependency tree.
* S2C2F will become part of the Salsa project.

REFERENCES
* Casari
* Securing the Software Supply Chain (book)
* OpenSSF
* CNCF
* Guac
* Salsa
* XZ utils
* OpenSSH
* Polyfill
* SolarWinds
* RubyGems
* requests (Python library)
* Splunk
* VEX
* Scorecard
* Ocal
* S2C2F
* In-toto Layouts
* The Update Framework (TUF)
* SBOMs
* jQ
* Snyk
* Trivy
* SPDX
* CycloneDX
* bom-ctl
* OpenVEX
* OSV
* ClearlyDefined
* Depths.dev
* Prometheus Golang client
* Kubernetes
* GitHub
* GitHub Actions
* Google
* IBM

ONE-SENTENCE TAKEAWAY
Prioritize software supply chain security by leveraging open-source tools and best practices.

RECOMMENDATIONS
* Implement threat modeling and risk assessment for software projects.
* Track software throughout its lifecycle to identify vulnerabilities.
* Use open specifications and standards for wider tool support.
* Generate and analyze SBOMs to understand software composition.
* Use tools like Guac to analyze and manage supply chain metadata.
* Contribute to open-source projects to improve security tooling.
* Explore S2C2F for secure software consumption practices.
* Join OpenSSF and participate in its working groups and meetings.
