# Honey Insurance

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

Honey Insurance is an Australian direct-to-consumer insurtech selling smart home, contents, renters and landlord insurance, founded by Richard Joffe and headquartered in Sydney. Honey Insurance Pty Ltd (ABN 52 643 672 628, AFSL 528244) distributes and administers the policies, which are underwritten by RACQ Insurance Limited (ABN 50 009 704 152, AFSL 233082), an APRA-authorised general insurer. Its differentiator is a bundle of free smart-home sensors supplied at policy inception in exchange for a recurring premium discount, a three-minute online quote-and-bind funnel, and a heavy prevention rather than indemnity pitch. It sells personal lines only and distributes through its own website plus embedded partnerships with mortgage aggregators, home builders and real-estate groups (Finsure, Metricon, McGrath, BGC, Specialist Finance Group, Bank of Queensland, AGL, RACQ). Its API posture is closed: Honey publishes no public developer portal, no API reference, no OpenAPI or Swagger definition, no Postman collection, no GraphQL surface and no webhook or event catalogue. Probes of developer, developers, docs, /developers, /api, /developer, /partners and /integrations all return NXDOMAIN or HTTP 404, and the sitemap contains no developer, API or partner-portal page at all. A real backend host exists at api.honeyinsurance.com, but it is a private AWS API Gateway that answers every path with HTTP 403 {"message":"Forbidden"}; it serves Honey's own quote funnel and account app and is not documented for third parties. The only publicly reachable standards-based surface is an Auth0 custom-domain tenant at auth.honeyinsurance.com serving anonymous OpenID Connect discovery for consumer account sign-in — not developer API credentials. Quote, bind, issue and FNOL all exist only as consumer web and telephone journeys. No ACORD, AL3, ACORD XML or NGDS reference appears anywhere on the site, which is consistent with an Australian personal-lines carrier operating outside the ACORD agency-download world and with a home market where the Consumer Data Right was designated for general insurance and then deferred, leaving no forcing function for open insurance APIs.

**Areas:** Insurance · Australia · Insurtech · Home Insurance · Property and Casualty · Personal Lines · Direct to Consumer · Embedded Insurance · Smart Home · Claims · Underwriting

## Honey Insurance on APIs.io

Everything profiled for Honey Insurance is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/honey-insurance/](https://apis.io/providers/honey-insurance/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Honey Insurance Authentication](https://apis.io/security/honey-insurance/honey-insurance-authentication/)
- [Honey Insurance Domain Security](https://apis.io/security/honey-insurance/honey-insurance-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Honey Insurance Scopes](https://apis.io/scopes/honey-insurance/honey-insurance-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.honeyinsurance.com/)
- [Sign up](https://www.honeyinsurance.com/get-a-quote/start)
- [Support](https://www.honeyinsurance.com/honey-help/)
- [Blog](https://www.honeyinsurance.com/blog/)
- [Terms of service](https://www.honeyinsurance.com/terms/)
- [Privacy policy](https://www.honeyinsurance.com/privacy/)

## API Evangelist rating

**Kin Score 20.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 49.1 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 0.0 |
| Developer ergonomics | 19.0 |
| Access clarity | 34.2 |

**Agent readiness 15.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |

**Regulatory alignment 36.8** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/honey-insurance/](https://apis.io/providers/honey-insurance/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Honey Insurance: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/honey-insurance/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
