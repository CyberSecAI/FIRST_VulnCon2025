# Identifying Malicious OSS Across Ecosystems

**Video URL:** [https://www.youtube.com/watch?v=qo8zG13I3dQ](https://www.youtube.com/watch?v=qo8zG13I3dQ)
**Video ID:** qo8zG13I3dQ

---

SUMMARY
At VonCon, Microsoft's open source security team member discusses identifying malicious open source software across ecosystems.

IDEAS
* Open-source software (OSS) is widely used, with a low barrier to entry for publishing.
* Malicious OSS packages are increasing, mirroring the growth of OSS overall.
* Traditional malware detection methods, static and dynamic analysis, have limitations.
* Metadata analysis offers an alternative approach to identifying malicious packages.
* Metadata includes package name, keywords, description, version, and author information.
* Interactive examples demonstrated how to spot suspicious metadata indicators.
* Libraries.io and similar platforms provide neutral metadata for analysis.
* Osimilation project collects metadata and applies rules to detect malware.
* Human review is essential for accurate malware identification.
* Exfiltration of data, droppers, crypto stealers, miners, and spam are common threats.
* Crash handler exfiltrated system information via Discord webhook.
* Agent base typo-squatted and downloaded scripts from Ethereum wallets.
* Spam campaigns abused npm's readme feature for advertising.
* Spam erodes trust and burdens package managers.
* Azure-themed spam packages highlighted the need for vigilance.
* T protocol's dependency-based ranking was exploited for profit.
* Automation is necessary but insufficient for malware detection.
* Attack techniques evolve, requiring continuous adaptation of detection rules.
* Attackers exploit any platform for financial gain, even small amounts.
* Collaboration and information sharing are crucial for supply chain security.
* Package managers strive to protect users, but shared responsibility is key.
* Prior open-source and academic work contributes to the fight against malware.

INSIGHTS
* The ease of publishing OSS creates opportunities for malicious actors.
* Metadata analysis is a valuable tool for detecting malicious OSS.
* Human expertise remains crucial for accurate malware identification.
* Malicious OSS employs diverse techniques for data exfiltration and execution.
* Spam and abuse erode trust and exploit platform features.
* Financial incentives drive malicious OSS activity, even for small gains.
* Supply chain security requires collaborative efforts and continuous improvement.
* Package managers play a vital role but cannot solely address the threat.
* Automation and human oversight are both essential for effective detection.
* Attack techniques evolve, necessitating ongoing adaptation and innovation.

QUOTES
* "I'm going to talk about malware. I'm not going to talk about vulnerabilities at all." - Speaker
* "96 or 97% of code bases include OSS." - Speaker
* "These packages have access to your build systems, they have access to your production systems." - Speaker
* "We're also seeing the number of malicious packages increasing year over year." - Speaker
* "Attackers love this capability." - Speaker
* "As soon as you install it, it runs Maven clean package." - Audience Member
* "It does suspicious things, but it's not malware." - Speaker
* "Easy mistake to make." - Speaker
* "This one's also funny because a lot of anti-virus would actually catch this." - Speaker
* "They all go out and scrape these package managers themselves." - Speaker
* "We generally always need a human in the loop to accurately identify." - Speaker
* "So some bad guy's just monitoring his Discord channel watching machines report in." - Speaker
* "They ran it through an obfuscator." - Speaker
* "Bad guys said, great, I'd like to use your ability to display web pages for free." - Speaker
* "Presumably, bad guys are making fractions of a penny, but they're making fractions of a penny for free." - Speaker
* "It erodes trust in the ecosystem." - Speaker
* "This has a lot of dependencies and we don't recognize any of them." - Speaker
* "42,000 dependent projects. That's not reasonable." - Speaker
* "Almost all the packages that have the T protocol are garbage." - Speaker
* "Automation is necessary to find malware across ecosystems but it's not sufficient." - Speaker
* "Attackers will abuse any platform that allows them to freely automate money-making schemes." - Speaker

HABITS
* Manually inspect suspicious packages and run tools to confirm malware.
* Collaborate with package managers to report and remove malicious packages.
* Continuously iterate on detection rules and techniques to adapt to evolving threats.
* Review package metadata for suspicious indicators like missing information or mismatches.
* Analyze code for obfuscation, suspicious connections, and data exfiltration attempts.
* Monitor logs for unusual activity and investigate potential malware infections.
* Stay informed about latest malware trends and attack techniques.

FACTS
* 96-97% of codebases include open-source software.
* Malicious OSS packages are increasing year over year.
* NPM is the largest repository and a major target for malware.
* Libraries.io provides neutral metadata for multiple package managers.
* The T protocol's ranking system was exploited for creating spam packages.
* 47,000+ spam packages related to the T protocol were removed from npm.

REFERENCES
* CRA
* CVE
* NPM
* Pip
* NuGet
* VS Marketplace
* Libraries.io
* deps.dev
* OSSF's malicious package dataset
* Express.js
* Crash Handler package
* Libraries.io
* Agent Base package
* Prettier package
* Discord
* Ethereum
* T protocol
* T-rank
* Leftpad package
* Socket

ONE-SENTENCE TAKEAWAY
Automate metadata analysis and human review to combat the rising threat of malicious open-source software.

RECOMMENDATIONS
* Scrutinize OSS metadata for suspicious indicators before incorporating.
* Implement robust security measures in build and production systems.
* Collaborate with security researchers and package maintainers.
* Utilize tools and platforms that provide neutral metadata analysis.
* Stay informed about evolving attack techniques and malware trends.
* Report suspicious packages to package managers promptly.
* Develop and refine automated detection rules for malicious OSS.
* Incorporate human review into the malware identification process.
* Educate developers about secure OSS usage and best practices.
* Advocate for improved security measures within package ecosystems.
* Consider the potential impact of OSS dependencies on supply chain security.
* Foster collaboration and information sharing within the security community.
* Support efforts to enhance the security of open-source software.
* Continuously adapt and innovate to stay ahead of evolving threats.
* Prioritize supply chain security as an integral part of development.
