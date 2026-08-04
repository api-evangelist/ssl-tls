# SSL/TLS (ssl-tls)

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

SSL/TLS (Secure Sockets Layer / Transport Layer Security) is the cryptographic protocol that secures communications over the internet. TLS 1.3 is the current standard, providing authentication, confidentiality, and integrity for HTTPS, email, VoIP, and other protocols. This covers certificate management, public key infrastructure (PKI), certificate authorities, and TLS configuration APIs from major vendors and open source projects.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- SSL/TLS
- TLS
- Certificates
- PKI
- Cryptography
- Certificate Authority
- HTTPS

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Let's Encrypt ACME API

Let's Encrypt provides free, automated SSL/TLS certificates via the ACME (Automatic Certificate Management Environment) protocol (RFC 8555). The ACME API enables automated certificate issuance, renewal, and revocation using HTTP-01, DNS-01, and TLS-ALPN-01 challenges to verify domain ownership.

- **Human URL:** [https://letsencrypt.org/](https://letsencrypt.org/)
- **Base URL:** `https://acme-v02.api.letsencrypt.org/directory`

#### Tags

- SSL/TLS
- Certificate Authority
- ACME
- Let's Encrypt
- HTTPS

#### Properties

- [Documentation](https://letsencrypt.org/docs/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ssl-tls-certificate-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssl-tls-certificate-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DigiCert Certificate Management API

DigiCert provides enterprise certificate management through a REST API supporting issuance, renewal, revocation, and lifecycle management for OV, EV, DV, and private certificates. Supports CT log integration and ACME protocol.

- **Human URL:** [https://www.digicert.com/](https://www.digicert.com/)
- **Base URL:** `https://www.digicert.com/services/v2`

#### Tags

- SSL/TLS
- Certificate Authority
- Enterprise PKI
- DigiCert

#### Properties

- [Documentation](https://dev.digicert.com/)
- [Postman Collection](collections/ssl-tls-certificate-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssl-tls-certificate-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sectigo Certificate Manager API

Sectigo (formerly Comodo CA) provides certificate lifecycle management APIs for enterprise PKI, including S/MIME, code signing, and TLS certificates.

- **Human URL:** [https://sectigo.com/](https://sectigo.com/)
- **Base URL:** `https://cert-manager.com/api`

#### Tags

- SSL/TLS
- Certificate Authority
- Enterprise PKI

#### Properties

- [Documentation](https://sectigo.com/knowledge-base)
- [Postman Collection](collections/ssl-tls-certificate-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssl-tls-certificate-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://letsencrypt.org/)
- [Documentation](https://letsencrypt.org/docs/)
- [GitHub Organization](https://github.com/letsencrypt)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/openapi/ssl-tls-certificate-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-schema/ssl-tls-certificate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-structure/ssl-tls-certificate-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/json-ld/ssl-tls-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/rules/ssl-tls-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ssl-tls/refs/heads/main/vocabulary/ssl-tls-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
