---
title: "Deploying Let's Encrypt's New Issuance Chains"
url: "https://letsencrypt.org/2024/04/12/changes-to-issuance-chains.html"
date: "2024-04-12"
feed_url: "https://letsencrypt.org/feed.xml"
---
On Thursday, June 6th, 2024 , we will be switching issuance to use our new intermediate certificates . Simultaneously, we are removing the DST Root CA X3 cross-sign from our API, aligning with our strategy to shorten the Let’s Encrypt chain of trust. We will begin issuing ECDSA end-entity certificates from a default chain that just contains a single ECDSA intermediate, removing a second intermediate and the option to issue an ECDSA end-entity certificate from an RSA intermediate.
