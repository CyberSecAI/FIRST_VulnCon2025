# Models and Systems_ How to Think About Vulnerabilities and Artificial Intelligence

**Video URL:** [https://www.youtube.com/watch?v=lCWitnSDELA](https://www.youtube.com/watch?v=lCWitnSDELA)
**Video ID:** lCWitnSDELA

---

SUMMARY
Erica Lincoln discusses AI models and systems, focusing on vulnerabilities, especially prompt injection, and CVE assignment.

IDEAS
* AI models are loosely defined, with generative transformers and LLMs being the current focus.
* LLMs are a small part of AI, but dominate the conversation due to rapid enterprise adoption.
* LLMs predict the next token probabilistically, leading to non-determinism.
* There's no effective way to distinguish between system prompt, context, and user prompt.
* LLMs don't reason, think, or know anything; they make statistical predictions.
* Prompt injection and jailbreaking exploit the alignment process of LLMs.
* Prompt injection is data misinterpreted as prompt instructions.
* Jailbreaking bypasses the safety policies of the model.
* AI-related CVEs fall into vulnerabilities in libraries, applications, and systems.
* Prompt injection vulnerabilities arise from poor controls within AI systems.
* CVE IDs are assigned for products with weaknesses exploitable for security impact.
* Undesirable content without security impact doesn't warrant a CVE ID.
* Model stealing, while possible, doesn't warrant a CVE unless it has a security impact.
* Disclosing system prompts isn't a security vulnerability.
* CVE assignment focuses on system-level impacts, not just model weaknesses.
* Models don't do anything; systems do.
* Lambda layers allow custom code execution within models, potentially introducing vulnerabilities.
* Existing CNA rules are robust for AI-related issues.
* Focus on the attack surface of the deployed system, not just the model.
* Report prompt injections to PSIRT, even if they don't warrant CVEs.
* Join working groups to discuss and contribute to AI vulnerability handling.
* Model poisoning is hard to distinguish from training on low-quality data.
* Assign CVEs for model poisoning only if there's a clear security impact.
* Invisible Unicode characters can disrupt models' tokenization process.
* Consider using similar techniques for active defense against attacker-driven AI.
* Be mindful of potential liability issues when implementing active defense measures.

INSIGHTS
* The current focus on LLMs within AI necessitates understanding their unique vulnerabilities.
* The probabilistic nature of LLMs introduces inherent security risks.
* The lack of separation between control and data planes in LLMs is a key vulnerability.
* Prompt injection and jailbreaking highlight the limitations of LLM safety mechanisms.
* CVE assignment for AI systems requires demonstrable security impact, not just undesirable behavior.
* Model stealing is an inherent risk, but not a vulnerability unless exploited for security gain.
* System context is crucial for assessing the security implications of AI model weaknesses.
* Focus on system-level vulnerabilities when deploying AI models in production.
* Existing security frameworks can be adapted to address AI-related vulnerabilities.
* Collaboration and discussion are essential for navigating the evolving landscape of AI security.

QUOTES
* "LLMs are just one little tiny part of that." - Erica Lincoln
* "There is no effective way to distinguish between these things." - Erica Lincoln
* "LLMs don't reason. They don't actually think. They don't actually know anything." - Erica Lincoln
* "Unfortunately, this is just how LLMs work." - Erica Lincoln, quoting Rich Herang
* "Prompt injection is when data is misinterpreted as part of the prompt instructions." - Erica Lincoln
* "Jailbreaking is when the prompter bypasses the safety policies of the model." - Erica Lincoln
* "Models don't do anything. Systems do things." - Erica Lincoln
* "CVE assignability is usually almost always going to be more concerned with systems than with models." - Erica Lincoln
* "System prompts private or protected information and those people are wrong." - Erica Lincoln
* "Anything that you input to a model, including the system prompt, may be echoed by the model." - Erica Lincoln
* "A lot of the actually exploitable things that we see are very familiar to us." - Erica Lincoln
* "AI models, again, don't think they don't read. They are sand and math." - Erica Lincoln

HABITS
* Drinks water frequently, especially in the morning.
* Learns new things, like shutting off notifications.
* Reads papers and NIST docs to stay informed.
* Attends conferences like PhoneCon to share knowledge.
* Encourages audience participation and questions.
* Follows security experts on social media platforms.
* Actively participates in working groups for CVE and CWE.
* Uses analogies to explain complex concepts.
* Researches and cites CNA rules when discussing CVE assignment.
* Analyzes real-world examples of AI vulnerabilities.

FACTS
* Artificial intelligence is a loosely defined concept with multiple accepted definitions.
* LLMs are a specific type of AI, namely generative transformers.
* LLMs sample probabilistically, leading to non-deterministic outputs.
* There's no separation between control plane and data plane in LLMs.
* NIST has multiple definitions of "vulnerability".
* CVE uses a specific definition of "vulnerability" based on security impact.
* AI systems are software products containing one or more models.
* Agentic systems can take actions without direct human instruction.
* LLMs don't reason, think, or know anything; they make statistical predictions.
* Prompt injection and jailbreaking are common LLM vulnerabilities.
* CVE IDs are assigned based on specific criteria outlined in CNA rules.
* Model stealing is possible but not always a security vulnerability.
* System prompts are not considered private or protected information.
* Lambda layers allow custom code execution within models.
* Invisible Unicode characters can disrupt LLM tokenization.

REFERENCES
* NIST docs
* CVE program
* CVE blog post
* CIA triad
* Large language models (LLMs)
* Generative transformers
* Retrieval augmented generation systems
* Symbolic and logical AI
* Chatbots, ChatGPT
* Control tokens
* Autoregressive transformers
* GitHub
* LangChain
* TensorFlow
* MLflow
* Anyarray
* Ginga templates
* CPE strings
* CWE (Common Weakness Enumeration)
* CWE-1039 (Adversarial Examples)
* CWE-1426 (Improper Validation of Generative AI Output)
* CWE-1427 (Improper Neutralization of Input Used for LLM Prompting)
* CNA (CVE Numbering Authorities) operational rules (section 4.4, rule 4.1.8)
* MITRE AI Risk Database
* AVID (Adversarial Vulnerability Identification Database)
* Hugging Face
* MOU Hacks proof pudding write-up
* CVE-2019-20634 (Proofpoint vulnerability)
* Bluesky social media platform

ONE-SENTENCE TAKEAWAY
Understand AI system vulnerabilities, especially prompt injection, and focus on system-level security impacts.

RECOMMENDATIONS
* Validate LLM outputs to mitigate risks from non-determinism.
* Implement strong controls to prevent prompt injection attacks.
* Treat AI systems as products and assess their attack surface.
* Prioritize system-level security over model-specific weaknesses.
* Follow CNA rules when assigning CVEs for AI vulnerabilities.
* Use MITRE AI Risk Database and AVID to catalog AI weaknesses.
* Join CVE and CWE working groups to contribute to AI security.
* Be aware of model poisoning and its potential security impact.
* Consider lambda layer vulnerabilities when using custom code in models.
* Use invisible Unicode characters for active defense against AI attacks.
* Be cautious of potential liability issues with active defense.
* Educate PSIRT about prompt injections and other AI issues.
* Share knowledge and discuss AI security best practices.
* Continuously learn and adapt to the evolving AI threat landscape.
* Focus on practical security measures for deployed AI systems.
