 # **Improving the knative eventing onboarding experience (proposal)** 


<img src="https://knative.dev/docs/images/logo/rgb/knative-logo-rgb.png" alt="Google Cloud" width="120" height="100">





***


## Abstract:<a id="abstract"></a>

The **complexity** of knative eventing coupled with technical documentation, creates significant challenges for new users during the onboarding process. This user research project purposes a multi-pronged approach to identify these barriers and develop actionable recommendations to improve the **user experience** and promote sustained engagement within the knative eventing community. Through interviews with **new**, **current**, and **past users**, along with scenario-based activities and document reviews, the project aims to gain a comprehensive understanding of user pain points. The ultimate goal is to produce a **report** detailing the end-user journey and propose concrete steps, such as enhanced onboarding content, to streamline the process and foster a more welcoming environment for new knative eventing adopters.

![knative eventing7 drawio](https://github.com/UtkarshUmre/improving-knative-eventing-onboarding/assets/112888849/0ba9310a-2b26-44a6-9509-2a78350fdb70)




The diagram visually depicts the developer’s thought process. Initially, they see the benefits of EDA (scalability, flexibility), but manual implementation leads to complexity  and limited scalability. Knative Eventing offers a solution with a central broker, simplifying event routing and improving scalability. Onboarding involves shifting from custom code to leveraging knative’s components.


# Research Goals:<a id="research-goals"></a>

1. **Understand User Pain Points:**  this research aims to identify the specific challenges faced by new users during the Knative Eventing onboarding process. This includes pinpointing areas of confusion in the documentation, difficulties with setup and configuration, and knowledge gaps related to EDA concepts within Knative Eventing.

2. **Evaluate Documentation Effectiveness:** we will assess the clarity, comprehensiveness, and user-friendliness of existing Knative Eventing documentation and tutorials. This involves identifying areas where the documentation might be lacking or overly technical, hindering user understanding.

3. **Explore User Background and Expectations:** we plan to understand the prior experience level and expectations of new Knative Eventing users. This includes their familiarity with EDA concepts, cloud-native technologies, and their overall goals for utilizing Knative Eventing.

4. **Measure User Engagement and Retention:** This research will investigate the factors that contribute to user engagement and retention after onboarding. We will analyze drop-off points in the onboarding journey and explore ways to encourage continued exploration and use of Knative Eventing features.

5. **Identify Opportunities for Improvement:** Based on the research findings, we will pinpoint specific opportunities to improve the Knative Eventing onboarding experience. This could include recommendations for developing new documentation formats (e.g., interactive tutorials, video guides), streamlining specific  configuration steps, or enhancing existing resources with clarity and user-friendliness in mind. 


# Research Methods:<a id="research-methods"></a>

This user research project will leverage a combination of qualitative and quantitative methods to gain a comprehensive understanding of the Knative Eventing onboarding experience for new users. Here’s a breakdown of some potential methods we can employ.

- **Qualitative methods:**

1. **Semi-structured interviews:** we will conduct in-depth interviews with a diverse group of participants, including:

   - New users who are just starting with knative eventing.

   - Current users who have recently onboarded.

   - Past users who may have encountered difficulties and discontinued use.

   In-depth interviews with a diverse group of participants will allow us to explore their experience in detail. Open-ended question will encourage them to share their thoughts, feelings, and specific challenges encountered during 
   onboarding.
   

    -  **Why:** allows for in-depth exploration of user experiences, challenges, and suggestions beyond pre-defined questions. Participants can elaborate on their thoughts and feelings.

    -  **Suggested tools:** Zoom, Google Meet for interviews with predetermined questions.
  


2. **Scenario-based Activities:** During interviews, we can present participants with common onboarding tasks and ask them to think aloud as they navigate the process. This will help us identify specific pain points and areas for improvement within the documentation or user interface

    - **Why:** Reveals pain points and areas for improvement by observing users navigate common tasks while verbalizing their thought process

    - **Suggested tools:** Screen recording software, online prototyping tools.

3. **Card Sorting:** This technique can be used to assess the organization and labelling of existing knative eventing resources. Participants will sort cards representing documentation topics or features based on their own understanding, revealing any inconsistencies or lack of clarity.

   -  **Why:** Helps understand how users categorize information within knative eventing documentation, revealing potential improvements in organization and structure.

   - **Suggested tools:** Online card sorting tools like OptimalSort & Maze

4. **Usability Testing:** We can observe participants as they attempt to complete specific tasks using the knative eventing platform or documentation. Observing their behavior and identifying points of frustration can highlight areas for improvement in the user experience.

   - **Why:** Provides direct observation of user interaction with knative eventing documentation and tutorials, uncovering confusing elements or missing information.

   - **Suggested tools**: Usability testing platforms like UserTesting.com, Lookback.io

5. **Social media listening:** We can monitor online communities and social media platforms for discussions related to knative eventing onboarding. This can provide valuable insights into user experiences and sentiment, even if users haven’t directly participated in the research project.

   -  **Why:** Provides insights into user sentiment and common pain points associated with knative eventing onboarding by analyzing online discussions and comments.

   - **Suggested tools:** social listening platforms like sprout social

* **Quantitative methods:**

1. **Surveys:** Online surveys can be distributed to a wider audience to gather broader quantitative data on user experiences. This can provide insights into user demographics, prior knowledge levels, and the prevalence of specific challenges during onboarding. 

    - **Why:** Allows gathering broader user feedback from larger audience, providing quantitative data to supplement qualitative interview insights.

    - **Suggested tools:** Survey platforms like SurveryMonkey, Google Forms

2. **Clickstream Analysis:** if applicable, analyzing clickstream data can reveal user navigation patterns within the knative eventing documentation or platform. This can identify areas where users frequently get stuck or encounter confusion, requiring potential revisions to the user interface or content flow.

    - **Why:** This data reveals user journey, identifies areas of confusion or difficulty, and help you optimize the overall user experience.

    - **Suggested tools:** Apache Clickhouse, Piwik Pro.

3. **A/B Testing:** This technique could be used to test the effectiveness of different onboarding approaches. By presenting different versions of instructions or documentation layouts to separate user groups, we can measure which method results in higher comprehension and task completion rates.

   -  **Why:** Continuously improve user experience by iteratively testing and improving elements based on A/B testing results, we can continually enhance the user experience.

   - **Suggested tools:** Google Optimize, Optimizely.

* **Additional considerations:**

1. **Data Analysis:** We will employ appropriate qualitative and quantitative data analysis techniques to extract meaningful insights from the research data. This may involve thematic analysis for interviews transcripts,  statistical analysis for survey data, and user journey mapping for combined findings.

   - **Why:** Data analysis involves collecting, cleaning, transforming, and interpreting data to extract meaningful insights. This data can come from various sources, including clickstream analysis, A/B testing results, user surveys, and social media analytics.

   - **Suggested tools:** Spreadsheets like Microsoft Excel and Google Sheets, data visualization tools like Tableau and Power BI, Programming languages like R and Python with data analysis libraries like pandas, NumPy in Python.

2. **Pilot Testing:** Before conducting full-scale research activities, it’s valuable to pilot test interview questions or survey instruments with a small group of participants. This allows us to refine the research tools for optimal clarity and effectiveness.

   -  **Why:** Pilot testing involves conducting a small-scale version of a larger project to identify potential issues, refine approaches, and gather initial feedback before full implementations.

   - **Suggested tools:** collaboration tools like figma and invision for sharing and testing UI prototypes, Email marketing platforms like mailchimp and constant contacts for pilot testing marketing campaigns.

3. **Comparative research**: By analyzing how alternative solutions approach onboarding, we can identify best practices and potential areas for differentiation in knative eventing’s onboarding journey. We will compare knative eventing with the other event driven solutions like cncf landscape alternatives e.g. apache kafka & pulsar, cloud specific eventing services, standalone message brokers and serverless workflow frameworks.

   - **Why:** comparative approach helps us identify best practices & improvement opportunities in knative eventing onboarding.

   - **Suggested tools and methodology**: comparative analysis matrix & heuristic evaluation, develop a matrix that compares knative eventing with alternative solutions across key dimensions relevant to onboarding, such as:

        * Documentation clarity & comprehensiveness.

        * Availability of tutorials and guides

        * Community support & resources

        * Ease of setup and configuration

By utilizing a combination of these research methods, we can gain a comprehensive understanding of the knative eventing onboarding experience from the user’s perspective. This will allow us to develop actionable recommendations that address key pain points and ultimately enhance user experience and user engagement with the platform.

![research-method2 drawio](https://github.com/UtkarshUmre/improving-knative-eventing-onboarding/assets/112888849/72e3ec79-4818-4869-a15c-09e26ccd952a)



<!-- ![](https://lh7-us.googleusercontent.com/r8wohHcjvKa_5bz_zFEa1orl2f3a6cqzPvDZkU04Lj21cKCQI_M2SNhSgG2qtpmx365BcZEVrzRunpuYtR4oVCRgrzMOa_JW5PvmmW0fZwKr_kLVLs--cS6zPqIRRA_v0N2onSJP42CMee4OGwwiPx8) -->

Our research will leverage a powerful combination of qualitative & quantitative data analysis to uncover valuable user insights. By synthesising data from various methods (interviews, surveys, etc.) we can identify patterns, trends & correlations that would be difficult to see in isolation.

- Quantitative analysis: we’ll utilize statistical software libraries in python to analyze numerical data from surveys. This helps us identify trends and measure the impact of different factors on the onboarding experience.

- Qualitative analysis: for data from interviews and user testing, we’ll employ thematic analysis, a systematic approach to identify recurring and user perspectives.

These combined analyses will inform the development of well-founded recommendations and suggestions for the final report. This approach ensures that our recommendations are not only informed by user experiences but also supported by evidence and data patterns.

**Note:** This knative eventing onboarding research  project will employ and iterative approach. This means we will continuously refine the research methods as we progress. This allows us to ensure a comprehensive investigation into critical areas related to improving the user onboarding experience. We can adapt the research process as needed to delve deeper into key aspects that emerge during the research.

1.  Collaborative selection of research methods

   - The proposed list of research methods serves as a starting point, and final selection will be made in collaboration with mentors during the initial mentorship phase. This collaborative approach ensures that the overall research structure is optimized to effectively meet the project’s objectives.

2. Additional tools to enhance research

    - Beyond the core research methods, we may utilize various tools to support the research process:

    - Digital whiteboard platforms like Figma or micro can facilitate brainstorming sessions

    - Research repository management, we can leverage tools like notion or google docs to manage and organize the research repository, ensuring all collected data, notes and findings are well documented and easily accessible

    - Prototyping and design, if necessary, figma can be used for prototyping and designing potential improvements to the onboarding experience based on research findings.

    - Data management & analysis: google sheets is a strong candidate for data storage due to its compatibility with python libraries for data analysis on CSV files. It also allows for easy collaboration and offers basic data analysis capabilities itself.

By employing an iterative approach and working collaboratively with mentors to refine the research methods, we ensure the project remains focused and delivers valuable insights to improve knative eventing onboarding experience. The selected tools will further enhance the research process by facilitating brainstorming, managing information and potentially prototyping solutions based on our findings.

<!-- ![](https://lh7-us.googleusercontent.com/GUQK3BTYGSdzOdJKwYJeMy83-llIgeWXmrWWIy4Bl4iOMKqfhIz7Ef-ROzn5lF8IBWyCe3LPN4ggFSI_xVemE401iv6ZuuW3CElh4fdZGD8ixBcOOHp9aDjrFv-LJKJkie5ydToBcS8SA4yCHBSfnps) -->
<!-- ![tools-to-be-used drawio](https://github.com/UtkarshUmre/improving-knative-eventing-onboarding/assets/112888849/15cdadda-7a0f-497e-bf27-1cb0a91c6fad) -->
  ![tools-Diagram drawio](https://github.com/UtkarshUmre/improving-knative-eventing-onboarding/assets/112888849/24a21bfc-a273-4af9-8c36-c54c293c29fc)



# Key Performance Indicators:<a id="key-performance-indicators"></a>

1. **User Experience (UX) Improvement:**

   - **Reduction in time to complete onboarding**: track the average time it takes for new users to complete the onboarding process (e.g. through tasks & surveys) and measure improvement after implementing recommendations.

   - **Increased user confidence**: conduct surveys and user interviews before and after implementing changes to measure user confidence in using knative eventing after completing onboarding.

   - **Improved user satisfaction**: utilize surveys and user interviews to gauge user satisfaction with the onboarding process after implementing changes.

2. **Engagement & Retention:**

   - Reduced user drop-off rate: identify points in the onboarding process where users abandon & measure the decrease in drop-off rate after implementing recommendations.

   - Increased community participation: Monitor participation in knative eventing forums. Discussions and meetups to see if there’s a rise in user engagement after onboarding improvements.

3. **Knowledge and skill development:**

   - **Improved user knowledge assessment:** developing a pre & post onboarding knowledge assessment to measure the increase in user knowledge about knative eventing concepts after completing the onboarding process.

   - **Increased completion of tutorials & documentation:** tracking the number of users who complete existing tutorials & documentation sections related to onboarding & measure growth after implementing changes**.**

   - **Reduced need for support:** monitoring the number of support tickets and forum posts related to onboarding issues and measures the decrease after implementing recommendations.

4. **Additional consideration:**

- **User-centric KPIs:**

   * Depth of user insights

   * Improved user sentiment

   * Increased user engagement

- **Onboarding process effectiveness KPIs:**

   * Completion rate of onboarding tutorials

   * Reduced time to complete onboarding

   * Number of support tickets

   * Participant outreach

- **Overall project success KPIs:**

   * Number of participants

   * Actionable recommendations

   * Project timeline

- **Knowledge dissemination and impact**

   * Report quality

   * Community engagement

   * Implementation rate

By incorporating these KPIs we can demonstrate the project’s potential impact on our user experience, user engagement, and skill development.

# How will I recruit participants for this user research project ?<a id="how-will-i-recruit-participants-for-this-user-research-project-"></a>

I will reach out to both users and developers who are currently using or interested in using Knative Eventing. Already, I have begun receiving responses from new, past, and current Knative Eventing users. This proactive outreach approach ensures a substantial number of interviewees for the user research project.

**Here are the steps I've taken:**

- Firstly, I have contacted organizations currently using Knative Eventing via email and social media platforms like LinkedIn and Twitter.

*  Additionally, I've engaged with online forums and the Knative Slack channel for outreach.

-  However, these methods are not exhaustive. I plan to attend CNCF events in my country, such as the Kubernetes Birthday Bash in June. This event will attract key figures, including maintainers and representatives from organizations like VMware, which I noticed in the adopters file is a Knative Eventing user.

  

![new-social-media drawio](https://github.com/UtkarshUmre/improving-knative-eventing-onboarding/assets/112888849/6ca75cb6-48a3-4ea2-990d-48011587c3b6)





I am actively seeking out users and developers who are discussing Knative Eventing across various platforms. My plan is to utilize every available resource to reach out to them for recruitment purposes. This includes engaging with online forums, official mailing lists, and any other relevant communities where these discussions are taking place. By tapping into these diverse platforms, I aim to connect with a wide range of individuals who can provide valuable insights for my research. This comprehensive approach ensures that I can gather a robust pool of participants for the project. To summarize, I will recruit participants through various channels: Knative and CNCF Slack channels, current Knative users from the adopters file, Twitter and LinkedIn outreach,and participation in tech events in India to engage with potential participants directly.





 # Timeline: [gantt chart](https://www.figma.com/board/Z1DsiE5V8G99v5gin8HUGs/Improving-the-knative-eventing-onboarding-experience?node-id=1-345&t=y5mm5kjNtTRxshAj-1)







To ensure optimal progress, the project will follow the 12-week LFX mentorship program structure. Here’s a breakdown of the planned activities.





| Week       | Activity                                                                                                                  |
|------------|---------------------------------------------------------------------------------------------------------------------------|
| Week 1 - 2 | Determine the research scope, choose the methods, and design comprehensive interview and survey questions.                |
| Week 3 - 4 | Commence Research! - Conduct interviews and discussions (focus groups), administer surveys, and gather valuable data.     |
| Week 5 - 7 | Examine the collected data, identify trends, carry out studies, and draft a preliminary report.                           |
| Week 8 - 9 | Work with mentors to develop actionable recommendations, refine the report, and conduct follow-up interviews or studies.  |
| Week 10    | Share the findings with the Knative community and make necessary adjustments based on feedback.                           |
| Week 11    | Refine the report based on community feedback, finalize implementation plans, and address any outstanding issues.         |
| Week 12    | Share the finalized report with the community, ensuring clarity and comprehensiveness.                                    |
| Post mentorship | Collaborate with the Knative Eventing community to evaluate the research's efficacy and plan for future enhancements.|




## Ethical concerns and considerations:
- [x] Informed Consent: Ensure all participants provide informed consent and understand the research purpose.
- [x] Data Security and Anonymity: Protect participant data, comply with privacy regulations, and anonymize data in the final report to maintain participant privacy.
- [x] Transparency: Clearly communicate research goals, methodologies, and results to mentors and stakeholders.
- [x] Respectful Representation: Accurately and respectfully represent the Knative community in the final report, avoiding biases.\
- [x] Feedback Incorporation: Prioritise feedback form mentors and the community throughout the research process.
- [x] Tool Selection: Evaluate the Privacy policies and data handling protocols of recommended research tools, selecting those that prioritise user and research data security and comply with ethical standards.  




## Why me for this project
I am genuinely grateful for the potential impact this opportunity could have on my personal and professional growth. I see myself as an ideal candidate for the "Improving Knative Eventing Onboarding" project due to my  knowledge in areas such as Kubernetes, cloud-native development, and Knative fundamentals. My commitment to continuous learning ensures that I can swiftly identify pain points during user research. Moreover, my strong communication skills, honed through engagements with tech communities, make me adept at understanding and addressing user needs. 

I have already taken proactive steps to reach out to potential candidates for interviews, and I am encouraged by the positive feedback received thus far. Through engagement with Knative online forums, Slack channels, and direct contact with current users listed in the adopters file, I have initiated meaningful conversations that will enrich my research. This early interaction underscores my commitment to gathering diverse perspectives and ensuring that the user research process is comprehensive and insightful. My flexibility and enthusiasm to contribute to the Knative community through this mentorship program underscore my suitability for the role.

My primary drive is to work hand-in-hand with the community, addressing user needs and propelling project success. This opportunity not only assures skill enhancement but also fosters learning from industry leaders and peers, while allowing me to impart my knowledge and insights. I am confident in executing this proposal effectively, making a significant contribution to the project. Furthermore, I am enthusiastic about closely collaborating with the community to tailor solutions to users' needs and drive project success. This program offers an excellent chance to receive mentorship, engage with a global community, and effect positive change. Participating will not only enhance my skills but also facilitate learning from peers and mentors, fostering knowledge sharing. These factors collectively position me as a compelling candidate for this program, demonstrating my capability to execute this proposal effectively.

## Closing Thoughts and Beyond the Mentorship:

In summary, this research proposal outlines a comprehensive plan to enhance the Knative Eventing onboarding experience. It will address current challenges, delve into developer and organizational motivations, and identify factors contributing to attrition. The approach, encompassing interviews, discussions, surveys, data collection, analysis, and a comparative study, is designed to provide actionable insights.

My commitment extends beyond ethical research practices, transparency, and fostering active community engagement. Through an iterative approach, I aim to deliver a final report with concrete recommendations based on user research. This report will highlight areas for improvement in the current onboarding journey within Knative eventing, ultimately promoting a collaborative environment that facilitates seamless onboarding and fosters sustained contributions!

### Looking Ahead: A Continued Journey With Knative

Even beyond the LFX Mentorship program, my passion for Knative extends far beyond this initial user research project. Upon successful completion, I envision myself continuing to contribute in various ways. This could involve further refining the Knative Eventing onboarding process, enhancing Knative documentation and designs to address user needs, or exploring opportunities to improve other aspects of the Knative ecosystem. If there are functionalities left unimplemented by the project's conclusion, I'll take the initiative to tackle them independently.

Furthermore, I see myself as a permanent fixture within the Knative community. I plan to stay actively involved by following project discussions and developments, and offering my contributions whenever possible. Regardless of the mentorship program's scope, I'm enthusiastic about engaging in conversations with the community to broaden my knowledge and gain exposure to novel technologies and ideas within the Knative world.

										
						                                                                                                                                                                                                                                                                  
                                                                                                                                                                                                                                                                              
                                                                                                                                                                                                                                                                     
   
							                                                  










