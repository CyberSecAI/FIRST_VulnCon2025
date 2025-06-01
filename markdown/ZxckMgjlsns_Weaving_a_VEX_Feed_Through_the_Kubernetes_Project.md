# Weaving a VEX Feed Through the Kubernetes Project

**Video URL:** [https://www.youtube.com/watch?v=ZxckMgjlsns](https://www.youtube.com/watch?v=ZxckMgjlsns)
**Video ID:** ZxckMgjlsns

---

SUMMARY
Puco Garcia discusses Kubernetes' new VEX tooling, its implementation, and how it improves security vulnerability assessments.

IDEAS
* VEX documents track vulnerability impact assessments over time, aiding security analysis.
* OpenVEX is a lean, linked data format designed for embedding in other formats.
* Kubernetes VEX feeds converge from component vulnerabilities, advisories, and base images.
* Go vcheck automatically detects non-impact vulnerabilities using the Go compiler.
* Maintainers provide expert assessments for vulnerabilities not caught by automated tools.
* Kubernetes security advisories inform VEX by identifying affected components.
* The VEX effort is coordinated between SIG Release, SIG Security, and the security response committee.
* Vexflow tool scans branches, opens triage issues, and generates VEX documents.
* ChatOps interface allows maintainers to issue assessments and justifications.
* The final VEX assembly combines branch assessments and adds container image specifics.
* Signed VEX documents are published to the GitHub attestation store for transparency.
* The policy engine checks for vulnerabilities and blocks releases if necessary.
* The Kubernetes release process aims for CRA compliance by addressing exploitable vulnerabilities.
* The initial VEX release focuses on non-exploitable vulnerabilities, aiding security.
* The VEX tooling is open source and available for use in other projects.
* The GitHub attestation store is read-only, preserving historical VEX data.
* VEX documents for the branch are generated during the triage process.
* The final VEX assembly discards vulnerabilities not present at release points.
* The VEX tooling integrates with existing Kubernetes infrastructure like owners files.
* The project aims to build a VEX stream for collaboration and data sharing.
* AquaSec VexHub is a repository of open source VEX information.
* There are open questions about handling vulnerabilities in base images.
* The project is considering hosting the VEX tooling in OpenVEX or Kubernetes.
* The project is discussing transparency of VEX statements with the Apache Software Foundation.
* There are concerns about attackers using VEX information to exploit vulnerabilities.
* The project aims to balance transparency with security considerations.

INSIGHTS
* VEX provides a structured approach to managing vulnerability information over time.
* OpenVEX's design promotes interoperability and integration with other security tools.
* Collaboration between different teams is crucial for effective VEX implementation.
* Automating vulnerability assessment improves efficiency and reduces manual effort.
* Maintainer expertise is essential for accurate and comprehensive vulnerability assessment.
* Integrating VEX with the release process ensures security considerations are addressed.
* The tooling enables maintainers to easily contribute to vulnerability assessments.
* Transparency in VEX reporting can benefit both defenders and attackers.
* Balancing transparency and security is a key challenge in vulnerability management.
* The project is actively working on improving and expanding its VEX tooling.

QUOTES
* "So me being here on the stage is like wearing both hats." - Puco Garcia
* "So this is I'm going to rush through the talk because it's like I only have half an hour." - Puco Garcia
* "Basically the dream that they were just discussing in the previous talk in open vex is a reality." - Puco Garcia
* "So you can attach if you publish a container image we can attach the documents signed together with the container image." - Puco Garcia
* "when you have mandates like the CRA which is requiring the shipping of products without known vulnerabilities." - Puco Garcia
* "Well, we think that there is a future where uh you can provide a security scan and pair it together with uh a VEX document." - Puco Garcia
* "So the VEX effort currently is being coordinated with between Z release which is the group that I'm a part of." - Puco Garcia
* "kubernetes is a CV number numbering authority so the the um the our like our advisories how do we how do they play into the the the whole ve system" - Puco Garcia
* "So, Kubernetes builds and releases images that are pulled um thousands maybe millions of times every month." - Puco Garcia
* "They are static. They once we build them they are never upgraded." - Puco Garcia
* "So we let's say that you have your code uh your uh your repository." - Puco Garcia
* "It's important to understand that Kubernetes always has three or four branches under maintenance which we need to vex constantly." - Puco Garcia
* "By the way this is this tool is is most likely so we're having this discussions on whether we're going to host it in Kubernetes or in open vex" - Puco Garcia
* "This tool uses if for those who are familiar, Kubernetes has the owners file which is a a way of creating a structure of um a structured uh permissions layer." - Puco Garcia
* "So I built um this demo about a there's um a lab uh for this project that has a a project that is specially crafted." - Puco Garcia
* "So by the way if anyone wants to see this live I can do it. Just look for me in the next couple of days and we can go over it." - Puco Garcia
* "So the idea here um is that in order for example to make this um compliant with the CRA no nonvulner no exploitable vulnerabilities." - Puco Garcia
* "This is kind of the way we are doing it now." - Puco Garcia
* "Uh we uh so the the tool is currently hosted here. it'll probably move to the to openvex or kubernetes depending on what happens in the next couple of weeks." - Puco Garcia
* "Uh so we are having this discussion with the Apache software foundation uh like multiple maintainers uh regarding whether it is good or okay to release a vex statement" - Puco Garcia
* "there's always an air gap. between uh like between the patch happening and and so on." - Munar Hafes
* "So, so the question is whether or not to uh quickly issue the VEX or like be more transparent or less transparent." - Munar Hafes

HABITS
* Puco Garcia wears multiple hats, contributing to different projects.
* Puco Garcia rushes through talks due to time constraints.
* Kubernetes maintainers actively assess vulnerabilities.
* Kubernetes uses automated tools like Go vcheck for vulnerability detection.
* Kubernetes uses a ChatOps interface for maintainers to interact.
* Kubernetes uses GitHub Actions for automation.
* Kubernetes uses the owners file for structured permissions.
* Kubernetes uses OSV scanner for vulnerability scanning.
* Kubernetes uses a policy engine to enforce security checks.
* Kubernetes uses GitHub's attestation store for VEX storage.
* Kubernetes prioritizes CRA compliance in its release process.
* Kubernetes scans code at build points for vulnerabilities.
* Kubernetes discards vulnerabilities not present at release.
* Kubernetes collaborates with other projects on VEX tooling.
* Kubernetes considers attacker perspectives in VEX discussions.

FACTS
* Trivy and Grype natively support OpenVEX document injection.
* The CRA mandates shipping products without known vulnerabilities.
* Kubernetes has three or four branches under constant maintenance.
* Kubernetes releases static images that are never upgraded.
* Kubernetes is a CVE Numbering Authority (CNA).
* Kubernetes advisories are a form of negative VEX.
* Kubernetes uses the OSV format for vulnerability data.
* Kubernetes uses Go modules for dependency management.
* The GitHub attestation store is read-only.
* Kubernetes has a demo repository with two crafted vulnerabilities.

REFERENCES
* Carabiner Systems
* Kubernetes
* OpenVEX project
* Open Source Security Foundation (OpenSSF)
* Trivy
* Grype
* Common Security Advisory Framework (CSAF)
* CycloneDX
* SPDX
* CRA (Cybersecurity and Infrastructure Security Agency)
* Go vcheck
* Go vol
* Kubernetes CVE feed
* OSV (Open Source Vulnerabilities) format
* AquaSec VexHub
* Kubernetes security advisories
* SIG Release
* SIG Security
* Security Response Committee (SRC)
* GitHub
* Owners file
* Vexflow tool
* ChatOps
* GitHub Actions
* GitHub attestation store
* Apache Software Foundation

ONE-SENTENCE TAKEAWAY
Kubernetes uses new VEX tooling to improve vulnerability assessments and ensure secure releases.

RECOMMENDATIONS
* Use VEX to track and manage vulnerability assessments over time.
* Adopt OpenVEX for its lean design and interoperability with other tools.
* Foster collaboration between security and release engineering teams.
* Automate vulnerability detection and assessment using tools like Go vcheck.
* Leverage maintainer expertise for accurate vulnerability assessments.
* Integrate VEX into the release process to address security concerns.
* Provide a user-friendly interface for maintainers to contribute assessments.
* Consider the potential impact of VEX transparency on both defenders and attackers.
* Strive for a balance between transparency and security in VEX reporting.
* Continuously improve and expand VEX tooling based on community feedback.
* Explore collaboration with other projects and initiatives like AquaSec VexHub.
* Address the challenge of managing vulnerabilities in base images.
* Consider hosting VEX tooling in a central location like OpenVEX or Kubernetes.
* Engage in discussions about VEX transparency with relevant organizations.
* Account for potential air gaps between patching and vulnerability disclosure.
* Evaluate the trade-offs between rapid VEX issuance and transparency.
