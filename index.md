# AWS Backend Architecture Reference Projects

This GitHub Pages site is a reference hub for backend-focused AWS architecture projects using Node.js, TypeScript, Terraform, serverless services, containers, and managed cloud integrations.

Each architecture project lives in its own repository with its own documentation and implementation details. The goal of this hub is to make the recommended technical path through the three featured projects clear.

> **Current state:** These projects are learning-focused reference examples. They are being improved over time and are not presented as deployable production systems.

---

## Recommended Review Path

If you only review three projects, start with:

1. [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend)
2. [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app)
3. [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter)

These featured projects are the suggested path through the backend and cloud architecture topics.

---

## Project Comparison

Use this comparison to choose where to start. The Serverless API Backend is the main backend discussion project, the Containerized Web App is best for ECS and infrastructure discussion, and the GenAI Starter is best for managed model integration discussion.

| Project | Main pattern | Core AWS services | Runtime / language | IaC | CI / validation | Testing | Observability | Main limitation / next step | Best discussion angle |
|---|---|---|---|---|---|---|---|---|---|
| [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) | REST-style serverless item API | API Gateway, Lambda, DynamoDB, IAM, CloudWatch | TypeScript Lambda handlers | Terraform | GitHub Actions for typecheck, tests, build, audit, packaging, Terraform fmt, and Terraform validate | Vitest unit tests; optional post-deployment smoke test helper | Structured Lambda logs, API Gateway access logs, CloudWatch metrics, and basic alarms | Add auth/access control, remote state, deployment flow, and controlled smoke tests | Main backend API discussion: validation, IAM, observability, cost, auth, and deployment trade-offs |
| [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) | Containerized web app behind a public ALB with private ECS tasks | ECS Fargate, ALB, EFS, VPC, IAM, CloudWatch Logs | Node.js / TypeScript sample app in Docker | Terraform | GitHub Actions for app build/test, Docker image build, Terraform fmt, init, and validate | Sample app tests | ECS task logs and ALB target health checks | No automatic deployment, ECR image publishing, HTTPS, or service autoscaling yet | Container infrastructure discussion: Fargate networking, ALB routing, EFS, and operational boundaries |
| [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) | Serverless managed-model request path with chat history | API Gateway HTTP API, Lambda, Bedrock Converse, DynamoDB, IAM, CloudWatch | TypeScript Lambda handler | Terraform | GitHub Actions for typecheck, unit tests, build, Lambda packaging, Terraform fmt, and Terraform validate | Unit tests | Logs, metrics, alarms, dashboard examples, optional notifications, and cost-signal examples | Scope CORS, model permissions, state, deployment permissions, and live validation before broader use | Managed model integration discussion: Bedrock calls, persistence, permissions, observability, and cost controls |

---

## Featured Projects

| Project | What it demonstrates | Main AWS services | Backend/cloud relevance | Status |
|---|---|---|---|---|
| [aws-serverless-api-backend](https://github.com/hongzz0618/aws-serverless-api-backend) | Serverless API architecture, request handling, persistence, and backend service boundaries. | Amazon API Gateway, AWS Lambda, Amazon DynamoDB, IAM, Amazon CloudWatch. | Strong fit for API backend design, service integration, validation, IAM, observability, scaling, and cost discussion. | Improving. Main project being deepened. |
| [aws-containerized-web-app](https://github.com/hongzz0618/aws-containerized-web-app) | Containerized web application architecture, service deployment, networking, and operational boundaries. | Amazon ECS, AWS Fargate, Elastic Load Balancing, Amazon EFS, Amazon VPC, IAM, Amazon CloudWatch. | Supports discussion of container operations, traffic routing, health checks, scaling, and deployment flow. | Basic. Baseline container architecture reference. |
| [aws-genai-starter](https://github.com/hongzz0618/aws-genai-starter) | Starter architecture for integrating managed model capabilities into a cloud application. | Amazon API Gateway (HTTP API), AWS Lambda, Amazon Bedrock, Amazon DynamoDB, IAM, Amazon CloudWatch. | Shows how model-assisted workflows still depend on backend fundamentals, permissions, operational visibility, and cost awareness. | Basic. Focused managed-model reference. |

---

## Status Notes

- **Basic** = initial implementation or architecture baseline exists in the linked repository.
- **Improving** = actively being enhanced with better documentation, security, observability, cost notes, and trade-offs.
- **Reference-ready** = target state, not currently claimed.

---

## Reference Focus

- AWS architecture patterns for backend and cloud engineering systems
- Serverless backend design
- Containerized application deployment
- Managed model application integration
- Security, observability, scalability, and cost trade-offs

---

## Roadmap

| Phase | Focus |
|---|---|
| Phase 1 | Improve the reference hub |
| Phase 2 | Standardize sub-repository documentation |
| Phase 3 | Deepen Serverless API Backend |
| Phase 4 | Deepen Containerized Web App and GenAI Starter |
| Phase 5 | Add cross-project notes on CI/CD, security, observability, and cost drivers |

---

## Connect

[LinkedIn - Zhou Hong](https://www.linkedin.com/in/hongzz/)
