---
title: "Announcing Certificate Profile Selection"
url: "https://letsencrypt.org/2025/01/09/acme-profiles.html"
date: "2025-01-09"
feed_url: "https://letsencrypt.org/feed.xml"
---
We are excited to announce a new extension to Let’s Encrypt’s implementation of the ACME protocol that we are calling “profile selection.” This new feature will allow site operators and ACME clients to opt in to the next evolution of Let’s Encrypt. As of today, the staging environment is advertising a new field in its directory resource: GET /directory HTTP/1.1 HTTP/1.1 200 OK Content-Type: application/json { ... "meta" : { "profiles" : { "classic" : "The same profile you're accustomed to" , "tlsserver" : "https://letsencrypt.org/2025/01/09/acme-profiles/" } } } Here, the keys are the names of
