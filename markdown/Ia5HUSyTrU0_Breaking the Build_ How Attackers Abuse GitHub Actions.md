# Breaking the Build_ How Attackers Abuse GitHub Actions

**Video URL:** [https://www.youtube.com/watch?v=Ia5HUSyTrU0](https://www.youtube.com/watch?v=Ia5HUSyTrU0)
**Video ID:** Ia5HUSyTrU0

---

SUMMARY
Jonathan Evans discusses GitHub Actions security, focusing on three vulnerabilities: expression injection, pipeline execution, and supply chain attacks.

IDEAS
* GitHub Actions automate workflows, including CI/CD, building, testing, and deploying code.
* Workflows are YAML files in .github/workflows with triggers, jobs, and steps.
* Jobs run on runners, either self-hosted or GitHub-provided VMs (Ubuntu, Windows, Mac).
* Each workflow gets a GitHub token determining its API access permissions.
* Pull request triggers can grant read or write access, configurable at workflow/job levels.
* Actions expressions injection involves injecting malicious data into action expressions.
* Use JavaScript actions or intermediate environment variables to mitigate injection risks.
* Poison pipeline execution involves injecting code into the pipeline that gets executed.
* Restrict write permissions to your repository to control pipeline execution.
* Supply chain attacks target dependencies to compromise downstream users.
* Avoid version tags; use full SHA-1 commit hashes for actions.
* Set least privileges at the job level for enhanced security.
* Use OpenID Connect for cloud resources and code scanning actions for workflows.
* OpenSSF scorecards action helps secure workflow dependencies.
* Personal Access Tokens (PATs) should be avoided due to security risks.
* Fine-grained tokens offer better security but require periodic refresh.
* Trust-on-first-use (TOFU) could enhance security by remembering initial commits.
* GitHub Actions may not be secure by default, requiring extra vigilance.
* Misconfigured GitHub Actions are a common source of vulnerabilities.
* The GitHub Advisory Database aggregates advisories from NVD and package registries.
* It enriches advisories with metadata like CVSS, CWEs, affected versions, and products.
* Advisories are published in OSV format and used by Dependabot for vulnerability detection.
* Unreviewed advisories are those not yet verified against supported registries.
* Reviewed advisories have been checked and enriched with additional data.

INSIGHTS
* GitHub Actions' flexibility introduces security risks if not configured carefully.
* User-controlled data in workflows requires careful handling to prevent exploits.
* Least privilege principle is crucial for minimizing the impact of compromised workflows.
* Supply chain attacks highlight the importance of securing dependencies.
* Comprehensive security measures are necessary to mitigate GitHub Actions risks.
* Fine-grained tokens and automated refresh mechanisms can improve security practices.
* Secure by default design would significantly reduce GitHub Actions vulnerabilities.
* Proactive scanning and dependency management are essential for secure workflows.
* The GitHub Advisory Database plays a vital role in the software supply chain security.
* Collaboration between security researchers and platform providers is crucial.

QUOTES
* "GitHub actions are a feature in GitHub that allow you to automate workflows." - Jonathan Evans
* "Every workflow has three elements: a triggering event, one or more jobs, and steps." - Jonathan Evans
* "Every workflow gets a GitHub token; the token determines what permissions that workflow or job has." - Jonathan Evans
* "Obviously, you can't trust that data, so you have to handle that data very carefully within your workflow." - Jonathan Evans
* "The pull request title is controlled by the user." - Jonathan Evans
* "You can use JavaScript actions or intermediate environment variables." - Jonathan Evans
* "Restrict who can actually have write permissions to your repo." - Jonathan Evans
* "Personal access tokens have all of the access from the maintainer." - Jonathan Evans
* "Don't use version tags when you're specifying which action you're using." - Jonathan Evans
* "Use least privileges whenever you can." - Jonathan Evans
* "GitHub has a bunch of code actions that you can use to scan your code to make sure that your workflow is safe." - Jonathan Evans
* "Coinbase appeared to be the target." - Jonathan Evans
* "This seems onerous, like can we make that process easier?" - Professor
* "This is sort of not secure by default at all." - Audience Member
* "We've given the Actions team that feedback, and they've heard it." - Jonathan Evans

HABITS
* Use JavaScript actions to avoid shell interpretation of user inputs.
* Utilize intermediate environment variables to isolate user-provided data.
* Restrict repository write permissions to trusted users and services.
* Avoid using Personal Access Tokens (PATs) in workflows.
* Use fine-grained tokens with shorter expiration times for better security.
* Pin dependencies to specific commit SHAs instead of version tags.
* Set least privileges at the job level to limit potential damage.
* Use OpenID Connect for secure cloud resource access.
* Regularly scan code and workflows for security vulnerabilities.
* Leverage OpenSSF scorecards to assess workflow dependency security.

FACTS
* GitHub Actions can automate CI/CD pipelines, build, test, and deploy code.
* Workflows are defined in YAML files stored in the .github/workflows directory.
* GitHub provides hosted runners for various operating systems.
* GitHub tokens control access to the GitHub API and repository resources.
* Pull request titles are user-controlled and can be exploited for injection attacks.
* Attackers target supply chains to compromise downstream users.
* Personal Access Tokens grant the same level of access as the maintainer.
* Version tags can be modified to point to malicious commits.
* OpenSSF scorecards help evaluate the security posture of dependencies.
* The GitHub Advisory Database provides vulnerability information for various ecosystems.

REFERENCES
* GitHub Actions
* YAML
* CI/CD
* GitHub Token
* JavaScript Actions
* OpenSSF Scorecards
* OpenID Connect
* Dependabot
* NVD
* OSV
* .github/workflows
* Ubuntu, Windows, Mac (VM options)
* Shell metacharacter attacks
* Pull Request triggers
* Personal Access Tokens (PATs)
* Fine-grained tokens
* Trust-on-first-use (TOFU) model
* GitHub Advisory Database

ONE-SENTENCE TAKEAWAY
Secure your GitHub Actions by using least privilege, avoiding PATs and version tags, and scanning code.

RECOMMENDATIONS
* Use JavaScript actions or environment variables to prevent expression injection.
* Restrict write access to repositories to mitigate poison pipeline execution.
* Avoid version tags and use full SHA commit hashes for actions.
* Implement least privilege principle at the job level.
* Utilize OpenID Connect for secure cloud resource integration.
* Regularly scan code and workflows for vulnerabilities.
* Leverage OpenSSF scorecards to secure workflow dependencies.
* Use fine-grained tokens with shorter expirations instead of PATs.
* Consider trust-on-first-use to enhance security by remembering commits.
* Report vulnerabilities to the GitHub Advisory Database.
* Stay informed about GitHub Actions security best practices.
* Review and update workflow permissions regularly.
* Educate developers on secure coding practices for GitHub Actions.
* Implement automated security checks in CI/CD pipelines.
* Monitor workflow logs for suspicious activity.
