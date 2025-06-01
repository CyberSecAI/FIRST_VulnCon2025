# Resolution Revolution_ Turbocharging Security Ticketing Timelines

**Video URL:** [https://www.youtube.com/watch?v=5TmIj7gwcP0](https://www.youtube.com/watch?v=5TmIj7gwcP0)
**Video ID:** 5TmIj7gwcP0

---

SUMMARY
Shrui Data Gupta and Joe, product security engineers at Adobe, discuss using AI to improve security ticketing timelines.

IDEAS
* Vulnerabilities are increasing, but security resources are limited, leading to overwhelming ticket volume.
* Bug bounty programs, pentests, and supply chain issues contribute to the rising ticket counts.
* Triaging and support are insufficient to manage the increasing number of security tickets.
* Unmanageable deadlines, unmet SLAs, and high developer-to-security ratios exacerbate the problem.
* Code creation is increasing, but secure coding practices and staffing aren't keeping pace.
* Cybersecurity positions haven't increased proportionally to the rise in vulnerabilities.
* Scattered communication and fragmented documentation hinder vulnerability resolution.
* Knowledge gaps and outdated information further complicate vulnerability management.
* Vulnerabilities impact company reputation, finances, individuals, and systems.
* AI can leverage and redistribute bandwidth for developers and security staff.
* Security engineers and developers have different expertise, requiring effective communication.
* AI can bridge the gap between security and development expertise.
* A unified knowledge base can centralize bug details, code data, and expert insights.
* Accessing this knowledge base via Jira and Slack facilitates different communication styles.
* AI-driven code fixing initially faced challenges with inconsistent output and training data.
* Shifting left and automating pull requests for code fixes was a primary goal.
* Pulling down entire repos to find vulnerabilities proved inefficient.
* Training LLMs with vulnerable code examples requires a robust vulnerability logging system.
* Even with logged vulnerabilities, training data quality remained a challenge.
* Advanced prompting techniques, quality metrics, and context improved AI code fixing.
* Humans remain essential in the loop for effective AI-driven security processes.
* A tailored approach is needed, considering product and vulnerability specifics.
* Microservices can provide accurate security suggestions based on product and vulnerability type.
* A unified knowledge base merges bug details, code data, and expert insights.
* Jira attracts a passive audience, while Slack enables interactive data exploration.
* AI with context and domain expertise is crucial for effective vulnerability management.
* The knowledge base must contain all necessary details for fixing vulnerabilities.
* Coder configuration fixes provide representative examples rather than exact code fixes.
* Ticket quality varies, with some providing detailed information, others less so.
* Representative examples offer generic instances of fixes based on product and vulnerability type.
* Expert finders identify individuals who have previously solved similar issues.
* LLMs can analyze Jira comments to identify experts for specific vulnerabilities.
* Vector databases store expert information and ticket data for similarity searches.
* Reranking logic fine-tunes search results to ensure high accuracy.
* Best practices guidance educates developers on fixing classes of vulnerabilities.
* This guidance scales manual security guidance and adds context to recommendations.
* It incorporates company-specific recommendations and approved libraries.
* It includes short-term and long-term fixes, addressing both immediate and systemic issues.
* Retrieval augmented generation (RAG) is used to build best practices guidance.
* Similar ticket finders provide context and references to past issues.
* They help new developers and reveal patterns in vulnerabilities.
* They offer insights into a product's security posture for specific vulnerabilities.
* Feedback and evaluations are crucial for building effective AI systems.
* Human oversight and continuous feedback from developers and security teams are essential.
* Model output evaluations ensure generated content aligns with expectations.
* Metrics like hallucination, accuracy, and understandability assess recommendation quality.
* Starting small, iterating, and continuously improving are key to success.
* AI can reduce human toil in manual and tedious security workflows.
* Context is crucial for tailoring general-purpose LLMs to specific use cases.
* Empowering teams and fostering developer empathy are essential for product security.
* Integrating AI solutions into existing developer workflows is key for adoption.
* AI is not a job replacement but a tool to make tasks easier.

INSIGHTS
* Limited resources and increasing vulnerabilities necessitate AI-driven solutions for security.
* Effective vulnerability management requires bridging the gap between security and development expertise.
* Contextualized AI and unified knowledge bases are key for efficient vulnerability remediation.
* Tailored, product-specific approaches are essential for AI-driven security solutions in large organizations.
* Human oversight, continuous feedback, and iterative improvement are crucial for AI system development.
* Empowering developers and integrating AI into their workflows promotes secure coding practices.
* AI excels at automating tedious tasks and leveraging existing knowledge for improved efficiency.
* Context is king in AI, enabling tailored solutions and controlling model outputs.
* Security is a team sport, and developers are essential partners in building secure products.
* Continuous learning and exploration are vital for harnessing the full potential of AI in security.

QUOTES
* "The reality is the same that we have these increasing CVEs. We have limited security resources and security teams are just awash in tickets." - Joe
* "So despite all the hype, AI code fix just was not there." - Joe
* "And this kind of led to the insight that you still need humans in the loop." - Joe
* "So the AI, the knowledge base has to have all the details of the product and all the details that it could use to fix it." - Shrui Data Gupta
* "So we decided we could just deliver a representative example that would just be like a generic instance of what this could look like if we have no other information." - Shrui Data Gupta
* "So so many times we were people were tasked with solving a problem, they'd be assigned a ticket and they would have no idea where to turn, but usually someone has solved it before." - Shrui Data Gupta
* "So this capability is in a way to scale best practice guidance and add that recommendation, add that guidance to the ticket in addition to the fixes." - Shrui Data Gupta
* "So this kind of helps you understand also what how your product is doing in terms of like what what is the security posture for that particular vulnerability looking like for your product." - Shrui Data Gupta
* "So understanding what developers need, making security easy and accessible for them is very important because doing like building secure products is the right thing to do." - Shrui Data Gupta
* "AI is not here to take our jobs. AI is here to help us make things easier for us." - Shrui Data Gupta
* "Context is king." - Shrui Data Gupta

HABITS
* Continuously seek feedback from developers and security teams to improve AI systems.
* Evaluate and test AI models rigorously to ensure alignment with expectations.
* Start small with AI projects, iterate, and continuously improve based on feedback.
* Assess knowledge gaps and understand the ecosystem for effective vulnerability remediation.
* Empower developers by making security easy, accessible, and integrated into their workflows.
* Empathize with developers, understand their pain points, and tailor solutions to their needs.
* Curate and cater general-purpose LLMs for specific use cases by adding relevant context.
* Leverage existing tools and data to enhance AI-driven security solutions.
* Use trusted AI providers when building enterprise-level solutions.
* Monitor and log AI model outputs to evaluate performance and identify potential issues.
* Prioritize building secure products and incentivize developers to adopt secure coding practices.
* Collaborate with product teams and vulnerability management teams to gain valuable insights.
* Use vector databases and similarity searches to find relevant information and experts.
* Provide both short-term and long-term fixes to address immediate and systemic issues.
* Share learnings and insights with the community to foster collaboration and innovation.
* Explore and experiment with new AI technologies to discover opportunities for improvement.

FACTS
* The number of vulnerabilities is skyrocketing, posing a significant challenge for security teams.
* Security staffing levels are not keeping pace with the increasing number of vulnerabilities.
* Scattered communication and fragmented documentation hinder vulnerability resolution efforts.
* Vulnerabilities can have significant reputational, financial, and systemic impacts.
* Developers and security engineers often have disparate realms of expertise.
* AI can be used to bridge the gap between security and development knowledge.
* Jira and Slack cater to different communication styles and audience engagement.
* AI code fixing can be challenging due to inconsistent outputs and training data limitations.
* The quality of security tickets varies significantly, impacting remediation efforts.
* Large language models (LLMs) can be used to identify experts for specific vulnerabilities.
* Vector databases enable efficient similarity searches for relevant information.
* Best practices guidance can help developers fix classes of vulnerabilities.
* Retrieval augmented generation (RAG) can be used to build knowledge-based AI solutions.
* Similar ticket analysis can reveal patterns and trends in vulnerabilities.
* Human oversight and feedback are essential for developing effective AI systems.
* Model output evaluations help ensure the quality and accuracy of AI-generated content.

REFERENCES
* Jira
* Slack
* Azure OpenAI
* LangChain
* LangGraph
* Pinecone vector databases
* SARIF files

ONE-SENTENCE TAKEAWAY
Leverage AI and contextual knowledge to empower developers and streamline security remediation.

RECOMMENDATIONS
* Use AI to automate tedious security tasks and reduce human toil.
* Add context to general-purpose LLMs to tailor them to your needs.
* Empower developers by making security easy, accessible, and integrated.
* Foster developer empathy by understanding their workflows and pain points.
* Start small with AI projects, iterate, and continuously improve.
* Leverage existing security tools and data to enhance AI solutions.
* Use trusted AI providers for enterprise-level applications.
* Monitor and log AI model outputs to evaluate performance.
* Prioritize building secure products and incentivize developers.
* Collaborate with product and vulnerability management teams.
* Use vector databases for efficient similarity searches.
* Provide both short-term and long-term vulnerability fixes.
* Share learnings and insights to foster collaboration.
* Explore new AI technologies to discover opportunities.
* Evaluate and test AI models rigorously.
* Seek continuous feedback from developers and security teams.
