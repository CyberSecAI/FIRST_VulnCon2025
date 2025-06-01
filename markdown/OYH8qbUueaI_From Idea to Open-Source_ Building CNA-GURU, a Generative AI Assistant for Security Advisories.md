# From Idea to Open-Source_ Building CNA-GURU, a Generative AI Assistant for Security Advisories

**Video URL:** [https://www.youtube.com/watch?v=OYH8qbUueaI](https://www.youtube.com/watch?v=OYH8qbUueaI)
**Video ID:** OYH8qbUueaI

---

SUMMARY
Ryan, AWS security outreach tech lead, discusses ChatCVE, an AI assistant for vulnerability assessments and its development.

IDEAS
* Repetitive tasks are tiresome and difficult to scale effectively for teams.
* New CNA directives in 2024 require scaling vulnerability assessments.
* ChatCVE helps security teams perform vulnerability assessments efficiently.
* It's nicknamed CNA Guru and ChatCVE, thanks to Chris Ferris.
* Scoring vulnerabilities is challenging, and training humans is even harder.
* The tool aims to lower the barrier to entry for CNA-type work.
* It helps those with less experience perform above their weight class.
* The initial version used AWS Labs examples and CDK in Python.
* The goal was a portable, easy-to-deploy, natural language processing tool.
* Users input vulnerability descriptions in their own words.
* A custom prompt searches a knowledge base with context.
* The knowledge base uses public data from sources like C.WE.
* The tool links natural language with the knowledge database.
* LLMs tend to favor lower-level CWEs, while humans prefer higher-level ones.
* Contextual follow-up questions are crucial for vulnerability analysis.
* The tool empowers humans, not replaces them, in decision-making.
* It reduces repetitive training time and effort for analysts.
* Analysts become less hesitant to ask questions with the tool.
* The tool helps build better questions through context and understanding.
* Accuracy is a concern, but guidelines and prompts mitigate hallucinations.
* Engagement time decreased significantly with the tool's use.
* A small sample size showed 90% accuracy in scoring CVEs.
* Fine-tuning the prompt is necessary for specific contexts and needs.
* The tool's evolution involved cost reduction and portability.
* Jupyter Notebook makes the Esquire version highly portable.
* Open-sourcing allows community adoption and contribution.
* The tool facilitates security advisory creation and training.
* It supports quality assurance by providing a second opinion.
* The tool promotes knowledge sharing and collaboration.
* It aims to make information retrieval natural and user-friendly.

INSIGHTS
* Automation of repetitive security tasks improves scalability and efficiency.
* ChatCVE empowers security analysts by lowering the barrier to entry for complex tasks.
* Contextual follow-up questions are key to effective vulnerability analysis and training.
* The tool enhances human decision-making by providing quick access to relevant information.
* Balancing accuracy and cost is crucial in developing AI-driven security tools.
* Prompt engineering and knowledge base customization are essential for optimal performance.
* Open-sourcing fosters community engagement and accelerates tool development.
* The tool addresses the growing need for scalable and accessible security training.
* AI assistance can improve the quality and speed of security advisory creation.
* Human expertise remains essential, with AI serving as a powerful assistant.

QUOTES
* "Scoring vulnerabilities is hard and uh training humans is harder." - Ryan
* "This is not a replacement for humans." - Ryan
* "LLMs tend to go lower down on the parent lineage for C.WE." - Ryan
* "This is about offering assistance and help to people." - Ryan
* "In fairness, most engineers I work with hallucinate." - Ryan
* "We don't let this AI drink during work hours." - Ryan
* "Your mileage may vary." - Ryan
* "Sharing is caring." - Ryan
* "This is not a solution to replace humans." - Ryan
* "The goal of the tool is to make it easier for humans to find the information they need to make informed decisions faster." - Ryan
* "You're not asking people to read a book. You're not asking them to Google stuff." - Ryan
* "That lowers the bar to entry especially for non-technical users." - Ryan

HABITS
* Continuously seeks ways to improve quality of life and efficiency.
* Builds tools to automate repetitive tasks and scale processes.
* Leverages existing resources and examples for rapid prototyping.
* Iteratively tests and refines tools based on user feedback.
* Analyzes user prompts to identify common misconceptions and training needs.
* Tunes prompts to optimize tool performance and context.
* Prioritizes user experience and ease of use in tool design.
* Encourages open-source contribution and community adoption.
* Focuses on empowering humans with information, not replacing them.
* Values knowledge sharing and collaboration within the security community.

FACTS
* New CNA directives in 2024 impact vulnerability assessment practices.
* Training humans on complex security skills is time-consuming and challenging.
* LLMs exhibit different CWE selection patterns compared to humans.
* Effective vulnerability descriptions are crucial for accurate scoring.
* Small sample size analysis showed 90% accuracy for the tool.
* Cost can be a barrier to adopting valuable security tools.
* Serverless technology offers scalability but can be expensive.
* CDK is a complex infrastructure-as-code language from AWS.
* Jupyter Notebook enhances portability of AI tools.
* Open-sourcing allows free access and customization of tools.

REFERENCES
* Chatbot to help security teams perform vulnerability assessments (GitHub repo)
* CNA Guru (nickname)
* Chat CVE (nickname)
* Vulcon (security conference)
* NVD (National Vulnerability Database)
* C.WE (Common Weakness Enumeration)
* CVSS (Common Vulnerability Scoring System)
* GHSA (GitHub Security Advisory)
* AWS Labs examples
* CDK (Cloud Development Kit)
* Python (programming language)
* Streamlit (open-source chat framework)
* ECS (Elastic Container Service)
* Docker (containerization platform)
* AWS Fargate (serverless compute engine)
* Bedrock (Amazon AI platform)
* Jupyter Notebook (interactive computing environment)
* CNA Guru Jr. (stripped-down version)
* CNA Guru Esquire (Jupyter Notebook version)
* AWS blog post explaining the project

ONE-SENTENCE TAKEAWAY
ChatCVE assists security analysts by automating vulnerability assessments and providing contextual knowledge.

RECOMMENDATIONS
* Automate repetitive security tasks to improve efficiency and scalability.
* Use ChatCVE to streamline vulnerability assessments and empower analysts.
* Focus on contextual follow-up questions for effective training and analysis.
* Leverage AI assistance to enhance human decision-making in security.
* Customize prompts and knowledge bases to optimize tool performance.
* Embrace open-source tools and contribute to community-driven development.
* Prioritize user experience and ease of use when designing security tools.
* Consider cost implications when adopting new security technologies.
* Explore different AI models and platforms for specific security needs.
* Promote knowledge sharing and collaboration within the security community.
* Use ChatCVE to create security advisories and improve quality assurance.
* Leverage the tool for training and supporting security analysts.
* Explore the flexibility and extensibility of ChatCVE for various use cases.
* Integrate ChatCVE with chat platforms like Slack for enhanced collaboration.
* Use the tool to generate drafts and gather missing information for CVEs.
