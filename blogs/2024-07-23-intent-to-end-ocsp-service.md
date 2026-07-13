---
title: "Intent to End OCSP Service"
url: "https://letsencrypt.org/2024/07/23/replacing-ocsp-with-crls.html"
date: "2024-07-23"
feed_url: "https://letsencrypt.org/feed.xml"
---
Today we are announcing our intent to end Online Certificate Status Protocol (OCSP) support in favor of Certificate Revocation Lists (CRLs) as soon as possible. OCSP and CRLs are both mechanisms by which CAs can communicate certificate revocation information, but CRLs have significant advantages over OCSP. Let’s Encrypt has been providing an OCSP responder since our launch nearly ten years ago.
