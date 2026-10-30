# Georgia Institute of Technology

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

Georgia Institute of Technology (Georgia Tech) is a public technological research university in Atlanta, Georgia, United States. Its programmable footprint is real but small, decentralized, and operated by individual units rather than by any central API program: there is no developer portal, no self-service key issuance, and no published OpenAPI anywhere on a gatech.edu host that Georgia Tech itself indexes. What does exist, and what was verified live on 2026-09-01, is four institution-operated machine surfaces — an OAI-PMH 2.0 provider and a DSpace 7.6 REST API on repository.gatech.edu (the Georgia Tech Digital Repository), a Shibboleth SAML 2.0 identity provider registered in InCommon and scoped gatech.edu, and a CourseLeaf course-data endpoint on catalog.gatech.edu — plus two contracts Georgia Tech units publish as documents: the SUMS (Shared User Management System) Swagger on sums.gatech.edu and the RNOC GT Places API Swagger on rnoc.gatech.edu. Georgia Tech is a DataCite direct member (symbol GT, prefix 10.35090) and is registered in ROR as 01zkghx44. Two things the profile has to say plainly: GT Places is documented as "open to all" but its declared host now answers with a Microsoft Entra ID sign-in redirect, and the enterprise integration API BuzzAPI (api.gatech.edu) lost its public documentation when webmasters.gatech.edu was rebuilt in 2026, so it is a credentialed surface with nothing public left to read.

**Areas:** University · Higher Education · Education · United States · Institute of Technology · Public Research University · Research Repository · Identity Federation · Course Catalog · Library · Open Data · Research

## Georgia Institute of Technology on APIs.io

Everything profiled for Georgia Institute of Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/georgia-institute-of-technology/](https://apis.io/providers/georgia-institute-of-technology/)** — or go straight to one of the APIs or properties below.

### APIs (26)

- [GT Digital Repository OAI-PMH](https://apis.io/apis/georgia-institute-of-technology/repository-oai/) — Public OAI-PMH 2.0 metadata harvesting interface for the Georgia Tech Digital Repository, the institutional repository for theses, dissertations,…
- [GT Digital Repository REST API](https://apis.io/apis/georgia-institute-of-technology/repository-rest/) — DSpace 7.6 REST API for the Georgia Tech Digital Repository, providing programmatic read access to communities, collections, items and bitstreams.…
- [BuzzAPI](https://apis.io/apis/georgia-institute-of-technology/buzzapi/) — Georgia Tech's enterprise integration API (BuzzAPI v3), operated by the Office of Information Technology at api.gatech.edu with a test environment at…
- [Georgia Tech Shibboleth Identity Provider (InCommon)](https://apis.io/apis/georgia-institute-of-technology/shibboleth-idp/) — Georgia Tech's own SAML 2.0 / Shibboleth identity provider, entityID https://idp.gatech.edu/idp/shibboleth, registered in the InCommon federation and…
- [Georgia Tech Course Catalog Data (CourseLeaf)](https://apis.io/apis/georgia-institute-of-technology/course-catalog/) — Course and curriculum data for the Georgia Tech catalog, served as XML from the institution's own host through the CourseLeaf "ribbit" data endpoint.…
- [DataCite membership (provider GT, prefix 10.35090)](https://apis.io/apis/georgia-institute-of-technology/datacite/) — Georgia Tech is a DataCite direct member. Verified 2026-09-01: https://api.datacite.org/providers/gt returns symbol GT, name "Georgia Institute of…
- [ROR registration (01zkghx44)](https://apis.io/apis/georgia-institute-of-technology/ror/) — Georgia Institute of Technology is registered in the Research Organization Registry as https://ror.org/01zkghx44, with declared domain gatech.edu,…
- [Canvas LMS (Instructure tenant)](https://apis.io/apis/georgia-institute-of-technology/canvas/) — Georgia Tech's learning management system is Canvas, running as an Instructure-hosted tenant at gatech.instructure.com (200 on 2026-09-01, titled "GT | GT…
- [Georgia Institute of Technology Buildings API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-buildings-api/) — The buildings API from Georgia Institute of Technology — 1 operation(s) for buildings.
- [Georgia Institute of Technology Buildings ID API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-buildings-id-api/) — The buildings_id API from Georgia Institute of Technology — 1 operation(s) for buildings_id.
- [Georgia Institute of Technology Categories API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-categories-api/) — The categories API from Georgia Institute of Technology — 1 operation(s) for categories.
- [Georgia Institute of Technology Tags API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-tags-api/) — The tags API from Georgia Institute of Technology — 2 operation(s) for tags.
- [Georgia Institute of Technology Add User By Username API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-add-user-by-username-api/) — The Add User By Username API from Georgia Institute of Technology — 1 operation(s) for add user by username.
- [Georgia Institute of Technology Contact Forms API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-contactforms-api/) — The ContactForms API from Georgia Institute of Technology — 1 operation(s) for contactforms.
- [Georgia Institute of Technology EquipmentGroup Info API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-equipmentgroup-info-api/) — The EquipmentGroup Info API from Georgia Institute of Technology — 1 operation(s) for equipmentgroup info.
- [Georgia Institute of Technology EquipmentGroup QueueGroups API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-equipmentgroup-queuegroups-api/) — The EquipmentGroup QueueGroups API from Georgia Institute of Technology — 1 operation(s) for equipmentgroup queuegroups.
- [Georgia Institute of Technology EquipmentGroup QueueUsers API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-equipmentgroup-queueusers-api/) — The EquipmentGroup QueueUsers API from Georgia Institute of Technology — 1 operation(s) for equipmentgroup queueusers.
- [Georgia Institute of Technology EquipmentGroup Tools API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-equipmentgroup-tools-api/) — The EquipmentGroup Tools API from Georgia Institute of Technology — 1 operation(s) for equipmentgroup tools.
- [Georgia Institute of Technology Get Tool Status API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-gettoolstatus-api/) — The GetToolStatus API from Georgia Institute of Technology — 1 operation(s) for gettoolstatus.
- [Georgia Institute of Technology Get Training Report API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-gettrainingreport-api/) — The GetTrainingReport API from Georgia Institute of Technology — 1 operation(s) for gettrainingreport.
- [Georgia Institute of Technology Get User Name And Email By Buzz Card Number API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-getusernameandemailbybuzzcardnumber-api/) — The GetUserNameAndEmailByBuzzCardNumber API from Georgia Institute of Technology — 1 operation(s) for getusernameandemailbybuzzcardnumber.
- [Georgia Institute of Technology Tool Check Logged In API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-toolcheckloggedin-api/) — The ToolCheckLoggedIn API from Georgia Institute of Technology — 1 operation(s) for toolcheckloggedin.
- [Georgia Institute of Technology Training Info API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-traininginfo-api/) — The TrainingInfo API from Georgia Institute of Technology — 1 operation(s) for traininginfo.
- [Georgia Institute of Technology Update User Template API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-updateusertemplate-api/) — The UpdateUserTemplate API from Georgia Institute of Technology — 1 operation(s) for updateusertemplate.
- [Georgia Institute of Technology User Info API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-user-info-api/) — The User Info API from Georgia Institute of Technology — 1 operation(s) for user info.
- [Georgia Institute of Technology Who Logged In API](https://apis.io/apis/georgia-institute-of-technology/georgia-institute-of-technology-whologgedin-api/) — The WhoLoggedIn API from Georgia Institute of Technology — 1 operation(s) for whologgedin.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Georgia Institute Of Technology Agentic Access](https://apis.io/agentic-access/georgia-institute-of-technology/georgia-institute-of-technology-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [SUMS Tool Record](https://apis.io/schemas/georgia-institute-of-technology/georgia-institute-of-technology-tool/)
- [SUMS TrainingInfo Record](https://apis.io/schemas/georgia-institute-of-technology/georgia-institute-of-technology-traininginfo/)
- [SUMS WhoLoggedIn Record](https://apis.io/schemas/georgia-institute-of-technology/georgia-institute-of-technology-whologgedin/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Georgia Institute Of Technology Tool Structure](https://apis.io/json-structure/georgia-institute-of-technology/georgia-institute-of-technology-tool-structure/)
- [Georgia Institute Of Technology Whologgedin Structure](https://apis.io/json-structure/georgia-institute-of-technology/georgia-institute-of-technology-whologgedin-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Georgia Institute Of Technology Context](https://apis.io/jsonld/georgia-institute-of-technology/georgia-institute-of-technology-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Georgia Tech SUMS API Vocabulary](https://apis.io/vocabularies/georgia-institute-of-technology/georgia-institute-of-technology-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Georgia Institute Of Technology Getusernameandemailbybuzzcardnumber Example](https://apis.io/examples/georgia-institute-of-technology/georgia-institute-of-technology-GetUserNameAndEmailByBuzzCardNumber-example/)
- [Georgia Institute Of Technology Whologgedin Example](https://apis.io/examples/georgia-institute-of-technology/georgia-institute-of-technology-WhoLoggedIn-example/)

#### Collections (1)

Postman and Open Collection request collections.

- [Georgia Tech SUMS REST API API](https://apis.io/collections/georgia-institute-of-technology/open-georgia-institute-of-technology-api-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Georgia Institute of Technology — jsonschema rules](https://apis.io/rules/georgia-institute-of-technology/georgia-institute-of-technology-jsonschema-spectral-rules/)
- [Georgia Institute of Technology API Rules](https://apis.io/rules/georgia-institute-of-technology/georgia-institute-of-technology-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Georgia Institute Of Technology Authentication](https://apis.io/security/georgia-institute-of-technology/georgia-institute-of-technology-authentication/)
- [Georgia Institute Of Technology Domain Security](https://apis.io/security/georgia-institute-of-technology/georgia-institute-of-technology-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Georgia Institute Of Technology Plans Pricing](https://apis.io/plans/georgia-institute-of-technology/georgia-institute-of-technology-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Georgia Institute Of Technology Rate Limits](https://apis.io/rate-limits/georgia-institute-of-technology/georgia-institute-of-technology-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Georgia Institute Of Technology Finops](https://apis.io/finops/georgia-institute-of-technology/georgia-institute-of-technology-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.gatech.edu/)
- [Support](https://gatech.service-now.com/technology)
- [Blog](https://news.gatech.edu/)
- [Terms of service](https://www.gatech.edu/legal)
- [Privacy policy](https://www.gatech.edu/privacy)
- [GitHub](https://github.com/gt-ospo)

## API Evangelist rating

**Kin Score 36.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 47.3 |
| Contract governance | 28.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 38.1 |
| Access clarity | 26.3 |

**Agent readiness 20.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 32.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/georgia-institute-of-technology/](https://apis.io/providers/georgia-institute-of-technology/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Georgia Institute of Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/georgia-institute-of-technology/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
