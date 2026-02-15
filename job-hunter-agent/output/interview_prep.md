```markdown
# Interview Prep: Exactpi – Senior GoLang Developer

---

## Job Overview  
Exactpi is building a scalable Life Cycle Assessment (LCA) platform that helps manufacturers measure, improve, and share their environmental footprint. As a Senior GoLang Developer based in Amsterdam (hybrid/remote-friendly), you will:

- Design and implement high-throughput microservices in Go  
- Build GraphQL and gRPC APIs, CQRS command and query handlers  
- Model complex data in PostgreSQL, optimize queries and indexing  
- Collaborate with DevOps on AWS / Kubernetes / ECS / CI-CD pipelines  
- Integrate AI-driven tooling for codegen and workflow automation  
- Contribute end-to-end in a Scrum environment, using Jira, Notion, Sentry, Prometheus, Grafana  

Key technologies: Go, Microservices, GraphQL, gRPC, CQRS, PostgreSQL, AWS, Docker, Kubernetes, CI/CD.

---

## Why This Job Is a Fit  
1. **Backend & API Expertise**  
   – You’ve built and maintained GraphQL APIs and REST services at scale, and you’re comfortable designing service boundaries and data models.  
2. **Cloud & DevOps Savvy**  
   – Your AWS experience (EC2, ECS, Lambda), Docker containers, CI/CD pipelines and GitFlow culture align perfectly with Exactpi’s stack.  
3. **Rapid GoLang Adoption**  
   – Although your background is in Node.js/TypeScript, you’ve already launched personal Go projects, mastered goroutines and channels, and are eager to own production Go services.  
4. **Passion for Sustainability**  
   – You’re motivated by green tech, have read up on LCA methodologies, and want to contribute to reducing real-world carbon footprints.  
5. **Proactive & Collaborative**  
   – You thrive in Scrum teams, lead code reviews, mentor peers, and take initiative—qualities Exactpi values for driving product excellence.

---

## Resume Highlights for This Role  
**Juan Srisaiwong – Senior Backend Developer**  
• 3 years of commercial experience building scalable microservices & APIs  
• GoLang (in progress): implemented personal CLI tool for log processing, explored memory profiling, unit testing with Go’s standard library  
• GraphQL: designed schemas and resolvers for high-traffic dashboards serving 10k+ users  
• gRPC: prototyped streaming services for real-time notifications  
• CQRS/Event-Driven Patterns: split write/read models in Node.js services, prepared migration to event sourcing  
• PostgreSQL: optimized schemas, composite indexes, partitioning—cut query latencies by 30%  
• AWS & Kubernetes: containerized services on ECS/EKS, automated deployments via GitHub Actions  
• Monitoring & Observability: set up Sentry for error tracking, Prometheus metrics with Grafana dashboards  
• AI-Tooling: experimented with GitHub Copilot for codegen, automated test skeletons  
• Collaboration: GitFlow workflows, Jira/Scrum rituals, cross-functional teamwork  

---

## Company Summary  
**Exactpi** (Amsterdam) is a ClimateTech/SaaS provider specializing in Life Cycle Assessment software. They empower manufacturers to quantify and reduce environmental impact through:

- A modular LCA platform: microservices for data ingestion, analytics, reporting  
- AI-driven features: automated data validation, predictive insights  
- Sustainable culture: 50% emissions cut by 2024, net-zero by 2025  
- Values:  
  • Sustainability First  
  • Partnership & Transparency  
  • Technical Excellence  
  • Continuous Learning  

**Perks & Benefits**: private medical care, multisport, training budget (€900/yr), hybrid work, pizza Thursdays, physiotherapist, Amsterdam apartment for workations.

---

## Predicted Interview Questions  
1. Describe your experience writing production services in Go. What challenges did you face with concurrency and memory management?  
2. How would you structure a microservice that ingests environmental data, processes it, and exposes both GraphQL and gRPC endpoints?  
3. Explain your approach to CQRS in a distributed system. When is it beneficial and what trade-offs exist?  
4. Walk us through your PostgreSQL schema design for a time-series dataset with millions of records. How do you optimize queries?  
5. How have you integrated CI/CD in your past projects? Which tools did you use and what gating mechanisms (tests, linters) did you enforce?  
6. Discuss an incident you troubleshooted in production using Sentry, Prometheus or Grafana. What was your resolution process?  
7. How do you ensure API versioning and backward compatibility in GraphQL or gRPC services?  
8. Tell us about a time you used AI-based tooling in your workflow. What worked, what didn’t, and how did you measure ROI?  
9. How do you prioritize technical debt versus feature delivery in an Agile/Scrum environment?  
10. What appeals to you about working on a sustainable-development LCA product?  

---

## Questions to Ask Them  
1. What are the top priorities for the LCA platform in the next 6–12 months?  
2. How is the Go team organized—who will I pair with, code-review, and mentor?  
3. Can you share examples of AI-driven workflows already in production?  
4. How do you balance performance, scalability, and accuracy in environmental computations?  
5. What does success look like for this role at 3, 6, and 12 months?  
6. How do you handle cross-office collaboration (Amsterdam ↔ Poland)? Which tools/processes keep everyone aligned?  
7. What professional development and career-growth paths exist for senior engineers here?  
8. What are the biggest technical or cultural challenges on your team today?  
9. How flexible is the hybrid model—are there core in-office days or team gatherings?  
10. How does Exactpi measure engineer contributions toward sustainability goals?  

---

## Concepts To Know/Review  
- Go fundamentals: goroutines, channels, `sync` primitives, error handling patterns  
- Profiling & benchmarking: `pprof`, `go test -bench`, memory and CPU tuning  
- Microservices design: service boundaries, idempotency, retries, circuit breakers  
- GraphQL schema design & performance (batching, DataLoader)  
- gRPC streaming vs unary calls, proto definitions, error models  
- CQRS / Event-Driven Architecture: command/query handlers, event sourcing basics  
- PostgreSQL: indexing strategies, partitioning, multi-tenant schemas, EXPLAIN ANALYZE  
- AWS & Kubernetes: ECS/EKS, Helm charts, infra-as-code (Terraform/CloudFormation)  
- CI/CD best practices: GitFlow, automated tests (unit, integration), policy as code  
- Monitoring & observability: Sentry, Prometheus metrics, Grafana dashboards, Datadog  
- LCA fundamentals: GHG Protocol scopes, cradle-to-gate vs cradle-to-grave, ISO 14040/44  

---

## Strategic Advice  
Tone & Focus  
- Be **confident** about your backend mastery; humbly own gaps in Go but emphasize rapid up-skilling.  
- Show **passion** for sustainability—link past projects or personal initiatives to green tech.  
- Demonstrate **proactivity**: ask about technical roadmaps, suggest improvements, share mini “spike” ideas.  

Red Flags to Avoid  
- Over-emphasizing Node.js without concrete Go experience; pivot to how you quickly learned new languages.  
- Lack of questions about team dynamics, career growth or sustainability KPIs—signals low engagement.  
- Vague answers on observability or production incidents—be specific, quantify impact.  

Preparation Tips  
- Prepare one or two short “Go code” examples to explain concurrency patterns or API handlers.  
- Sketch a high-level architecture diagram on a whiteboard for a sample LCA microservice.  
- Review the LCA domain briefly—understand key environmental metrics and reporting needs.  
- Practice STAR stories around system design, performance tuning, and cross-functional collaboration.  

With this prep, you’ll demonstrate both the technical chops and the sustainability mindset Exactpi is looking for. Good luck!