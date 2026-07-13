---
title: "Ending OCSP Support in 2025"
url: "https://letsencrypt.org/2024/12/05/ending-ocsp.html"
date: "2024-12-05"
feed_url: "https://letsencrypt.org/feed.xml"
---
Earlier this year we announced our intent to provide certificate revocation information exclusively via Certificate Revocation Lists (CRLs) , ending support for providing certificate revocation information via the Online Certificate Status Protocol (OCSP) . Today we are providing a timeline for ending OCSP services: January 30, 2025 OCSP Must-Staple requests will fail, unless the requesting account has previously issued a certificate containing the OCSP Must Staple extension May 7, 2025 Prior to this date we will have added CRL URLs to certificates On this date we will drop OCSP URLs from cert
