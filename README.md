# Honey Insurance (honey-insurance)

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

Honey Insurance is an Australian direct-to-consumer insurtech selling smart home, contents, renters and landlord insurance, founded by Richard Joffe and headquartered in Sydney. Honey Insurance Pty Ltd (ABN 52 643 672 628, AFSL 528244) distributes and administers the policies, which are underwritten by RACQ Insurance Limited (ABN 50 009 704 152, AFSL 233082), an APRA-authorised general insurer. Its differentiator is a bundle of free smart-home sensors supplied at policy inception in exchange for a recurring premium discount, a three-minute online quote-and-bind funnel, and a prevention-over-indemnity pitch. It sells personal lines only, and distributes through its own website plus embedded partnerships with mortgage aggregators, home builders and real-estate groups.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/honey-insurance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/honey-insurance/refs/heads/main/apis.yml)

## Tags

- Insurance
- Australia
- Insurtech
- Home Insurance
- Property and Casualty
- Personal Lines
- Direct to Consumer
- Embedded Insurance
- Smart Home
- Claims
- Underwriting

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

None. Honey Insurance publishes no public API.

This is the honest finding, not a gap in the research. As of 2026-07-25:

- **No developer portal.** `developer.`, `developers.` and `docs.honeyinsurance.com` do not resolve. `/developers`, `/developer`, `/api`, `/partners` and `/integrations` all return HTTP 404. The published sitemap lists 80 URLs and not one of them is a developer, API, broker or partner-portal page.
- **No downloadable specification.** No OpenAPI, Swagger, AsyncAPI, GraphQL SDL, `.proto` or Postman collection is published anywhere. Zero specs were harvested, and none were inferred.
- **A private backend, not a public API.** `api.honeyinsurance.com` resolves and returns JSON, but every probed path answers HTTP 403 `{"message":"Forbidden"}` — the AWS API Gateway default deny. It serves Honey's own quote funnel and account app.
- **Auth is for customers, not developers.** `auth.honeyinsurance.com` is an Auth0 custom-domain tenant serving anonymous OpenID Connect discovery and JWKS (HTTP 200), advertising only stock OIDC profile scopes. There is no developer credential path and no published API audience.
- **Quote, bind, issue and FNOL all exist — as consumer journeys.** Quote and bind run at `/get-a-quote/start`; issue and documents sit behind `/my-account`; claims are lodged at `/my-account/claims`, by phone on 137 138, or by email. None of the four verbs is exposed as an API, to consumers, agents or partners.
- **No ACORD footprint.** No reference to ACORD, AL3, ACORD XML, ACORD certified or NGDS appears anywhere on the property. Consistent with an Australian personal-lines direct writer operating outside the ACORD agency-download world.
- **No webhooks or event catalogue.**

Australia has the legal machinery for open insurance and no live obligation. The Consumer Data Right that opened banking and energy was designated to extend to general insurance, then deferred and de-prioritised — so there is no forcing function reaching a company like this one, and its posture reflects that exactly.

See [review.yml](review.yml) for the full probe log, HTTP statuses, auth metadata and provenance.

## Common Properties

- [Website](https://www.honeyinsurance.com/)
- [About](https://www.honeyinsurance.com/about-us/)
- [Blog](https://www.honeyinsurance.com/blog/)
- [Newsroom](https://www.honeyinsurance.com/media-centre/newsroom/)
- [Support](https://www.honeyinsurance.com/honey-help/)
- [FAQ](https://www.honeyinsurance.com/faq/)
- [Vocabulary](https://www.honeyinsurance.com/glossary/)
- [Login](https://www.honeyinsurance.com/my-account)
- [Terms of Service](https://www.honeyinsurance.com/terms/)
- [Privacy Policy](https://www.honeyinsurance.com/privacy/)
- [Well-Known (OIDC)](https://auth.honeyinsurance.com/.well-known/openid-configuration)

## Maintainers

- Kin Lane — kin@apievangelist.com
