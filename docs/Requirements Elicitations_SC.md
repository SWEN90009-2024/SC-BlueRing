# Roles and responsibilities
| Name | Role | Responsibilities |
| --- | --- | --- |
| Hao Guan | Meeting facilitator | Survey members' availability, schedule client meetings, and moderate proceedings. Assist interviewer with questions and provide details.
|
| Tori Li | Interviewer | Gather team members' questions and concerns, organize them for client meetings, and facilitate discussions with clients. |
| Mingchong Li | Meeting recorder | Take meeting notes and record discussions for team review and organization. |

***Roles will be rotated each week within the team.**
# How to get requirements
## Meeting with client
**Meeting type:** Online meeting
**Meeting time:**  Monday, March 18, 2024, 16:00
**Meeting information:**

| Questions | Client's reply | Summary of Requirement |
| --- | --- | --- |
| What are the main objectives of the project? What concrete results do we hope to achieve through this project? | The main objectives of the project are not fully defined by the client themselves; instead, they provided documents and expect the team to understand and derive the objectives based on the provided materials. | The team is expected to analyze the provided documents to understand the project's objectives. Specifically, the project is about the Ruby platform and how teachers make decisions using it. The team may need to investigate how decisions are made and possibly how to improve or expand upon this process. |
| Do different teachers evaluating the same course have different evaluation criteria for the same competency? How should these differences be addressed? | The client confirmed that the issue of different teachers having different evaluation criteria for the same competency is indeed a concern and part of their research question. The exact method of addressing this variance is not provided but is a key interest area for the project. | The project needs to explore how to manage or understand the variance in teachers' evaluation criteria for competencies assessed through the Ruby platform. This may involve research into standardization or accommodation of diverse assessment strategies. |
| What is the meeting schedule for future weeks, and how are decisions regarding the project's direction made? | The client did not have specific information on the meeting schedule or decision-making process. They suggested that these procedural aspects need to be clarified with the mentor. | The teams need to establish a clear communication channel and procedural framework with their mentor for scheduling future meetings and making decisions about the project's direction. |
| Are there any specific deliverables or expectations for this project? | The client indicated that they do not have details on specific deliverables or expectations, as these are likely outlined in the task instructions provided to the team. However, they mentioned that any solution should consider reducing the workload for teachers and researchers, implying a preference for efficient and practical solutions. | While specific deliverables were not detailed by the client, the project should focus on solutions that do not increase the workload for teachers or researchers, and effectively address the research problem concerning how teachers make evaluative decisions on the Ruby platform. |

## Document analysis
### Website provided by clients:
> [https://melbourne-assessment-sample.arcassess.education/app/self-assess/rate/reg/3a0cf5a1-316d-cd06-af3e-fe1f4eedff82/5](https://melbourne-assessment-sample.arcassess.education/app/self-assess/rate/reg/3a0cf5a1-316d-cd06-af3e-fe1f4eedff82/5)
> [https://education.unimelb.edu.au/melbourne-assessment](https://melbourne-assessment-sample.arcassess.education/app/self-assess/rate/reg/3a0cf5a1-316d-cd06-af3e-fe1f4eedff82/5)

### Documents provided by mentor and clients:
![Screenshot 2024-03-22 at 13.04.55.png](https://cdn.nlark.com/yuque/0/2024/png/40721791/1711073105613-bf919207-4bb1-49e7-8c83-c4cf6a1940f4.png#averageHue=%236a9ec8&clientId=u7182eff7-9cb3-4&from=drop&height=280&id=u73a53d11&originHeight=1876&originWidth=1328&originalType=binary&ratio=2&rotation=0&showTitle=false&size=1261906&status=done&style=none&taskId=u6eb617dc-0094-4286-b2bb-b6250ddb528&title=&width=198)![Screenshot 2024-03-22 at 13.05.19.png](https://cdn.nlark.com/yuque/0/2024/png/40721791/1711073126381-3e442858-0130-44b2-99ff-5acce38dd42c.png#averageHue=%23f6f5f5&clientId=u7182eff7-9cb3-4&from=drop&height=282&id=ud2f57f4b&originHeight=1270&originWidth=1122&originalType=binary&ratio=2&rotation=0&showTitle=false&size=507450&status=done&style=none&taskId=u679180c5-7ea6-44f1-a105-ff8994bf36b&title=&width=249)
#### Melbourne Metrics Overview

1. **Current Issue:**

As they move towards high-stakes credentialing, ensuring teachers' consistent understanding and application of assessment items across diverse contexts becomes crucial. They lack insight into the evidence teachers use to judge students' competency levels, especially concerning general capabilities like collaboration.

2. **Ruby Platform for Data Collection:**

An advanced, research-based platform designed to assess complex competencies, supporting a variety of user roles including teachers, students and external assessors. The platform supports flexible assessment scheduling, rubric-based delivery, user portfolio uploads, and detailed reporting capabilities.
#### Assessing Agency in Learning

1. **Content Overview: **

A guide for registered schools to understand and implement assessments of complex competencies, with a focus on agency in learning. It outlines next-generation assessment and reporting, resources for school leaders and teachers, and examples of learner reflection tools.

2. **Competencies and Learning Progressions: **

Detailed descriptions of complex competencies like ethical decision-making, collaboration, communication, and personal development. The document provides an architectural framework for understanding, teaching, and assessing these competencies.
#### Goals

1. **Enhance Consistency in Assessments:**

As the Ruby platform moves towards high-stakes certificate certification, we need to ensure that teachers with different subject backgrounds, different teaching levels and directions have a unified understanding of competency assessment standards.

2. **Deepen Understanding of Competency Evidence:**

Improve understanding of the types of evidence teachers rely on when assessing students’’ abilities to adopt more standardized and transparent assessment methods.
# Strategies

1. Design surveys or questionnaires with specific questions for users or stakeholders to fill out, which helps in gathering a broad range of requirements early on, especially useful for large groups of users.
2. Develop an initial software prototype and let stakeholders try it out, which can reveal unarticulated requirements through their interactions with the prototype and collect their feedback.
3. Take notes during the interviews, record important requirements and summarise them after the meeting in a simple summary of requirements, asking stakeholders and users to confirm that we have understood their requirements correctly.
4. Research similar products or solutions on the market to understand how they meet user needs, which can help identify potential requirements or inspire improvements for the current project idea.
5. Conduct a Strengths, Weaknesses, Opportunities, and Threats analysis(SWOT analysis) of the project to help identify requirements closely linked to project success, which helps the team consider all aspects of the project more comprehensively.
# Observations
## Current system
Ruby leverages expert human judgments from across a learner's educational program to assess growth in competence and represent what a learner knows and can do.
It provides assessment rigor and technical quality, and is built from years of research and project experiences aiming to support many types of users, including system curriculum leaders; school leadership; teachers; students; module designers; external assessors; and stakeholders/parents.
### Teachers answering questions
After starting, a text box will appear in the middle of the screen for teachers to input the student's name. After entering the student's name on the next screen, teachers will be guided to complete 13 questions. The topics of these questions may revolve around agency and learning, collaboration, or any other form of complex competency relevant to schools. The questions will be in the form of multiple-choice, and teachers will need to answer based on their understanding of this student. The last option in each multiple-choice question indicates that the teacher does not understand this aspect of the student. Upon completing these questions, the teacher can obtain a report on the student's performance in that particular area.
### Report generation
The report is called the Learner Competency Report, which uses a Rocket Graph to represent the types of students. The Rocket Graph is divided into multiple sections, and the algorithm rates students based on the questions answered by teachers, placing them into corresponding segments of the rocket, each of which manifests as a particular type. Following the graph, the report provides detailed explanations for each type of student.
## Challenges/problems
### How decision made
A significant challenge is ensuring that teachers’ understanding and interpretation of assessment items is consistent across contexts. The project does not have a clear understanding of the evidence teachers use when judging each student's ability level, raising concerns about the uniformity and fairness of assessment. Teachers may have subjective understandings of abilities in areas such as collaboration, leading to differences in assessments and judgments of student ability levels. This discrepancy poses a risk to the validity and reliability of the certificates issued. As credentialing becomes increasingly risky, inconsistencies in understanding and assessing complex competencies can undermine the credibility of credentials, impacting students’ future opportunities and the reputation of educational institutions.
### Workload on teachers
The project requires significant effort from teachers who use the platform to assess their students. Teachers need to answer questions about students' ability levels, explain learning progress, and handle various reports. As the system continues to evolve to support high-stakes qualifications, its complexity and demands on teachers' time are likely to increase, particularly given the need for more rigorous and nuanced assessments. Increased workload may lead to teacher burnout and a decrease in the quality of assessments. Teachers may rush through assessments due to time constraints or workload pressures, resulting in less accurate or thoughtful assessments of student abilities. Additionally, additional demands may affect teachers' ability to focus on other critical aspects of their role, such as instructional time and support for students, potentially affecting the overall quality of education.
### Accurate
In terms of the Accurate challenge, the main issues faced by the project centered on the consistency of assessment results and how to accurately assess students' complex abilities. There can be significant inconsistencies in assessment results due to the fact that teachers may rely on different evidence when assessing students' competence, as well as individual differences in their understanding and application of the assessment criteria. In particular, the lack of objective and clear criteria and quantitative tools for assessing complex competencies such as Agency and Learning Competencies makes the assessment results largely dependent on teachers' subjective judgements. In addition, when teachers from different disciplinary backgrounds use the same assessment criteria to assess their students, the differences in their professional backgrounds and teaching experiences may also lead to different interpretations of the assessment criteria, thus affecting the accuracy and universality of the assessment. Together, these factors constitute a complex challenge to improving the accuracy of assessments.
