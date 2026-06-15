# SSL/TLS (ssl-tls)

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
