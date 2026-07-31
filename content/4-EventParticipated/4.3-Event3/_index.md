---
title: "Event 3"
date: 2026-07-25
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Summary Report: "Agentic AI Build Week (AABW) – Demo Day"

### Event Purpose

- Showcase practical results after intensive days of building Agentic AI products on the AWS platform.
- Create a hands-on environment for competing teams to apply the AWS AI/ML ecosystem to real-world enterprise problems.
- Connect young talent with experienced experts and mentors across the AWS community.
- Spread the "Build Week" spirit – transforming ideas into fully functional, production-ready products within tight time constraints.

### Participating Teams

- **3KA:** Huynh An Khuong, Nguyen Quoc Huy, Ngo Quang Khoi, Hoang Le Thanh Duc, Dang Nguyen Phuoc Loc, Dang Truong Hung.
- **OneTeam:** Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy.
- **Plan V:** Pham Tien Thuan Phat, Huynh Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An.
- **Signal Scout:** Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan.

---

### Project Highlights

#### 1. Team 3KA – S.H.E.P.H.E.R.D (Smart Crowd Evaluation & Hazard Detection)
- **Problem Statement:** Real-time crowd density monitoring, queue management, and bottleneck alerts at large venue events.
- **Solution & Architecture:** Integrated **YOLO + ByteTrack** (detection/tracking) + **Amazon SageMaker** (inference) + **Amazon Bedrock AgentCore & Strands Agent** (AI agent layer) + Real-time React Monitoring Dashboard.
- **Key Highlights:** Dual-layer AI operating model: **Autonomous Monitor** (automated anomaly detection and proactive alerts) and **Operator Copilot** (enabling operators to query real-time data using natural language).
- **Challenges:** Maintaining stable video streams, minimizing inference latency, optimizing operational costs, and ensuring agent explainability.

#### 2. Team OneTeam – KFC Bot Agent (Conversational Commerce)
- **Problem Statement:** Addressing customer drop-offs during chat-based ordering caused by app-switching friction.
- **Solution:** Multi-channel conversational ordering agent (Zalo OA, Messenger) operating on a 5-step lifecycle: **Goal → Plan → Tools → Act → Verify**.
- **Results:** **3–5 second** end-to-end response latency, highly optimized costs (**~$0.006/order**, **~$88/month** total infra), and a **60% reduction in infrastructure code** leveraging AgentCore.

#### 3. Team Plan V – Solution Architect Professional Native App (AI Assistant for Solution Architects)
- **Problem Statement:** Automating time-consuming manual workflows involving BRD/SOP analysis, architecture design, and cost estimation.
- **Solution:** An AI-native application connecting **Amazon Bedrock**, **Draw.io MCP**, and **AWS Pricing MCP**.
- **Impact:** Transformed manual workflows into an "Upload + Chat" experience—automatically generating Requirements Catalogues, AWS-compliant architecture diagrams, and detailed cost estimates within minutes.

#### 4. Team Signal Scout – Enterprise Strategic Intelligence
- **Problem Statement:** Gathering and verifying public evidence to detect early corporate restructuring and strategic shifts among competitors.
- **Multi-Agent Architecture:** An **Agent-to-Agent (A2A)** model featuring a **Crawler Subagent** (data ingestion via TinyFish, Apify) and an **Analysis Subagent** (analysis, Bedrock Guardrails enforcement, and Langfuse logging), fully backed by AWS security standards (WAF, Cognito, CloudWatch).
- **Business Value:** Provides verifiable evidence supporting business decisions (*Maintain – Adapt – Accelerate*) with optimized monthly costs (**$81–$359/month**).

---

### Key Takeaways

#### Technical Insights
- **Agentic AI Architecture on AWS:** Mastered orchestrating Amazon Bedrock, AgentCore Runtime, and Strands Agent to build autonomous agents capable of planning, tool execution, and self-verification.
- **Multi-Agent Systems (A2A):** Understood domain separation between specialized subagents to maximize overall system throughput and reliability.
- **Automation & Computer Vision:** Applied real-world video stream processing (YOLO, ByteTrack) and automated cloud design via Model Context Protocol (MCP) servers.

#### Product Mindset
- Always start with **concrete user pain points** before making technology choices.
- Incorporate operational cost optimization (Cost Design) directly into early architectural decisions.
- Balance rapid development under time constraints with AI system explainability and safety.

#### Teamwork & Execution
- Embraced the mindset *"Execution matters more than perfection"*—a complete, working prototype delivers far more value than an unfinished grand concept.
- Clear role separation and well-defined objectives are essential when delivering under high pressure.

---

### Practical Applications

- Apply the core Agentic decision loop (**Goal → Plan → Tools → Act → Verify**) when designing system automation features.
- Experiment with **AgentCore / Strands Agent** for complex, multi-step orchestration workflows.
- Leverage AI-assisted tooling to streamline requirement gathering and initial AWS cost estimations for future technical proposals.

---

### Event Experience & Personal Reflections

Attending the **Agentic AI Build Week – Demo Day** as an observer was an inspiring experience. It clearly demonstrated that Agentic AI has evolved beyond theoretical concepts into practical, production-ready enterprise solutions.

#### Diversity in Real-World Applications
The four teams tackled vastly different domains: crowd safety, conversational commerce, solution architecture assistance, and enterprise intelligence. This highlighted the exceptional versatility and scalability of the AWS AI/ML ecosystem.

#### Production-Grade Architectural Learnings
Gained valuable insights into cutting-edge AWS AI components (**Bedrock AgentCore, Strands Agent, AgentCore Gateway/Memory**) and learned how teams addressed real-world operational challenges: latency mitigation, Guardrails security, and cost control.

#### Core Conclusion
- AI is shifting rapidly from passive "Conversational Chatbots" to active "Action Agents" capable of reasoning, executing tools, and verifying outcomes independently.
- Seamless integration across the AWS service stack is the key driver in taking an AI concept from the lab to stable production.

#### Event Photos

![](/images/4-Event/event3.jpg)
![](/images/4-Event/event3-2.jpg)

> Overall, **Agentic AI Build Week Demo Day** not only deepened my technical knowledge of AI/ML on AWS but also reinforced the essence of engineering execution: taking real-world problems, building optimal cloud architectures, and delivering functional products.