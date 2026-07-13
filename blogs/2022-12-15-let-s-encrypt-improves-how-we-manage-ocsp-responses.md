---
title: "Let’s Encrypt improves how we manage OCSP responses"
url: "https://letsencrypt.org/2022/12/15/ocspcaching.html"
date: "2022-12-15"
feed_url: "https://letsencrypt.org/feed.xml"
---
Let’s Encrypt has improved how we manage Online Certificate Status Protocol (OCSP) responses by deploying Redis and generating responses on-demand rather than pre-generating them, making us more reliable than ever. About OCSP Responses OCSP is used to communicate the revocation status of TLS certificates. When an ACME agent signs a request to revoke a certificate, our Let’s Encrypt Certificate Authority (CA) verifies whether or not the request is authorized and if it is, we begin publishing a ‘revoked’ OCSP response for that certificate.
