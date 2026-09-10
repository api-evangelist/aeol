# Aeol

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

AEOL (AEOL KOREA Co., Ltd. / 주식회사 에이올코리아) is a South Korean advanced-materials and
climate-technology manufacturer founded in February 2018 out of the Korea University Campus Town
programme and headquartered in Seongnam, Gyeonggi Province. It holds a twenty-year exclusive licence
from the Korea Research Institute of Chemical Technology to manufacture and sell Metal-Organic
Framework (MOF) materials and was the first Korean company to commercialise MOF production at scale,
which it turns into physical equipment: MOF desiccant rotors and hybrid dehumidifiers that
regenerate at low temperature instead of using refrigerant compression, all-in-one heat-recovery
ventilation units with UV-LED and HEPA air purification, the Red Dot-awarded Mofresh Mini gas and
odour adsorber, and the CarbonSorV rotary CO2-capture wheel shown at CES 2025. It won a CES 2024
Innovation Award and the FIX 2024 Grand Innovation Award.

## No API surface

AEOL sells hardware and materials, not software. It publishes no developer portal, no API
documentation, no SDK, no webhook surface and no machine-readable API contract of any kind.

`aeolkorea.co.kr` is a Cafe24-hosted Korean-language brochure site sitting behind a "CUPID" AES
JavaScript cookie interstitial that answers HTTP 200 with an identical ~780-byte challenge shell for
**every** path — including a negative-control path that cannot exist. A 200 from that host is not
evidence a document exists, and the shell echoes the requested URL back into its own body, so
keyword matches against it are matches against the request. Every well-known, OpenAPI, GraphQL,
agent-card and apis.json probe on that origin is recorded as a miss for exactly that reason.

`aeolkorea.com` is a **different company** — AEOL Electronics Korea, a heatpipe, vapor-chamber and
thermal-module supplier — and nothing on that domain belongs to this profile. `aeol.kr` does not
resolve.

## What is in this repository

- `apis.yml` — company identity, links, and the `x-coverage` record of why this profile is thin
- `well-known/aeol-well-known.yml` — the `/.well-known/` probe: zero hits, catch-all origin, negative control failed
- `security/aeol-domain-security.yml` — TLS/DNS posture (TLS 1.2, no HSTS, no DNSSEC, no CAA, no DMARC)
- `packages/aeol-packages.yml` — registry sweep: no first-party package on npm, PyPI, RubyGems, crates.io, Packagist or NuGet, and no GitHub organization
- `conformance/aeol-conformance.yml` — API standards recorded as not-applicable; the CES/Red Dot awards and the KRICT MOF licence recorded as the real third-party assessments
- `llms/aeol-llms.txt` — an agent-facing summary of the above

## Links

- Website: https://www.aeolkorea.co.kr/
- Crunchbase: https://www.crunchbase.com/organization/aeol
- Secondary market: https://equityzen.com/company/aeol/
