# Using Jupyter Notebooks to Explore Public CVE Data

**Video URL:** [https://www.youtube.com/watch?v=CUzluKxfQO0](https://www.youtube.com/watch?v=CUzluKxfQO0)
**Video ID:** CUzluKxfQO0

---

SUMMARY
Jerry Gamblin, principal engineer at Cisco, discusses CVE data analysis, its importance, and tools for making it more accessible.

IDEAS
* CVE data analysis should be more open and accessible to everyone.
* Many people don't understand or even look at CVE data regularly.
* Open-source projects can make CVE data publicly available for analysis.
* Public CVE data is often enriched and sold by various companies.
* Vulnerability visualizations are effective and engaging for audiences.
* Simple CVE graphs can generate significant interest on platforms like LinkedIn.
* The NVD sometimes maps CVE data to private email databases.
* It's important to understand how CVE data flows through the system.
* The CVE program is valuable, but its data is underutilized.
* Many companies still rely on the NVD program instead of raw CVE data.
* Using raw CVE data can be challenging for individuals due to its format.
* The NVD JSONL file simplifies access to CVE data compared to individual files.
* The CVE list repo lacks an easy way to filter by publication year.
* The speaker's blog revealed a 10-year-old data issue at Cisco.
* Jupyter notebooks, pandas, and matplotlib are useful for CVE analysis.
* MyBinder allows running GitHub repos in Jupyter notebooks for free.
* Google Colab lacks easy repo cloning and no-authentication options.
* Personal projects shouldn't be relied upon for work-related processes.
* The CVE program's schema is incomplete and needs improvement.
* Only a small percentage of CVE schema keys have descriptions or types.
* The CVE program lacks control over major CVE publishing tools.
* Data frames simplify CVE data analysis by providing an in-memory structure.
* Chunking code in Jupyter notebooks helps with debugging and organization.
* The CVE program sometimes includes CVEs with missing publication dates.
* The speaker worked for the government, Carfax, and Kenna Security.
* Cisco aims to improve CVE data quality and usability.
* Verbose CVE descriptions may be perceived as increasing exploit risk.
* Short CVE descriptions are common, especially from companies like Microsoft.
* LLMs could potentially improve CVE descriptions automatically.
* Competing data formats hinder collaboration and tool development.
* CPE is considered an abandoned format with unclear ownership.
* Some CVEs have an excessively high number of affected products listed.
* Data quality issues in CVEs need to be addressed more effectively.
* Patchstack effectively utilizes the CVE program for WordPress plugins.
* The CVE program needs better intake policies for data quality.

INSIGHTS
* Open access to CVE data empowers individuals and improves security.
* Visualizing CVE data enhances understanding and engagement.
* The CVE data ecosystem needs better quality control and standardization.
* Utilizing raw CVE data requires technical expertise and effort.
* The CVE program's structure and tooling require modernization.
* MyBinder facilitates accessible and collaborative data analysis.
* Personal projects can reveal systemic data issues in organizations.
* The source of truth for CVE data is becoming increasingly fragmented.
* Balancing data transparency with security concerns is crucial.
* Competing formats and abandoned standards hinder progress.

QUOTES
* "I want to make CVE data analysis more open and available to the public." - Jerry Gamblin
* "Vulnerability visualizations work and work really well." - Jerry Gamblin
* "Nobody looks at the data." - Jerry Gamblin
* "I love the CVE program. Nobody uses their data." - Jerry Gamblin
* "Please don't build your work-related processes off of my personal projects." - Jerry Gamblin
* "This is the interactive part." - Jerry Gamblin
* "The AI codebots are great at Jupiter and pandas." - Jerry Gamblin
* "Only 62% of the keys have descriptions in the CVE schema." - Jerry Gamblin
* "The pattern is the only data quality match that they do at this point in the CVE program." - Jerry Gamblin
* "Right now the CVE program does not own any of the major tooling that is used by CNAs to publish CVEs." - Jerry Gamblin
* "A data frame, think of it as an in-memory database Excel spreadsheet." - Jerry Gamblin
* "Welcome to the life of live demos." - Jerry Gamblin
* "For the longest time, the CVE program just kind of outsourced all of that work to NVD." - Jerry Gamblin
* "Who is the source of truth for CVE data?" - Jerry Gamblin
* "We really need to get serious about data quality." - Jerry Gamblin
* "I'm happy to come help you at your desk." - Jerry Gamblin
* "I think CPE is an abandoned format." - Jerry Gamblin

HABITS
* Analyzes CVE data and shares insights on his blog and LinkedIn.
* Runs a website that hosts updated NVD JSONL files.
* Creates and shares Jupyter notebooks for CVE data analysis.
* Attends meetings to advocate for CVE data users.
* Works on improving CVE data quality within Cisco.
* Uses data analysis to identify and understand data completeness.
* Leverages GitHub actions to automate website updates.
* Presents talks on CVE data quality and related topics.
* Actively participates in CVE-related working groups.
* Encourages community involvement in improving CVE data.

FACTS
* Only 62% of CVE schema keys have descriptions, and 50% have types.
* Patchstack outpublishes MITRE as a CNA, focusing on WordPress plugins.
* CVE program's data quality checks rely solely on pattern matching.
* The CVE program doesn't own the primary tools used for publishing CVEs.
* Carfax was once the world's largest data company.
* There are approximately 250,000 CVE records.
* Some CVEs have over 4,800 affected products listed.
* The minimum description length for a CVE is one character.
* MyBinder offers free cloud-based Jupyter notebook execution.
* The NVD JSONL file contains every CVE record.

REFERENCES
* CVE program
* NVD
* NVD 2.0 API
* nvd.handsonhacking.org
* CVE list (version 5)
* Jupyter notebooks
* Pandas
* Matplotlib
* MyBinder
* Google Colab
* GitHub
* Discord
* LinkedIn
* cve.icu
* jerry.gamblin.com
* GitHub repo (github.com/jgamblin/workshop)
* NVD JSONL file
* CVE schema
* CVE data quality
* NVD++
* OSV.dev
* SBOM
* SPDS
* CPE
* Pearl
* Omnivore
* Volcon/Volagram
* Kenna Security
* Cisco
* MITRE
* Patchstack.com
* Kernel.org
* WordPress

ONE-SENTENCE TAKEAWAY
Improve CVE data quality and accessibility through open analysis and tooling modernization.

RECOMMENDATIONS
* Explore CVE data using provided Jupyter notebooks and resources.
* Advocate for improved CVE schema completeness and data quality.
* Utilize vulnerability visualizations to communicate insights effectively.
* Consider raw CVE data for deeper analysis, but be mindful of challenges.
* Support open-source projects that enhance CVE data accessibility.
* Contribute to discussions about the source of truth for CVE data.
* Explore alternative data sources like NVD++, OSV.dev, and GitHub's database.
* Use data frames and chunking for efficient CVE data analysis in Jupyter.
* Familiarize yourself with the CVE program's schema and data structure.
* Engage with the CVE community to address data quality concerns.
* Consider the implications of verbose versus concise CVE descriptions.
* Push for standardization and interoperability between CVE data formats.
* Investigate and address the issue of excessive CPE counts in some CVEs.
* Don't rely on personal projects for critical work-related processes.
* Share your CVE data analysis insights and contribute to the community.
* Contact the speaker for further assistance or questions about CVE data.
