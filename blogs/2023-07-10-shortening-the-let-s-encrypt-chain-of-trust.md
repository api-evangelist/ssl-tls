---
title: "Shortening the Let's Encrypt Chain of Trust"
url: "https://letsencrypt.org/2023/07/10/cross-sign-expiration.html"
date: "2023-07-10"
feed_url: "https://letsencrypt.org/feed.xml"
---
When Let’s Encrypt first launched, we needed to ensure that our certificates were widely trusted. To that end, we arranged to have our intermediate certificates cross-signed by IdenTrust’s DST Root CA X3 . This meant that all certificates issued by those intermediates would be trusted, even while our own ISRG Root X1 wasn’t yet.
