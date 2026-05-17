# AWS Architecture Portfolio Hub

This repository is the central hub for my **AWS architecture portfolio**, focused on backend and cloud engineering with Node.js, TypeScript, AWS Serverless, Terraform, and cloud architecture.

The architecture implementations live in separate repositories linked below. This hub is not a deployable infrastructure repository and does not contain Terraform code, application code, or environment-specific deployment assets.

## Portfolio Goal

The goal of this portfolio is to make the strongest AWS backend and cloud architecture work easy to review for CV screening, interviews, and technical discussion.

It demonstrates:

- Backend and cloud architecture patterns on AWS
- Serverless API design, containerized application deployment, and managed AI application integration
- Terraform and Infrastructure as Code concepts through linked project repositories
- Awareness of security, observability, scalability, and cost trade-offs
- Clear architecture communication without presenting the examples as production-ready systems

These projects are portfolio and learning-oriented architecture examples. The maturity labels below are intentionally modest.

## Recommended Review Path

If you only review three projects, start with:

1. [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) - strongest fit for backend/serverless API discussion.
2. [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) - shows cloud application design around managed GenAI capabilities.
3. [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) - shows container deployment, networking, and service operation concepts.

These are the featured projects and the clearest review path for backend/cloud engineering roles. The remaining repositories are still part of the portfolio, but they should be treated as supporting AWS architecture references rather than equally deep projects.

## Featured Projects

| Project | What it demonstrates | Main AWS services | Why it is relevant for backend/cloud roles | Current maturity/status |
|---|---|---|---|---|
| [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) | Serverless API architecture, request handling, persistence, and backend service boundaries. | Amazon API Gateway, AWS Lambda, Amazon DynamoDB, IAM, Amazon CloudWatch. | Directly maps to API backend work, serverless application design, service integration, and discussions about validation, IAM, observability, scaling, and cost. | Improving. This is the main project being deepened with clearer API design notes, security considerations, observability notes, and cost trade-offs. |
| [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) | A starter architecture for integrating managed GenAI capabilities into a cloud application. | Amazon Bedrock, AWS Lambda, API/application integration patterns, IAM, Amazon CloudWatch. | Relevant for teams adding AI-assisted workflows while still needing backend fundamentals: service boundaries, permissions, operational visibility, and cost awareness. | Basic. Useful as a focused GenAI architecture reference, with room to deepen implementation detail and operational notes. |
| [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) | Containerized web application architecture, service deployment, networking, and scaling concepts. | Amazon ECS, AWS Fargate, Elastic Load Balancing, Amazon EFS, Amazon VPC, IAM, Amazon CloudWatch. | Supports discussion of backend service hosting outside pure serverless, including container operations, traffic routing, health checks, scaling, and deployment flow. | Basic. A baseline container architecture reference that should be reviewed as a foundation rather than a production platform claim. |

## Additional AWS Architecture References

These repositories show breadth across common AWS architecture patterns. They are included to demonstrate wider exposure to AWS services and design choices, but they are not all equally deep.

| Repository | Architecture reference | Main AWS services / pattern | Current maturity/status |
|---|---|---|---|
| [aws-static-website-hosting](https://github.com/hongzz0618/aws-static-website-hosting) | Static website hosting and CDN delivery. | Amazon S3, Amazon CloudFront, DNS/TLS concepts. | Basic supporting reference. |
| [aws-data-lake](https://github.com/hongzz0618/aws-data-lake) | Data lake and analytics foundation. | Amazon S3 data lake pattern, cataloging, query and analytics services. | Basic supporting reference. |
| [aws-event-driven-processing](https://github.com/hongzz0618/aws-event-driven-processing) | Event-driven processing and asynchronous workflow design. | Amazon EventBridge, AWS Lambda, managed messaging/event patterns. | Basic supporting reference. |
| [aws-realtime-streaming](https://github.com/hongzz0618/aws-realtime-streaming) | Real-time ingestion and streaming architecture. | Amazon Kinesis-style streaming ingestion and processing pattern. | Basic supporting reference. |
| [aws-ci-cd](https://github.com/hongzz0618/aws-ci-cd) | Delivery automation and CI/CD workflow design. | AWS CodePipeline-style build, test, and deployment workflow. | Basic supporting reference. |

## Maturity Labels

| Maturity | Meaning |
|---|---|
| Basic | Initial implementation or architecture baseline exists in the linked repository. |
| Improving | The project is being enhanced with clearer documentation, security notes, observability notes, cost notes, and architecture trade-offs. |
| Portfolio-ready | Target state where a project is suitable for deeper CV and interview discussion, with enough structure to explain architecture choices and trade-offs clearly. |

None of the projects are described as production-ready. The focus is clear architecture communication, practical AWS learning, and steady improvement.

## CV and Interview Relevance

This portfolio is designed to support backend and cloud engineering applications by making the most relevant work easy to find first.

The strongest discussion areas are:

- Explaining service selection and trade-offs for serverless and containerized backends
- Discussing how IAM, observability, cost, and scalability would be improved over time
- Comparing serverless, containerized, event-driven, data, streaming, and CI/CD architectures
- Showing practical familiarity with Terraform and Infrastructure as Code through the linked implementation repositories
- Communicating cloud architecture clearly and honestly

## Roadmap

| Phase | Focus | Outcome |
|---|---|---|
| Phase 1 | Improve the main portfolio hub | Make the README and GitHub Pages content a clear landing point for backend/cloud engineering review. |
| Phase 2 | Standardize sub-repository READMEs | Align project documentation around overview, services, architecture diagram, deployment notes, trade-offs, and next steps. |
| Phase 3 | Deepen Serverless API Backend | Improve API design notes, IAM boundaries, validation, observability, and cost considerations. |
| Phase 4 | Deepen GenAI Starter and Containerized Web App | Improve GenAI application boundaries and container architecture notes, including networking, scaling, health checks, and deployment flow. |
| Phase 5 | Improve supporting references | Add clearer cross-project notes on CI/CD, security, observability, cost drivers, data, streaming, and event-driven patterns. |

## Feedback

Suggestions, issues, and improvements are welcome. This portfolio is being improved iteratively as the linked architecture projects become more complete and better documented.
