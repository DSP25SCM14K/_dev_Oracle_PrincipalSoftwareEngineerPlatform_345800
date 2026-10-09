# Oracle Principal Platform Software Engineer — role research

## Scope and source note

The supplied document is a resume for **Principal, Backend Platform & APIs** at Sprouts AI. It does not include a separate Oracle job-description URL. Oracle's posting for req. **345800** was not indexed in the searches available for this task. For an evidence-based view of the target role, this research uses Oracle Careers' closely matching **Principal Software Engineer, Platform** req. **345414**, and Oracle's own platform/API materials. Confirm the exact req. 345800 posting if its requirements differ.

## What the role is about

Oracle describes OCI as serving mission-critical enterprise workloads across more than 50 regions. The Principal Platform Software Engineer role is a cross-team individual-contributor position: build and evolve backend platform services, APIs, middleware, runtimes, integration frameworks, and developer tools. Its output is the shared foundation that lets many service teams interoperate consistently and safely.

The technical center of gravity is lifecycle engineering as much as feature delivery:

- Establish API versioning, deprecation, and rollout practices that protect downstream users.
- Make reusable contracts, middleware, and runtimes work across services and tenants.
- Improve availability with observability baselines, SLOs, error budgets, resilience patterns, and capacity planning.
- Diagnose multi-service failures, make durable remediations, and guide compatibility-safe migrations.
- Influence architecture through reviews and hands-on implementation, then improve adoption through SDKs, docs, examples, and playbooks.

Oracle's API Platform documentation reinforces the ecosystem model: gateway runtimes apply API policies; management interfaces govern and publish APIs; developer portals help application developers discover and consume them. Oracle's architecture guidance also calls out API versioning, backward compatibility, documentation, authentication, and error handling as core design concerns.

## Resume evidence relevant to the work

- **Platform scope:** a multi-tenant API gateway, shared runtime, middleware, and integration framework in Java and Go supporting 40+ internal services.
- **API safety:** 30+ releases with zero breaking changes; semantic versioning, OpenAPI contract tests, compatibility checks, and deprecation headers.
- **Adoption:** 20+ services onboarded in two quarters using SDKs, CLI scaffolding, migration guides, playbooks, docs, and examples.
- **Service health:** 99.99%+ availability; shared SLO/error-budget and OpenTelemetry standards across 12 teams; MTTR down 40%, alert noise down 35%.
- **Performance and operations:** p99 improvements at Sprouts AI and Resilience Inc; safe canary rollouts and rollback; migration of 15+ services with zero downtime; capacity planning and incident response.
- **Technical leadership:** architecture and code reviews, mentoring six engineers, and leading a cross-functional Agile team of eight.

## Strongest portfolio narrative

The clearest story is **platform engineering as a force multiplier**: make service integration predictable, make API evolution safe for consumers, and pair shared infrastructure with approachable tooling so adoption grows. Quantified examples carry the narrative better than generic claims about passion or scale. The visual language in the site uses API contracts, service teams, integration paths, and developer tooling to tell that story.

## Likely interview areas to prepare

1. Trade-offs in API versioning and deprecation when consumers migrate at different speeds.
2. How OpenAPI and contract tests are enforced, and how false positives or intentional changes are handled.
3. Design of a multi-tenant gateway/runtime: isolation, fairness, auth, backpressure, failure handling, and observability.
4. A concrete migration story: shadow traffic, phased cutover, rollback criteria, and proving no downtime.
5. How shared standards were introduced across 12 teams without slowing local delivery.
6. Capacity, tail latency, and service-to-service consistency diagnosis; explain measurements and attribution.
7. Security controls around OAuth2/JWT, mTLS, secrets, dependency scans, and OWASP hardening.
8. Adoption outcomes for SDK/CLI/docs: onboarding friction before and after, feedback, and maintenance model.

## Primary sources

- [Oracle Careers — Principal Software Engineer, Platform (req. 345414)](https://careers.oracle.com/en/sites/jobsearch/job/345414/?s=35)
- [Oracle OCI platform services overview](https://docs.oracle.com/en-us/iaas/Content/General/Reference/gettingstartedwithPaaS.htm)
- [Oracle API Platform components: gateway, management portal, developer portal](https://docs.oracle.com/en/cloud/paas/api-platform-cloud/apfad/components-oracle-api-platform-cloud-service.html)
- [Oracle API lifecycle and management](https://docs.oracle.com/en/cloud/paas/api-platform-cloud/apfad/manage-apis.html)
- [Oracle application architecture guidance, including API design and versioning](https://docs.oracle.com/en-us/iaas/Content/cloud-adoption-framework/ea-application-architecture.htm)
