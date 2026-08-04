# ClassLink (classlink)

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

ClassLink is an EdTech identity and access management platform purpose-built for K-12 school districts, providing single sign-on (SSO) to over 6,000 digital learning resources through its LaunchPad portal. The platform offers a OneRoster-compliant REST API for secure rostering and student data exchange, enabling automated provisioning and synchronization between student information systems and educational applications. ClassLink OneSync handles identity management and account provisioning integrations with any SIS, while Roster Server facilitates standards-based data sharing using OAuth 1.0 and OAuth 2.0. The Analytics and Analytics+ products expose usage telemetry APIs that help district administrators track edtech engagement and license utilization across all devices. ClassLink maintains open developer resources including multi-language request libraries (C#, Java, JavaScript, PHP, Ruby, Python, Go) on GitHub and a partner developer portal.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/classlink/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=classlink-api-evangelist&utm_content=repo

## Tags

EdTech, Education, Identity, Single Sign-On, SSO, OneRoster, Rostering, Provisioning, Analytics, K-12, LTI, OAuth, Student Data

## APIs

| Name | Description |
|---|---|
| ClassLink OneRoster API | OneRoster v1.1-compliant REST API for exchanging K-12 roster data—users, orgs, courses, classes, enrollments, academicSessions, demographics, and resources—between ClassLink Roster Server and third-party educational applications. |
| ClassLink OAuth2 / SSO API | OAuth 2.0 authorization code flow enabling third-party applications to authenticate users via ClassLink LaunchPad and retrieve identity profile data. |
| ClassLink Analytics API | API providing district-level edtech usage analytics, application engagement metrics, and license utilization data. |
| ClassLink Application Provisioning API | REST API for provisioning and managing application accounts within ClassLink, automating creation, update, and deprovisioning of user accounts. |

## Plans / Rate Limits / FinOps

| Resource | Path |
|---|---|
| Plans & Pricing | [plans/classlink-plans-pricing.yml](plans/classlink-plans-pricing.yml) |
| Rate Limits | [rate-limits/classlink-rate-limits.yml](rate-limits/classlink-rate-limits.yml) |
| FinOps Framework | [finops/classlink-finops.yml](finops/classlink-finops.yml) |

## Timestamps

| Field | Value |
|---|---|
| Created | 2026-06-13 |
| Modified | 2026-06-13 |

## Common

| Type | URL |
|---|---|
| Website | https://www.classlink.com/ |
| Documentation | https://help.classlink.com/s/classlink-partners-home |
| GitHub Org | https://github.com/classlinkinc |
| GitHub Repository | https://github.com/classlinkinc/request-libraries |
| LinkedIn | https://www.linkedin.com/company/classlink |
| X | https://twitter.com/classlink |
| Blog | https://www.classlink.com/resources/blog |
| Pricing | https://www.classlink.com/contact |
| Status Page | https://status.classlink.com/ |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
