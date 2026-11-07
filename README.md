# Hi, I'm Raf

I build enterprise data platforms, reliable software and automation. My current focus is bringing those foundations into AI workflows: connecting systems, gathering evidence and keeping people in control of consequential actions.

My work spans platform engineering, streaming data, application development and delivery automation, with an interest in financial services and operational workflows.

## Selected projects

### AI-enabled workflow design and execution platform

My main AI engineering project is a visual platform for designing, configuring, running and observing reusable workflows. It brings together triggers, configurable connections and tool integrations, AI reasoning, executable steps and human decision points in one workflow.

The focus is practical enterprise automation: gathering evidence from connected systems, deciding the next step and routing actions through explicit user choices and approvals. Versioned workflows and recorded execution history make runs traceable and decisions easier to review.

An incident investigation and recovery showcase demonstrates the flow: detect a pipeline failure, gather evidence, use AI to assess the cause, pause for a human decision, then carry out a simulated recovery and verify the outcome. It shows how automated investigation, repeatable procedures and human oversight can work together.

The platform is under active development and its source remains private.

### [Pageview streaming pipeline](https://github.com/Rafalski/stream-challenge)

A runnable local pipeline using Python, Kafka and PyFlink to archive original events and calculate event-time aggregates.

The project explores data contracts, invalid and late events, checkpoint-dependent output, observability and independently specified test results. Its documentation explains the design tradeoffs, local safeguards and limits of its delivery guarantees.

## What I'm building

- **Data platforms:** streaming pipelines, payment-event processing, reconciliation, data quality and operational visibility.
- **AI automation:** evidence-led investigation, constrained tool use, versioned workflows, human approvals and auditable execution.
- **Software delivery:** repeatable environments, infrastructure as code, CI/CD, database migrations and backup/restore verification.
- **Business applications:** relational data models, permissions, audit trails and workflows that reflect real operational needs.

These are areas of active work. Public examples and case studies will distinguish demonstrated behaviour from planned capabilities.

## Community projects

Alongside my platform and AI work, I develop software to support community organisations.

- **CRM for supplementary and community language schools:** a system for managing families, pupils, enrolment, fees and payments, with role-based access and audit trails. The project began with a Polish Saturday school. The source remains private while I explore grant funding and partnerships to make the software available free of charge to supplementary and community language schools across the UK.
- **Running and athletics club management:** an application I developed for my own running club and which is now in use there. It supports membership and race administration, with results, club championships and club records on the roadmap. The source remains private as I develop it into a software-as-a-service offering for other clubs.

## Engineering approach

I care about clear contracts, reproducible demos, meaningful tests and explicit failure behaviour. I document why a design was chosen, what has been verified and where its limits are.

For AI-enabled systems, that includes evaluating results, limiting tool permissions and making approval boundaries visible. For cloud delivery, it includes managed identities, appropriate secret storage and realistic cost controls.

## Technologies

- **Languages:** Python · SQL · TypeScript/JavaScript · Java
- **Cloud and data:** Azure · AWS · Databricks · Azure Data Factory · Kafka · Apache Flink · StreamSets · PostgreSQL
- **Delivery:** Docker · Infrastructure as code · GitLab CI/CD · GitHub Actions
