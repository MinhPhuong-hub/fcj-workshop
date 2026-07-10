---
title: "Event 2"
date: 2026-05-23
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Event Report – Technology Knowledge Sharing

## Event Objectives

The event was organized to provide a platform for developers, engineers, architects, and technology enthusiasts to exchange knowledge and practical experiences in Cloud Computing and Artificial Intelligence.

The main topics included:

- Cost optimization and infrastructure security.
- AI-powered business process automation.
- Enterprise Multi-Agent AI systems.
- Context Engineering for Generative AI.
- AI governance and enterprise security.
- Practical challenges of deploying Large Language Models (LLMs) in production environments.

---

## Speakers

- **Pham Nguyen Hai Anh** – G-AsiaPacific Vietnam, AWS Community Builder
- **Nguyen Tuan Thinh** – DevOps Engineer, First Cloud AI Journey
- **Tinh Truong** – Platform Engineer, GoTymeX
- **Lam Vy** – Senior Business Systems Analyst, VPBank
- **Dao Duc** – Solution Architect, Cloud Kinetics

---

## Key Topics

### 1. Infrastructure Optimization with Amazon CloudFront

The session introduced the latest CloudFront capabilities that help organizations improve application performance, reduce operational costs, and strengthen security.

#### Flat-rate Pricing

AWS introduced fixed pricing plans for Amazon CloudFront:

- Free
- Pro
- Business
- Premium

Compared to the traditional pay-as-you-go model, these plans provide more predictable monthly costs and reduce the risk of unexpected expenses caused by traffic spikes or DDoS attacks.

#### Infrastructure Optimization

Several optimization techniques were presented:

- Free data transfer from AWS Origins to CloudFront.
- TCP connection management handled at Edge Locations.
- HTTP compression to reduce payload size.
- Reduced CPU utilization on origin servers.
- Lower Load Balancer processing costs.
- Faster content delivery for end users.

#### Distributed DDoS Protection

CloudFront mitigates volumetric attacks directly at Edge Locations before malicious traffic reaches backend services.

Additional enterprise security features such as mutual TLS (mTLS) were also introduced for applications requiring stronger authentication.

---

### 2. GenAIOps and Context Engineering

One of the most valuable sessions emphasized that AI quality depends more on context than on the model itself.

#### The Importance of Context

Poor AI responses are often caused by:

- Unclear objectives.
- Irrelevant information.
- Missing constraints.
- Undefined success criteria.
- Excessive unrelated documents.

Providing more information does not necessarily improve response quality and may increase token consumption.

#### Context Quality over Context Quantity

A high-quality context should contain four key components:

- **Goal**
- **Relevant Information**
- **Constraints**
- **Success Criteria**

This framework helps AI better understand the task and generate more accurate outputs.

#### The Evolution of AI

The speaker described the evolution of AI applications:

- Prompt Engineering
- Context Engineering
- Long-term Memory
- AgentOps

This evolution enables AI systems to become more autonomous and capable of solving increasingly complex tasks.

---

### 3. Business Process Automation with Amazon Quick Suite

Amazon Quick Suite was introduced as an Agentic AI platform for automating repetitive business processes.

Common business activities such as:

- Information collection
- Report generation
- Meeting documentation
- Email notifications
- Workflow coordination

can be automated through AI agents.

The platform integrates with:

- Amazon Bedrock
- More than 40 enterprise data sources
- Thousands of third-party applications

A practical example demonstrated how AI could automatically generate meeting minutes and distribute follow-up emails to participants.

---

### 4. Enterprise Multi-Agent Systems

This session presented an enterprise-grade Multi-Agent architecture through a startup credit assessment use case.

Instead of relying on a single AI model, specialized agents collaborate in different domains:

- Financial Analysis
- Market Evaluation
- Team Assessment
- Risk Analysis
- Compliance Review

This collaborative approach improves decision quality and transparency.

#### Advantages over Single-Agent Systems

Compared to traditional AI assistants, Multi-Agent systems provide:

- Cross-validation among agents.
- Better explainability.
- Higher auditability.
- Faster processing.
- Lower operational costs.

The case study demonstrated significant improvements in both processing time and decision-making efficiency.

#### Enterprise AI Security

The speaker emphasized that enterprise AI systems should include security controls from the beginning, including:

- Input and output filtering.
- PII detection.
- Prompt Injection prevention.
- Private VPC deployment.
- Access control.
- Logging and auditing.

---

### 5. Non-Determinism in Large Language Models

The final presentation explored why LLMs are not fully deterministic, even when using very low temperature settings.

#### Why It Happens

Experimental results showed that identical prompts may still produce different outputs due to:

- Floating-point computation on GPUs.
- Parallel execution.
- Inference batching.
- Hardware optimization.

#### Practical Recommendations

Several mitigation techniques were suggested:

- Use `temperature = 0.1` instead of zero in many scenarios.
- Apply majority voting.
- Enforce structured outputs such as JSON.
- Validate AI responses before downstream processing.
- Design applications that tolerate small output variations.

---

## What I Learned

### Infrastructure Optimization

I gained a better understanding of how Amazon CloudFront improves application performance while reducing infrastructure costs and strengthening security.

---

### Better Context Design

One important takeaway is that **high-quality context is more valuable than large amounts of information**.

Clearly defining objectives, constraints, and success criteria leads to more accurate AI responses.

---

### Agentic AI

The event demonstrated that AI is no longer limited to answering questions.

Modern AI agents can:

- Execute workflows.
- Integrate multiple services.
- Automate repetitive tasks.
- Coordinate complex business processes.

---

### Multi-Agent Architecture

For complex business problems, multiple specialized agents provide better scalability, transparency, and reliability than a single AI model.

---

### Understanding AI Limitations

I also learned that LLM outputs are naturally non-deterministic.

Instead of expecting identical responses every time, developers should build applications with validation, structured outputs, and fault-tolerant workflows.

---

## Applying the Knowledge

The knowledge gained from this event can be applied in several areas:

- Deploy Amazon CloudFront to improve application performance and security.
- Design AI prompts using structured Context Engineering principles.
- Adopt structured outputs when integrating LLMs into applications.
- Build validation layers before AI-generated data enters production systems.
- Explore Multi-Agent architectures for complex business workflows.
- Apply enterprise security practices when deploying AI systems.
- Automate repetitive business processes using Agentic AI.

---

## Personal Experience

Participating in this event provided valuable insights into how modern organizations are applying Cloud Computing and Artificial Intelligence in real-world environments.

The speakers not only introduced technical concepts but also shared practical implementation experiences and production challenges.

Among all presentations, the sessions on Context Engineering and Multi-Agent Systems were particularly impressive because they highlighted that successful AI applications require more than just powerful language models—they also depend on architecture, security, governance, and well-designed workflows.

The discussions also changed my perspective on AI development. Instead of focusing only on prompt engineering, I now recognize the importance of context management, long-term memory, security guardrails, and reliable system design.

Overall, the event broadened my understanding of enterprise AI and provided practical knowledge that can be applied to future software projects.

---

## Key Takeaways

- CloudFront is more than a CDN—it is also an important security and cost optimization solution.
- Context Engineering has a significant impact on AI response quality.
- Multi-Agent architectures are well suited for complex enterprise applications.
- AI systems should include governance and security controls from the design phase.
- LLMs are inherently non-deterministic, so production systems must be designed accordingly.
- Agentic AI has great potential to automate repetitive business processes and improve operational efficiency.

---

## Event Photos

<!-- Replace these placeholders with your actual images -->

![Event Photo 1](/fcj-workshop/images/4-Event/event2-1.jpg)

![Event Photo 2](/fcj-workshop/images/4-Event/event2-2.jpg)

![Event Photo 3](/fcj-workshop/images/4-Event/event2-3.jpg)

> Overall, this event provided valuable insights into enterprise AI, Cloud infrastructure, and practical system design, while encouraging participants to think beyond prompt engineering and focus on building secure, scalable, and production-ready AI solutions.