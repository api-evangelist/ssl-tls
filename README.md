# SSL/TLS

SSL/TLS (Secure Sockets Layer / Transport Layer Security) is the cryptographic protocol that secures communications over the internet. TLS 1.3 is the current standard, providing authentication, confidentiality, and integrity for HTTPS, email, VoIP, and other protocols. This covers certificate management, public key infrastructure (PKI), certificate authorities, and TLS configuration APIs from major vendors and open source projects.

- **Website:** https://letsencrypt.org/
- **Documentation:** https://letsencrypt.org/docs/
- **GitHub:** https://github.com/letsencrypt

## APIs

### Let's Encrypt ACME API

Let's Encrypt provides free, automated SSL/TLS certificates via the ACME (Automatic Certificate Management Environment) protocol. The ACME API enables automated certificate issuance, renewal, and revocation using HTTP-01, DNS-01, and TLS-ALPN-01 challenges to verify domain ownership.

- **Base URL:** https://acme-v02.api.letsencrypt.org/directory
- **Documentation:** https://letsencrypt.org/docs/
- **OpenAPI:** [ssl-tls-certificate-management-openapi.yml](openapi/ssl-tls-certificate-management-openapi.yml)

### DigiCert Certificate Management API

DigiCert provides enterprise certificate management through a REST API supporting issuance, renewal, revocation, and lifecycle management for OV, EV, DV, and private certificates.

- **Documentation:** https://dev.digicert.com/

### Sectigo Certificate Manager API

Sectigo provides certificate lifecycle management APIs for enterprise PKI, including S/MIME, code signing, and TLS certificates.

- **Documentation:** https://sectigo.com/knowledge-base

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [ssl-tls-certificate-management-openapi.yml](openapi/ssl-tls-certificate-management-openapi.yml) | SSL/TLS certificate lifecycle management API |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [ssl-tls-rules.yml](rules/ssl-tls-rules.yml) | Spectral rules for SSL/TLS certificate management API conventions |

### Capabilities

#### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [certificate-lifecycle.yaml](capabilities/certificate-lifecycle.yaml) | Unified certificate lifecycle management workflow |

#### Shared Definitions

| Shared | Description |
|--------|-------------|
| [certificate-management.yaml](capabilities/shared/certificate-management.yaml) | SSL/TLS Certificate Management API consumer definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [ssl-tls-certificate-schema.json](json-schema/ssl-tls-certificate-schema.json) | SSL/TLS certificate entity schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [ssl-tls-certificate-structure.json](json-structure/ssl-tls-certificate-structure.json) | Certificate management structure documentation |

### JSON-LD

| Context | Description |
|---------|-------------|
| [ssl-tls-context.jsonld](json-ld/ssl-tls-context.jsonld) | JSON-LD context for SSL/TLS certificate vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [ssl-tls-list-certificates-example.json](examples/ssl-tls-list-certificates-example.json) | List certificates expiring soon example |
| [ssl-tls-request-certificate-example.json](examples/ssl-tls-request-certificate-example.json) | Request DV certificate with ACME HTTP-01 challenge example |

### Vocabulary

| Vocabulary | Description |
|-----------|-------------|
| [ssl-tls-vocabulary.yml](vocabulary/ssl-tls-vocabulary.yml) | SSL/TLS protocol vocabulary and terminology |
