# Zenduty (zenduty)

Zenduty is an incident management and on-call platform that orchestrates alert routing, escalation policies, on-call schedules, and incident response workflows for SRE and DevOps teams. The platform integrates with observability tools, ticketing systems, and chat platforms to centralize incident triage. Zenduty exposes a REST API for managing incidents, services, teams, schedules, and escalation policies, plus an Events API for ingesting alerts, all secured with Token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zenduty/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zenduty/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Incident Management
- On-Call
- Alerting
- SRE
- DevOps
- Observability

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Zenduty REST API

Management REST API for incidents, services, teams, users, schedules, escalation policies, and integrations. Authenticated via "Authorization: Token <token>" header.

- **Human URL:** [https://apidocs.zenduty.com](https://apidocs.zenduty.com)
- **Base URL:** `https://www.zenduty.com/api`

#### Tags

- Incident Management
- On-Call
- Alerting

#### Properties

- [Documentation](https://apidocs.zenduty.com)
- [A P I  Keys  Guide](https://zenduty.com/docs/api-keys)
- [Postman Collection](collections/zenduty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenduty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zenduty Events API

Alert ingestion API for sending incident events from monitoring, observability, and custom systems into Zenduty.

- **Human URL:** [https://zenduty.com/docs/api-integration](https://zenduty.com/docs/api-integration)
- **Base URL:** `https://events.zenduty.com/api/events`

#### Tags

- Alerting
- Events

#### Properties

- [Documentation](https://zenduty.com/docs/api-integration)
- [Postman Collection](collections/zenduty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zenduty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zenduty)
- [Website](https://www.zenduty.com)
- [Documentation](https://zenduty.com/docs)
- [Pricing](https://www.zenduty.com/pricing)
- [Sign Up](https://www.zenduty.com/signup)
- [Git Hub  S D K](https://github.com/Zenduty/zenduty-python-sdk)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
