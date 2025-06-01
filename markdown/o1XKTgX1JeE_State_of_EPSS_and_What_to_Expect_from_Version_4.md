# State of EPSS and What to Expect from Version 4

**Video URL:** [https://www.youtube.com/watch?v=o1XKTgX1JeE](https://www.youtube.com/watch?v=o1XKTgX1JeE)
**Video ID:** o1XKTgX1JeE

---

**SUMMARY**
Jay presents data visualizations on EPSS, a predictive model estimating the probability of vulnerability exploitation, emphasizing feedback, objective information, and continuous improvement, while addressing challenges and future directions.

**IDEAS:**
* The absence of feedback loops in security decisions can lead to ineffective measures, highlighting the importance of data-driven approaches.
* EPSS is built on observed exploitation activity with timestamps, offering a dynamic and measurable approach to predicting vulnerabilities.
* Measuring the accuracy of predictive models through precision and recall, termed efficiency and coverage, is crucial for vulnerability management.
* Prioritizing vulnerabilities based solely on CVSS scores may result in inefficient remediation efforts, indicating the need for more nuanced approaches.
* Integrating threat intelligence feeds like Exploit DB and Metasploit can enhance vulnerability prioritization and improve remediation efficiency and coverage.
* EPSS aims to outperform CVSS in predicting exploitation activity, acknowledging CVSS wasn't designed for prediction, but expecting some correlation.
* Early EPSS versions were outperformed by Metasploit and KEV, highlighting the iterative nature of model development and the importance of continuous improvement.
* Centralizing data collection and leveraging APIs can significantly enhance the scalability and effectiveness of vulnerability prediction models.
* Overfitting can cause a model's performance to degrade over time, underscoring the need for regular retraining and validation with new data.
* Incorporating diverse data sources, such as malware analysis and network activity, can improve the accuracy and robustness of vulnerability prediction.
* The arbitrary nature of the 30-day prediction window in EPSS suggests flexibility in adapting the model to different planning horizons.
* The model doesn't know what category the features are in, but the presenter uses categories to understand the data better.
* Only a small fraction of published vulnerabilities have known exploitation activity, highlighting the challenge of identifying and prioritizing real threats.
* The presence of false positives in exploitation data necessitates careful filtering and validation to avoid misassociation and inaccurate predictions.
* The goal is to move vulnerability management to the upper right, increasing both efficiency and coverage in remediation efforts.
* The presenter was told that they were treating the KEV wrong, which led to a new way of thinking about the data.
* The presenter created a plot to show the real problem, which is picking out the vulnerabilities that need to be addressed.
* The presenter thinks that both the KEV and EPSS are accurate, but that EPSS is missing data.
* The presenter wants to compare EPSS to other methods, not just say that EPSS is the best.
* The presenter thinks that the joy of this is that this is not none of this model is a conscious effort.
* The presenter thinks that the model is really complex, and that there will be some weird things that happen.
* The presenter thinks that the KEV is a big thing, and that it is known to hackers.
* The presenter thinks that the model is tuned, but the variables themselves are not tuned.
* The presenter thinks that the algorithm is really complex, and that there is a lot of stuff in there.

**INSIGHTS:**
* Data-driven security requires continuous feedback loops to refine decisions, moving beyond gut feelings to objective, measurable outcomes.
* Effective vulnerability management hinges on balancing effort, efficiency, and coverage, optimizing resource allocation for maximum risk reduction.
* Combining diverse data sources and threat intelligence enhances predictive accuracy, providing a more comprehensive view of the threat landscape.
* Transparency and continuous improvement are essential for building trust in predictive models, acknowledging imperfections and striving for better performance.
* The value of a predictive model lies not in its perfection, but in its ability to outperform existing methods and inform better decisions.
* The model is only as good as the data that is fed into it, so it is important to have good data.
* The model is not perfect, but it is better than nothing, and it is constantly improving.
* The model is complex, and there are many factors that go into it, so it is hard to understand.
* The model is a tool, and it should be used as a tool, not as a replacement for human judgment.
* The model is a work in progress, and it will continue to evolve as new data becomes available.
* The model is a reflection of the real world, and the real world is messy and complicated.
* The model is a way to make sense of the messy and complicated real world.
* The model is a way to prioritize vulnerabilities and focus on the ones that are most likely to be exploited.
* The model is a way to improve security and reduce risk.
* The model is a way to make better decisions about security.

**QUOTES:**
* "Oh, I don't know. We didn't look we didn't we didn't look at any of that." - CISO
* "It's not built on what we feel would be a bad thing or what we consider to be risk or risky or whatever. It is built on objective information." - Jay
* "Again, what APSS is predicting, it's a predictive model, and it's estimating the probability...of exploitation activity being observed in the next 30 days." - Jay
* "These are typically things caught by security devices, IPS, IDS, honeypotss, malware detections, malware analysis." - Jay
* "Past results are not guaranteed that in the future they're not going to figure out finally how to exploit it." - Audience Member
* "After years of studying, I figured out it's because probability is unintuitive and and and difficult." - Professor of Risk Studies
* "If you want to point out how bad EPSS is, then do something like this. Like you could talk about it like this." - Jay
* "We want to compare. So what I did is I created that same coverage and efficiency plot and I said what if sysv was our ground truth?" - Jay
* "So it's pretty interesting I think to think about that and conversely no when it's not on there generally it's no impact act it's at zero." - Jay
* "So people will have an easier time understanding why a certain CV got a certain EPSS score to publish why like the change in the variable." - Audience Member
* "When the weatherman says you've got a 50% chance of rain do you go call him and be like why you know why why do you think I need umbrella." - Jay
* "We are continually searching for exploitation activity. So, if anybody either has at their company or they're buying it from somewhere or they have some secret sauce that they know about, we would love to talk to you." - Jay
* "There is a really really strong correlation between exploit code being published and available and activity." - Jay
* "Do we just disable it all or you know? But yeah. So it's got got a question back here." - Jay
* "We're going to keep EPSS exactly as it is, even better because we got commercial data." - Jay

**HABITS:**
* Prioritizing remediation efforts based on a combination of factors, not solely relying on CVSS scores or individual metrics.
* Continuously seeking feedback and incorporating diverse data sources to improve the accuracy and reliability of predictive models.
* Regularly retraining and validating models with new data to prevent overfitting and ensure sustained performance over time.
* Maintaining transparency and openly communicating the limitations and uncertainties of predictive models to build trust.
* Focusing on percentile rankings to prioritize vulnerabilities based on relative risk within the entire CVE landscape.
* Actively engaging with the security community and incorporating external research to validate and refine the model.
* Factoring in the age of vulnerabilities when assessing risk, recognizing that older vulnerabilities are often more frequently exploited.
* Monitoring the number of references to a vulnerability as an indicator of its importance and potential for exploitation.
* Using a log scale to accurately represent and interpret probability data, avoiding distortions caused by linear scales.
* Calibrating probability outputs to ensure that predicted probabilities align with observed exploitation frequencies.
* Isolating and analyzing the influence of individual variables to understand their contribution to the model's predictions.
* Acknowledging and addressing false positives in exploitation data to improve the accuracy of the model.
* Actively searching for new sources of exploitation activity to enhance the model's coverage and reduce false negatives.
* Openly discussing the challenges and limitations of the model to foster a collaborative approach to vulnerability management.
* Using data visualizations to effectively communicate complex information and insights to stakeholders.

**FACTS:**
* Disabling USB thumb drives in a large enterprise did not lead to measurable improvements in security, highlighting the need for data-driven decisions.
* EPSS is built on observed exploitation activity, recorded with timestamps, making it dynamic and responsive to emerging threats.
* Precision and recall, also known as efficiency and coverage, are key metrics for evaluating the accuracy of vulnerability management efforts.
* Only about 6% of all published vulnerabilities have known exploitation activity, underscoring the challenge of prioritizing real threats.
* The number of known exploited vulnerabilities is 13 times greater than what is currently on the CISA KEV list.
* The first version of EPSS was designed to be implemented in a spreadsheet, highlighting the initial constraints and subsequent advancements.
* Version 2 of EPSS incorporated over a thousand features, showcasing the evolution towards more complex and data-rich models.
* Overfitting can cause a model's performance to degrade over time, necessitating regular retraining and validation.
* Version 4 of EPSS includes malware data, expanding the scope of data sources and improving predictive accuracy.
* The model incorporates data from Shodan, HackerOne, and domain mentions to enhance vulnerability assessment.
* The model categorizes CWEs into 22 categories, providing a more granular and informative analysis of vulnerability types.
* The model incorporates CVSS 4.0 vectors, reflecting the latest standards in vulnerability scoring and assessment.
* The area under each density plot is the same, even though only 6% of vulnerabilities are exploited.
* The number of daily bulk downloads of EPSS data has increased significantly, indicating growing adoption and usage.
* The presenter's company got funding and staffing, and they were able to actually buy some commercial data.
* The presenter added Showdan, Hacker One, and domain mentions to the model.
* The presenter used to just throw the CWE in there, but now they roll all of them up into 22 categories.
* The presenter used to just do CVSS 3.1, but now they have 4.0 coming out.
* The presenter is missing 408 in their data, and clearly sysv with their collection is not seeing everything.
* The presenter created a plot to show the real problem, which is picking out the vulnerabilities that need to be addressed.

**REFERENCES:**
* EPSS (Exploitation Prediction Scoring System)
* USB Thumb Drives
* CISO (Chief Information Security Officer)
* IPS (Intrusion Prevention System)
* IDS (Intrusion Detection System)
* CVE (Common Vulnerabilities and Exposures)
* CVSS (Common Vulnerability Scoring System)
* EPSSV4
* EPSSV3
* EPSSV2
* EPSSV1
* Exploit DB
* ZDI (Zero Day Initiative)
* GitHub
* Nuclei
* Metasploit
* CISA KEV (Known Exploited Vulnerabilities) Catalog
* Intrigue
* Sniper Jails
* Scientia
* Empirical Security
* Shodan
* HackerOne
* CWE (Common Weakness Enumeration)
* Ben Edwards
* Steven Schaefer
* Vongcon
* Slack
* Google
* Oracle

**ONE-SENTENCE TAKEAWAY**
Leveraging data-driven insights and continuous feedback refines vulnerability prediction, enhancing security and resource allocation in a dynamic threat landscape.

**RECOMMENDATIONS:**
* Prioritize vulnerabilities based on EPSS percentile rankings to focus remediation efforts on the most critical and likely exploited issues.
* Integrate diverse data sources, including threat intelligence feeds and malware analysis, to enhance the accuracy of vulnerability predictions.
* Regularly retrain and validate predictive models with new data to prevent overfitting and ensure sustained performance over time.
* Calibrate probability outputs to ensure that predicted probabilities align with observed exploitation frequencies, improving the reliability of risk assessments.
* Focus on improving both efficiency and coverage in vulnerability management, optimizing resource allocation for maximum risk reduction.
* Actively seek feedback from the security community and incorporate external research to validate and refine predictive models.
* Monitor the number of references to a vulnerability as an indicator of its importance and potential for exploitation.
* Use a log scale to accurately represent and interpret probability data, avoiding distortions caused by linear scales.
* Acknowledge and address false positives in exploitation data to improve the accuracy of predictive models and avoid misallocation of resources.
* Actively search for new sources of exploitation activity to enhance the model's coverage and reduce false negatives.
* Openly communicate the limitations and uncertainties of predictive models to foster a collaborative approach to vulnerability management.
* Use data visualizations to effectively communicate complex information and insights to stakeholders, facilitating informed decision-making.
* Consider the age of vulnerabilities when assessing risk, recognizing that older vulnerabilities are often more frequently exploited.
* Tune the model to improve the accuracy of the predictions, and to make sure that the model is not overfitting.
* Improve the model or do something to either include or not include certain variables to improve accuracy.
