# Georgia Institute of Technology (georgia-institute-of-technology)

Georgia Institute of Technology (Georgia Tech) is a public research university in Atlanta, Georgia, United States, ranked #114 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint in the APIs.json format. The footprint is modest and partly gated: the Georgia Tech Library Digital Repository exposes public OAI-PMH and DSpace REST interfaces, RNOC documents a public GT Places API, and the Office of Information Technology runs the credentialed BuzzAPI plus CAS single sign-on.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/georgia-institute-of-technology/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=georgia-institute-of-technology-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, United States

## APIs

- **GT Digital Repository OAI-PMH** — Public OAI-PMH 2.0 metadata harvesting for the DSpace 7 institutional repository. Docs: https://repository.gatech.edu/ (base: https://repository.gatech.edu/server/oai/request)
- **GT Digital Repository REST API** — DSpace 7 REST API for communities, collections, items, and bitstreams. Docs: https://repository.gatech.edu/ (base: https://repository.gatech.edu/server/api)
- **GT Places API** — Campus building and office data (names, addresses, phone, images, GPS) documented by RNOC as openly accessible. Docs: https://rnoc.gatech.edu/gt-places-api
- **BuzzAPI** — Enterprise integration API at api.gatech.edu; credentialed access, docs gated behind CAS SSO. Docs: https://webmasters.gatech.edu/handbook/buzzapi-v3-example
- **SUMS REST API** — REST API on the OutSystems platform; help page loads but no public operation docs. Docs: https://sums.gatech.edu/SUMSAPI/rest/API/

## Plans / Rate Limits / FinOps

- Plans: [plans/georgia-institute-of-technology-plans-pricing.yml](plans/georgia-institute-of-technology-plans-pricing.yml)
- Rate Limits: [rate-limits/georgia-institute-of-technology-rate-limits.yml](rate-limits/georgia-institute-of-technology-rate-limits.yml)
- FinOps: [finops/georgia-institute-of-technology-finops.yml](finops/georgia-institute-of-technology-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.gatech.edu/
- GitHub: https://github.com/gatech
- LinkedIn: https://www.linkedin.com/school/georgia-institute-of-technology/
- Developer Portal: https://rnoc.gatech.edu/api
- Source Code (OSPO): https://ospo.cc.gatech.edu/github-resources/
- Authentication (CAS SSO): https://sso.gatech.edu/

## Notes

All endpoints were probed on 2026-06-03. The OAI-PMH Identify response and DSpace REST root were confirmed live (HTTP 200). The GT Places API is documented as openly accessible but publishes no base URL or endpoint specs. BuzzAPI is credentialed — its apiv3 root returns 404 unauthenticated and the developers handbook redirects to CAS SSO. The SUMS REST help page loads but exposes no public operation documentation. The legacy SMARTech OAI endpoint is dead and superseded by repository.gatech.edu. No endpoints were fabricated; gated and undocumented surfaces are flagged honestly.

## Maintainers

- Kin Lane — kin@apievangelist.com
