# Kestrel (kestrel)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kestrel AI is a YC-backed company building an AI-native cloud incident response platform. Their platform uses autonomous AI agents to detect, investigate, and remediate Kubernetes and cloud infrastructure incidents, delivering production-ready fixes through GitOps workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Incident Response, Kubernetes, AI Agents, Cloud Security, Observability

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Kestrel Platform
Kestrel AI provides an AI-native cloud incident response platform that uses autonomous agents to detect, investigate, and remediate Kubernetes and cloud infrastructure incidents. The platform monitors clusters continuously, identifies root causes, and generates production-ready fixes delivered as pull requests via GitOps workflows. It integrates with major cloud providers, observability tools, and CI/CD platforms to provide end-to-end incident management.

**Human URL:** [https://docs.usekestrel.ai/](https://docs.usekestrel.ai/)


#### Tags:

 - Incident Response, Kubernetes, AI Agents, Cloud Security

#### Properties

- [Documentation](https://docs.usekestrel.ai/)
- [GettingStarted](https://docs.usekestrel.ai/quickstart)
- [SignUp](https://platform.usekestrel.ai/register)

### Kestrel Kubernetes Operator
The Kestrel Kubernetes Operator is an open-source Go-based operator that connects Kubernetes clusters to the Kestrel AI platform. It communicates via bidirectional gRPC streaming over mTLS with OAuth2 authentication, streaming resource metadata, logs, events, and network telemetry. The operator supports OpenTelemetry OTLP ingestion and Istio Access Log Service integration for comprehensive observability. It is deployed via Helm chart from the GitHub Container Registry.

**Human URL:** [https://docs.usekestrel.ai/kubernetes/configuration](https://docs.usekestrel.ai/kubernetes/configuration)


#### Tags:

 - Kubernetes, Operators, gRPC, Helm

#### Properties

- [Documentation](https://docs.usekestrel.ai/kubernetes/configuration)
- [GitHubOrganization](https://github.com/KestrelAI/Kestrel-Operator)

## Common Properties

- [Website](https://usekestrel.ai/)
- [Documentation](https://docs.usekestrel.ai/)
- [SignUp](https://platform.usekestrel.ai/register)
- [GitHubOrganization](https://github.com/kestrelai)
- [Integration](https://docs.usekestrel.ai/integrations/slack)
- [Integration](https://docs.usekestrel.ai/integrations/pagerduty)
- [Integration](https://docs.usekestrel.ai/integrations/cicd)
- [Integration](https://docs.usekestrel.ai/cloud/aws)
- [SelfHosted](https://docs.usekestrel.ai/on-premise/setup)
- [Status](https://status.usekestrel.ai/)
- [Changelog](https://usekestrel.ai/changelog)
- [Security](https://trust.delve.co/kestrel-ai)
- [JSON-LD](json-ld/kestrel-context.jsonld)
- [JSONSchema](json-schema/kestrel-incident-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
