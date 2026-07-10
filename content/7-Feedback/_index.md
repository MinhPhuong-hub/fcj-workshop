---
title: "Feedback and Suggestions"
weight: 7
chapter: false
pre: "<b>7. </b>"
slug: "7-feedback"
---


## General Evaluation

### 1. Working Environment

The internship environment gave me the opportunity to approach Cloud Computing in a more practical way than only reading theory. During the internship, I studied through AWS workshops, compared the lab content with official AWS documentation, and recorded my weekly progress through worklogs. This helped me build a more systematic learning habit: reading documentation, practicing labs, noting encountered issues, and then summarizing the results into content that I could explain.

What I value is that the program did not only require isolated labs, but also required a proposal, an AWS diagram, and a final project. As a result, I had the chance to understand the relationship between individual AWS services and a complete architecture problem.

### 2. Support from Mentor / Admin Team

The mentor and admin team provided useful support in terms of learning direction, submission requirements, and result presentation. The workshop instructions gave me a clear starting point, especially in the early stage when I was not yet familiar with AWS Console, IAM, VPC, EC2, and concepts such as public/private subnets.

During the final project phase, the feedback on the proposal and diagram helped me realize that an AWS diagram should not only include enough services. It must also correctly show the business flow, security boundary, access control, and operational evidence. This was the most valuable part for me because it forced me to understand the design rationale, not just draw a visually acceptable diagram.

### 3. Relevance to My Major

The internship content was relevant to my Information Technology major and helped me expand from programming and system knowledge toward Cloud Architecture and Cloud Security. The knowledge I learned is directly connected to these areas:

* **Cloud Computing:** working with AWS Console, EC2, VPC, RDS, CloudWatch, IAM, and core AWS services.
* **Network & Security:** understanding public/private subnets, route tables, security groups, IAM roles, least privilege, and private-by-default design.
* **System Design:** converting requirements into an architecture with components, data flow, boundaries, and monitoring mechanisms.
* **Documentation:** writing worklogs, proposals, diagram explanations, and standardizing content in a Hugo workshop.

Before the internship, I usually viewed AWS services as separate parts. After 12 weeks, I better understood how to connect them into a workload with a clear purpose, such as a private worker that reads configuration, processes tasks, writes logs/evidence, and limits public access.

### 4. Learning Opportunities and Skill Development

During the 12-week internship, I improved both technical skills and architecture thinking.

Technical skills:

* Configuring IAM based on the least privilege principle.
* Designing a VPC with public/private subnets, route tables, and security groups.
* Deploying EC2, understanding AMI, user data, and safer administrative access.
* Working with Amazon RDS as a private database, including subnet groups, backup, and connectivity from an application/worker.
* Using CloudWatch Logs, Metrics, and Alarms to create operational evidence.
* Understanding AWS Budgets, cost awareness, and resource cleanup after labs.
* Approaching Infrastructure as Code with CloudFormation/Terraform at a foundational level.

Soft skills:

* Recording weekly progress so that learning outcomes were not lost after finishing labs.
* Reading English documentation and extracting the main ideas for project application.
* Collaborating with my teammate during the final two weeks to align the proposal, diagram, and implementation direction.
* Receiving feedback, correcting the inaccurate diagram, and improving the clarity of my presentation.

The clearest improvement for me was my ability to explain architecture. At first, I only knew what each service was used for. By the end, I could explain why a service appeared in the diagram, which component it communicated with, what risk it addressed, and where the verification evidence could be found.

### 5. Culture and Teamwork

During the internship, I found teamwork and mutual support important. In the early weeks, each person could focus on a different learning direction. However, in the final two weeks, when we had to finalize the proposal, correct the AWS diagram, and implement the project, aligning our understanding became necessary.

My teammate and I divided responsibilities more reasonably: I focused more on architecture, security boundary, IAM, private VPC design, monitoring, and evidence; my teammate focused more on implementation, operations, testing, documentation, and cleanup. This division made the project more coordinated instead of both of us duplicating exactly the same work.

### 6. Internship Policy / Benefits

The internship program had a clear learning path and was suitable for students who were new to AWS. The combination of workshops, official AWS documentation, worklogs, proposal, and final project helped interns learn while also producing concrete evidence of their learning process.

I especially appreciated the requirement to create a diagram and proposal. These two tasks were more difficult than simply running labs, but they helped me understand the content more deeply. If I only completed labs, I might finish the steps without being able to explain the design. When I had to write the proposal and defend the diagram, I had to review every component and connection.

If possible, I hope the program can add some diagram or proposal review sessions earlier than the final week. This would help interns detect architecture issues sooner and avoid concentrating too many corrections at the end.

---

## Additional Questions

### What were you most satisfied with during the internship?

What satisfied me most was that I developed a clearer view of AWS Architecture. Previously, I learned cloud in a fragmented way: I knew a little about many services, but I did not have a strong anchor to understand why those services should exist together in one system. After the internship, especially through the proposal and diagram work, I better understood how to ask key questions: What is the workload’s goal? Where does the data flow? Which part should remain private? Who has access? Where are the logs/evidence? Is the cost controlled?

I was also satisfied with my improvement in self-learning. Instead of only following step-by-step instructions, I learned to compare workshops with AWS Docs, record issues, edit Hugo content, and summarize results into worklogs.

### What do you think the company should improve for future interns?

In my opinion, the internship program is already well organized, with a clear learning roadmap and comprehensive learning materials. Throughout the internship, I did not encounter any major difficulties regarding the training content or learning resources.

If I could make one small suggestion, it would be to include more experience-sharing sessions about real-world projects or the engineering team's development workflow. This would help interns better understand how AWS technologies are applied in a professional working environment.

I also hope the company will continue to maintain this internship program so that more students can gain valuable learning and practical experience.

### Would you recommend this internship to your friends? Why?

Yes. I would recommend it to friends who genuinely want to learn AWS through practice. The program is suitable for students who want a path from fundamentals to a project, especially those who want to understand Cloud beyond simply knowing service names. It helps learners explain deployment flow, security, operations, and cost considerations.

However, I would also make it clear that the program requires proactiveness. If a student only follows the labs without reading AWS Docs, documenting issues, and asking why the architecture is designed that way, the learning result will not be deep. Learners need to actively ask questions, reread documentation, and review their own project.

---

## Suggestions and Expectations

### Do you have any suggestions to improve the internship experience?

I suggest adding a short session on how to evaluate an AWS diagram. The content could focus on basic questions such as:

* Does the diagram correctly show the public/private boundary?
* Which service handles the main business logic?
* Where does data flow from and to?
* Are IAM roles, security groups, and monitoring/evidence included?
* Which logs, metrics, or screenshots can prove that the project worked?

With this type of checklist, interns would be able to review their own projects more easily before submission.

### Would you like to continue this program in the future?

Yes. If I have the opportunity, I would like to continue learning more deeply about Cloud Security, Infrastructure as Code, and private workload architecture on AWS. I also want to practice more with services such as VPC Endpoint, SQS, EventBridge, SNS, CloudWatch Alarm, KMS, and Systems Manager to better understand how to implement an internal workload that is secure, observable, and cost-aware.

In addition, I want to keep improving my bilingual technical documentation skills. While building the Hugo workshop, I realized that good documentation must not only be technically correct, but also well-structured, readable, and easy to verify.

### Other feedback:

I would like to thank the company, mentor, and admin team for giving me the opportunity to approach AWS in a practical way. The internship helped me understand that learning Cloud is not only about creating resources on AWS, but also about understanding architecture, security, operations, cost, and evidence that proves the system works correctly.

After 12 weeks, I feel that I have a stronger foundation to continue learning Cloud Architecture and Cloud Security. I still need to improve my implementation speed, concise explanation ability, and diagram review skills, but the internship has given me a clearer learning direction.

---

This is my honest feedback based on my personal internship experience.
