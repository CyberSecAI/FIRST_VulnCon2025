# Distribution Builders Meet VEX

**Video URL:** [https://www.youtube.com/watch?v=TCs33Yehxak](https://www.youtube.com/watch?v=TCs33Yehxak)
**Video ID:** TCs33Yehxak

---

SUMMARY
Marta discusses the Yocto Project, its CVE checking tool, VEX integration challenges, and future directions for embedded security.

IDEAS
* Yocto Project simplifies building custom Linux distributions for embedded devices.
* CVE check tool scans for vulnerabilities using package versions and metadata.
* Patches fix CVEs, but vendors can modify configurations, impacting vulnerability status.
* VEX doesn't express all desired statuses, like incorrect NVD entries.
* Merging SBOMs and VEXes for multiple processors in one product is needed.
* Two levels of assessments are needed: generic and product-specific.
* Open-source VEX specification and tooling are crucial for the embedded community.
* Machine-readable VEX fields are preferred for automated processing.
* Automated solutions are essential for product manufacturers lacking security teams.
* Yocto can be used to create diagnostic hardware devices for telecom protocol monitoring.
* Community interest drives the development of tools and recipes in Yocto.
* Embedded field is moving towards machine-readable formats for vulnerability information.
* Yocto Project's CVE checking code sees increasing interest and usage.
* Correct vulnerability information is crucial for regulatory and other reasons.
* VEX-like behavior is often done manually in spreadsheets, not machine-readable formats.
* Vendors can modify build configurations and potentially VEX statements.
* Patches can introduce new vulnerabilities or unblock existing ones.
* Inheritance of VEX statements and configurations is an open problem.
* Current VEX output is based on OpenVEX with additional statuses.
* Generating CVE-related information outside the build process is desired.
* Merging SBOMs and VEXes from different processors is a challenge.
* Different standards and multiple files complicate merging SBOMs and VEXes.
* Some VEX fields are human-readable, hindering machine processing.
* Many VEX formats fulfill their basic role effectively.
* Yocto can create diagnostic devices, but requires additional software development.
* Community interest drives Yocto's development direction.

INSIGHTS
* Yocto Project streamlines embedded Linux development, but vulnerability management is complex.
* VEX standardization and tooling are crucial for automated vulnerability analysis in embedded systems.
* Vendor modifications and patch management pose challenges for accurate vulnerability assessment.
* Machine-readable VEX formats are essential for scalable and automated security analysis.
* Combining SBOMs and VEXes from diverse sources is a key challenge for embedded security.
* The embedded community needs a unified, open-source VEX format with comprehensive statuses.
* Automated vulnerability management is critical for embedded manufacturers, especially those lacking security expertise.
* Yocto's extensibility enables custom diagnostic tools, but community involvement is key.
* The embedded industry is transitioning from manual to automated vulnerability reporting using VEX.
* Enhanced VEX expressiveness and machine readability are vital for effective vulnerability management.

QUOTES
* "The Yocto Project is a way to build your own Linux distribution." - Marta
* "It's a de facto standard for building custom Linux distributions." - Marta
* "CVE check is used to check the whole composition for non-vulnerabilities." - Marta
* "It's using package versions only and it's not testing if the vulnerability is actually present." - Marta
* "The GRUB project doesn't have a policy of stable versions." - Marta
* "The CVE checking in the Yocto Project is taking that into account." - Marta
* "This CVE doesn't apply." - Marta
* "Not applicable platform." - Marta
* "It's not exploitable." - Marta
* "It's not applicable because of a configuration." - Marta
* "A small embedded product is at least 200 packages." - Marta
* "We absolutely need the whole thing automated." - Marta
* "We need at least non-standard extensions to output all that we have." - Marta
* "There is no VEX statement for 'the NVD database is wrong for this entry'." - Marta
* "We do generate VEX today." - Marta
* "The current VEX output is based on OpenVEX." - Marta
* "Embedded vendors will quite likely need to merge SBOMs and VEXes." - Marta
* "It should be open source with open source tooling." - Marta
* "At this moment we have enough of formats." - Marta
* "It just has to be a standard format." - Marta
* "For the embedded crowd, it must be open source." - Marta
* "There's just more and more interest in the code itself." - Marta
* "They are currently mostly about generating SBOMs." - Marta
* "That's a very likely next step." - Marta
* "Moving to a machine-readable format maybe that's would be a good idea." - Marta

HABITS
* Marta works on open-source security, including the Yocto Project.
* Marta founded a company working 100% on open-source security.
* Marta researches and presents on cybersecurity topics like the Cyber Resilience Act.
* Marta actively participates in discussions and seeks solutions for VEX challenges.
* Marta collaborates with the embedded community to improve vulnerability management.
* Marta analyzes and addresses limitations of existing vulnerability scanning tools.
* Marta develops and maintains CVE checking code for the Yocto Project.
* Marta explores and evaluates different VEX formats and standards.
* Marta advocates for open-source specifications and tooling for VEX.
* Marta promotes automated solutions for vulnerability management in embedded systems.
* Marta encourages community involvement in Yocto's development.
* Marta shares examples and insights to facilitate discussions on VEX improvements.
* Marta emphasizes the importance of machine-readable data for automated processing.
* Marta addresses the need for merging SBOMs and VEXes from various sources.
* Marta highlights the challenges of manual vulnerability management in spreadsheets.

FACTS
* Yocto Project is used to build Linux distributions for embedded devices.
* Yocto Project supports various programming languages and ecosystems.
* Yocto Project uses recipes and layers to organize software packages.
* Yocto Project's CVE check tool uses the NVD database.
* GRUB project doesn't have a policy of stable versions.
* NVD database has issues with accepting or delaying patches.
* A small embedded product contains at least 200 packages.
* Embedded vendors often need to merge SBOMs and VEXes.
* Multiple processors in a device can lead to different SBOMs and VEXes.
* Different processors may use different toolchains and output formats.
* Embedded manufacturers often lack dedicated security teams.
* VEX formats often contain fields designed for human readability.
* Yocto can be used to create diagnostic hardware devices.
* Community contributions drive the development of Yocto recipes and tools.
* Embedded field is increasingly interested in VEX and vulnerability management.

REFERENCES
* Yocto Project
* CVE check
* VEX
* NVD database
* GRUB bootloader
* Cyber Resilience Act
* OpenVEX
* CISF
* ESPD3
* SBOMs
* GDB

ONE-SENTENCE TAKEAWAY
Standardize and automate VEX generation in Yocto Project to improve embedded vulnerability management.

RECOMMENDATIONS
* Adopt a unified, open-source VEX format with comprehensive status expressions.
* Develop open-source tooling for VEX generation, conversion, and merging.
* Prioritize machine-readable VEX fields for automated processing and analysis.
* Implement two levels of VEX assessments: generic and product-specific.
* Address the challenges of merging SBOMs and VEXes from multiple sources.
* Encourage community involvement in developing Yocto recipes and tools.
* Educate the embedded community about VEX and its benefits.
* Promote automated vulnerability management solutions for embedded systems.
* Advocate for clear guidelines on VEX usage and inheritance in Yocto.
* Explore solutions for handling vendor modifications and patch impacts on VEX.
* Improve NVD data accuracy and collaboration with open-source projects.
* Develop tools for analyzing embedded code for actual vulnerability presence.
* Consider Yocto for creating diagnostic hardware devices for specific needs.
* Research and address the open problems related to VEX inheritance.
* Continue advancing VEX integration within the Yocto Project.
* Foster collaboration between embedded vendors and security experts.
* Share examples and best practices for VEX implementation in Yocto.
* Develop automated solutions for generating VEX from spreadsheets.
* Investigate the use of Yocto for telecom protocol monitoring and analysis.
