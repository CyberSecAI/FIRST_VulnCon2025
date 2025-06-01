# Managing Vulnerabilities through SSDLC

**Video URL:** [https://www.youtube.com/watch?v=bLmsdsxmJGE](https://www.youtube.com/watch?v=bLmsdsxmJGE)
**Video ID:** bLmsdsxmJGE

---

SUMMARY
Luchi Stanesco, security engineering manager at Canonical, discusses Canonical's Secure Software Development Lifecycle (SSDLC) processes.

IDEAS
* Threat modeling should be done by product teams who understand their product best.
* Defining the scope of threat modeling is crucial for its effectiveness and feasibility.
* Data flows between assets are essential for a meaningful threat model.
* Identify and quantify threats to assets, considering both known and imagined threats.
* Mitigating controls should address identified threats and protect valuable assets.
* Residual risk assessment helps determine the need for additional security controls.
* Threat modeling should be done continuously to adapt to changing systems and contexts.
* Integrate static code analysis tools into CI pipelines for automated quality checks.
* Static code analysis tools do not guarantee the absence of all security issues.
* Vulnerability scanning helps identify known vulnerabilities and manage dependencies.
* Different vulnerability scanners have different strengths and should be tested thoroughly.
* Rescan artifacts periodically, even after a clean bill of health at release time.
* Threat-led penetration testing focuses on the most important aspects of a product.
* Vulnerability response should be treated as business as usual, not a crisis.
* Define a product lifecycle and support period for handling vulnerabilities.
* Prioritize vulnerabilities based on their severity and potential impact.
* Mitigations can be provided sooner than root cause fixes in some cases.
* Communicate vulnerability information transparently and empathetically to users.
* Security documentation is crucial for transparency and user empowerment.
* Consider different user personas when writing security documentation.
* Discuss identified risks and information security implications in documentation.
* Cover security-sensitive functions like authentication and cryptography thoroughly.
* Provide how-to guides for secure product usage in various contexts.
* How-to guides should include checklists and security best practices.
* Hardening guides help users adapt the product to their specific security contexts.
* Security is an ongoing process of learning, adapting, and improving.
* Canonical uses a combination of tools and processes to manage security risks.
* Open source projects benefit from a structured approach to security.
* Collaboration between security and product teams is essential.
* Transparency and communication are key to effective security practices.
* Continuous improvement is vital for staying ahead of evolving threats.

INSIGHTS
* Empower product teams to own threat modeling with appropriate security guidance.
* A well-defined scope is essential for effective and manageable threat modeling.
* Visualizing data flows as a graph enhances threat model understanding.
* Threat identification should encompass both known vulnerabilities and potential unknowns.
* Mitigating controls are subject to failure and require ongoing evaluation.
* Continuous threat modeling adapts to evolving systems and changing contexts.
* Integrating security into daily workflows normalizes its importance.
* Vulnerability scanning is a continuous process, not a one-time event.
* Threat-led penetration testing ensures focus on critical vulnerabilities.
* Vulnerability response should be a systematic and prioritized process.
* Transparent communication builds trust and reduces user panic.
* Security documentation empowers users to make informed security decisions.

QUOTES
* "Threat modeling can actually be done by product teams and is best done by product teams." - Luchi Stanesco
* "At the end of the day, knowledge is key, right?" - Luchi Stanesco
* "You can mitigate, avoid, transfer, or simply accept a risk, but you just don't want to ignore them." - Luchi Stanesco
* "Threat modeling should be done continuously because your systems are going to change." - Luchi Stanesco
* "A false sense of security is really dangerous." - Luchi Stanesco
* "Each artifact needs to be rescanned periodically forever." - Luchi Stanesco
* "Don't run around like headless chicken. It has to be business as usual because you will find vulnerabilities." - Luchi Stanesco
* "Not all vulnerabilities disclosed are equal." - Luchi Stanesco
* "Security documentation is great. Writing it is difficult." - Luchi Stanesco
* "Cryptography is a moving target. It always changes." - Luchi Stanesco
* "It's not a magic wand, right? It's meant to protect certain things." - Luchi Stanesco

HABITS
* Allocate dedicated time for handling and addressing vulnerabilities.
* Continuously perform threat modeling to adapt to system changes.
* Integrate static code analysis into CI pipelines for automation.
* Regularly rescan artifacts for vulnerabilities, even after release.
* Prioritize vulnerabilities based on severity and business impact.
* Communicate vulnerability information transparently to users.
* Write security documentation with different user personas in mind.
* Use threat models to inform security documentation and user guidance.
* Document security-sensitive functions and their proper usage.
* Create how-to guides with checklists for secure product usage.
* Develop hardening guides to help users secure the product in their context.

FACTS
* Cyber security threats are often subtle, nuanced, and not always immediately visible.
* Static code analysis tools can identify potential problems and improve code quality.
* Vulnerability scanners rely on identifying known vulnerabilities.
* Threat-led penetration testing is mandated by the EU DORA regulation for the financial sector.
* Not all vulnerabilities are created equal; prioritization is essential.
* TLS, while a security control, can be broken and should be included in threat modeling.
* A product's deployment context significantly influences its security.
* Security documentation empowers users to use products securely.
* Cryptography is constantly evolving and requires ongoing attention.
* Different user personas have different security information needs.

REFERENCES
* Canonical's blog post on tracking code quality
* EU DORA regulation
* GitHub Security Advisory features
* Canonical's products: Mass and Juju, and their how-to guides

ONE-SENTENCE TAKEAWAY
Integrate security throughout the software development lifecycle for robust and user-focused protection.

RECOMMENDATIONS
* Empower product teams to conduct threat modeling with security team support.
* Clearly define the scope of threat modeling to avoid unnecessary complexity.
* Visualize data flows between assets to understand system interactions.
* Consider both known and potential unknown threats during threat modeling.
* Document mitigating controls and regularly assess their effectiveness.
* Perform threat modeling continuously to adapt to evolving systems.
* Integrate static code analysis into CI/CD pipelines for automated checks.
* Use multiple vulnerability scanners and understand their limitations.
* Rescan artifacts periodically for vulnerabilities, even after release.
* Conduct threat-led penetration testing to focus on critical areas.
* Treat vulnerability response as a normal business process, not a crisis.
* Prioritize vulnerabilities based on severity and potential impact.
* Provide mitigations quickly, even before addressing the root cause.
* Communicate vulnerability information transparently and empathetically.
* Write security documentation for different user personas and their needs.
* Include how-to guides and hardening guides for secure product usage.
