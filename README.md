# SendBridge

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SendBridge provides an email verification service that helps businesses ensure high deliverability by validating email addresses in real time. Their API offers a simple GET endpoint that returns JSON indicating whether an address is valid, disposable, or risky, enabling marketers and developers to clean mailing lists, reduce bounce rates, and improve inbox placement. The platform emphasizes fast responses, easy integration, and detailed validation results, supporting use cases such as sign‑up forms, CRM data hygiene, and campaign targeting.

**Areas:** email · verification · api · deliverability · validation · marketing · service

## SendBridge on APIs.io

Everything profiled for SendBridge is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sendbridge-com/](https://apis.io/providers/sendbridge-com/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [SendBridge Account API](https://apis.io/apis/sendbridge-com/sendbridge-com-account-api/) — Inspect the current API key. Free — does not charge credits.
- [SendBridge DMARC API](https://apis.io/apis/sendbridge-com/sendbridge-com-dmarc-api/) — Read monitored domains, 7-day DMARC stats, and recent aggregate reports. Live calls are free. Test keys return fixtures.
- [SendBridge Mail Tester API](https://apis.io/apis/sendbridge-com/sendbridge-com-mail-tester-api/) — Generate a unique inbox, send a message to it, then poll the deliverability report. Live calls charge 200 credits. Test keys return a completed demo report…
- [SendBridge Validation API](https://apis.io/apis/sendbridge-com/sendbridge-com-validation-api/) — Verify a single email address. Charges 1 credit on live keys. Test keys return fixtures and are free.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sendbridge Com Agentic Access](https://apis.io/agentic-access/sendbridge-com/sendbridge-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CreateMailTestRequest](https://apis.io/schemas/sendbridge-com/sendbridge-com-create-mail-test-request/)
- [MailTestAddress](https://apis.io/schemas/sendbridge-com/sendbridge-com-mail-test-address/)
- [MailTestResult](https://apis.io/schemas/sendbridge-com/sendbridge-com-mail-test-result/)
- [Me](https://apis.io/schemas/sendbridge-com/sendbridge-com-me/)
- [Meta](https://apis.io/schemas/sendbridge-com/sendbridge-com-meta/)
- [VerificationResult](https://apis.io/schemas/sendbridge-com/sendbridge-com-verification-result/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Sendbridge Com Context](https://apis.io/jsonld/sendbridge-com/sendbridge-com-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Sendbridge Com Openapi Overlay](https://apis.io/overlays/sendbridge-com/sendbridge-com-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [SendBridge API Rules](https://apis.io/rules/sendbridge-com/sendbridge-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Sendbridge Com Authentication](https://apis.io/security/sendbridge-com/sendbridge-com-authentication/)
- [Sendbridge Com Domain Security](https://apis.io/security/sendbridge-com/sendbridge-com-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sendbridge Com Plans Pricing](https://apis.io/plans/sendbridge-com/sendbridge-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sendbridge Com Rate Limits](https://apis.io/rate-limits/sendbridge-com/sendbridge-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sendbridge.com)
- [Documentation](https://sendbridge.com/email-verification-api)
- [API reference](https://api.sendbridge.com/#tag/validation)
- [Pricing](https://sendbridge.com/pricing)
- [Sign up](https://app.sendbridge.com/signup)
- [Support](https://sendbridge.com/support)
- [Blog](https://sendbridge.com/blog)
- [Terms of service](https://sendbridge.com/tos)
- [Privacy policy](https://sendbridge.com/privacy-policy)
- [GitHub](https://github.com/sendbridge)

## API Evangelist rating

**Kin Score 58.7** — strong · rubric 0.25.0 · scored 2026-10-29

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 60.1 |
| Contract governance | 79.1 |
| Operational transparency | 24.2 |
| Developer ergonomics | 42.1 |
| Access clarity | 73.2 |

**Agent readiness 44.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sendbridge-com/](https://apis.io/providers/sendbridge-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SendBridge: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sendbridge-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
