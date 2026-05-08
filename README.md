# AWS Architecture Portfolio Hub

This repository is the central portfolio hub for **8 AWS architecture projects** focused on backend, cloud engineering, and practical AWS design patterns.

The actual architecture implementations live in separate repositories linked below. This hub is not a deployable infrastructure repository and does not contain Terraform code, application code, or environment-specific deployment assets.

## Portfolio Goal

The goal of this portfolio is to demonstrate the ability to design, explain, and compare common AWS architectures used in backend and cloud engineering roles.

It is intended to support CV screening, technical interviews, and project discussions by showing:

- Practical understanding of AWS service combinations
- Awareness of backend, serverless, event-driven, container, data, and CI/CD patterns
- Ability to document architecture decisions clearly
- Consideration of security, observability, scalability, and cost trade-offs
- Continuous improvement through focused, realistic project iterations

These projects are portfolio and learning-oriented architecture examples. They are not presented as production-ready systems.

## What This Repository Is

This repository is the central index for the AWS Architecture Portfolio.

Each architecture has its own dedicated repository. The linked repositories contain the relevant implementation details, diagrams, Terraform or Infrastructure as Code examples, deployment notes, and project-specific documentation.

Use this hub to compare the architecture patterns, understand the skills demonstrated by each project, and navigate to the individual repositories for deeper technical detail.

## Skills Demonstrated

This portfolio demonstrates exposure to AWS backend and cloud engineering topics including:

- AWS architecture patterns for common real-world workloads
- Terraform and Infrastructure as Code concepts
- Serverless backend design with API Gateway, Lambda, DynamoDB, and related services
- Event-driven architecture using managed AWS event and messaging services
- Containerized application deployment patterns
- Data lake, streaming, and analytics-oriented cloud patterns
- CI/CD workflow design for application and infrastructure delivery
- Security awareness, including IAM, encryption, access boundaries, and least privilege
- Observability awareness, including logs, metrics, tracing, and alerting considerations
- Cost awareness, including service selection, scaling behavior, and optimization trade-offs

## Architecture Overview

| Architecture | Main AWS Services / Pattern | Real-world use case | Key skill demonstrated | Current maturity | Repository link |
|---|---|---|---|---|---|
| Static Website Hosting | S3 and CloudFront static hosting pattern | Marketing sites, documentation portals, portfolio sites | Static hosting, CDN delivery, DNS, and TLS concepts | Basic | [Repository](https://github.com/hongzz0618/aws-static-website-hosting) |
| Serverless API Backend | API Gateway, Lambda, and DynamoDB serverless API pattern | Mobile backends, web APIs, microservices | Serverless backend design and API integration | Improving | [Repository](https://github.com/hongzz0618/aws-serverless-api-backend) |
| Data Lake | S3-based data lake and analytics pattern | Analytics foundations, business intelligence, data storage | Data organization, query patterns, analytics architecture | Basic | [Repository](https://github.com/hongzz0618/aws-data-lake) |
| Event-Driven Processing | EventBridge, Lambda, and messaging-oriented event pattern | File processing, automation workflows, async business events | Event-driven system design and decoupling | Basic | [Repository](https://github.com/hongzz0618/aws-event-driven-processing) |
| Real-Time Data Streaming | Kinesis-style streaming ingestion pattern | IoT events, live dashboards, streaming ingestion | Streaming ingestion and near-real-time processing | Basic | [Repository](https://github.com/hongzz0618/aws-realtime-streaming) |
| Containerized Web App | ECS/Fargate-style container application pattern | Scalable web platforms and backend services | Container deployment, networking, and service scaling concepts | Basic | [Repository](https://github.com/hongzz0618/aws-containerized-web-app) |
| CI/CD Pipeline | AWS managed CI/CD pipeline pattern | Automated build, test, and deployment workflows | Delivery automation and deployment pipeline design | Basic | [Repository](https://github.com/hongzz0618/aws-ci-cd) |
| GenAI-Powered Application | Managed GenAI application integration pattern | AI-assisted workflows, chatbots, content generation | Integrating managed GenAI services into cloud applications | Basic | [Repository](https://github.com/hongzz0618/aws-genai-starter) |

Serverless API Backend is currently marked as Improving because it is the first architecture being actively deepened with clearer API design notes, security considerations, observability notes, and cost trade-offs. The other projects are currently treated as Basic until their documentation and implementation baselines are reviewed and improved.

## Project Maturity

The maturity labels are intentionally modest and reflect the current portfolio status of each linked project. Portfolio-ready is a target state for the portfolio, not a current label applied to any project in this hub.

| Maturity | Meaning |
|---|---|
| Basic | Deployable baseline or initial implementation exists in the linked repository. |
| Improving | The project is being enhanced with better documentation, security notes, observability notes, cost notes, and architecture trade-offs. |
| Portfolio-ready | Target state where a project is suitable for CV and interview discussion, with enough structure to explain the architecture, service choices, and trade-offs clearly. |

None of the projects are described as production-ready. The focus is on clear architecture communication, practical AWS learning, and steady improvement.

## Roadmap

| Phase | Focus | Outcome |
|---|---|---|
| Phase 1 | Improve the main portfolio hub | Make this README a clear landing page for AWS backend and cloud engineering roles. |
| Phase 2 | Standardize sub-repository READMEs | Align each project around consistent sections for overview, services, architecture diagram, deployment notes, trade-offs, and next steps. |
| Phase 3 | Deepen Serverless API Backend | Improve API design notes, IAM boundaries, validation, observability, and cost considerations. |
| Phase 4 | Deepen Containerized Web App | Improve ECS/Fargate architecture notes, networking, scaling, health checks, and deployment flow. |
| Phase 5 | Improve CI/CD, security, observability, and cost documentation | Add clearer cross-project notes on delivery pipelines, monitoring, logging, least privilege, and cost drivers. |

## CV and Interview Relevance

This portfolio is designed to support AWS backend and cloud engineering applications by making the architecture work easy to review and discuss.

For CV screening, it provides a concise map of AWS patterns, services, and project themes. For interviews, it gives concrete examples to discuss service selection, trade-offs, scaling behavior, operational concerns, and future improvements.

The strongest interview use cases are:

- Explaining why specific AWS services were selected for each workload
- Comparing serverless, containerized, event-driven, and data-oriented architectures
- Discussing how security, observability, and cost considerations would be improved over time
- Showing practical familiarity with Terraform and Infrastructure as Code through the linked implementation repositories
- Demonstrating the ability to communicate architecture clearly and honestly

## Feedback

Suggestions, issues, and improvements are welcome. This portfolio is being improved iteratively as the linked architecture projects become more complete and better documented.
