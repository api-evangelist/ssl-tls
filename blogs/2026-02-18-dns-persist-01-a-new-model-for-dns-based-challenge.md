---
title: "DNS-PERSIST-01: A New Model for DNS-based Challenge Validation"
url: "https://letsencrypt.org/2026/02/18/dns-persist-01.html"
date: "2026-02-18"
feed_url: "https://letsencrypt.org/feed.xml"
---
When you request a certificate from Let’s Encrypt, our servers validate that you control the hostnames in that certificate using ACME challenges . For subscribers who need wildcard certificates or who prefer not to expose infrastructure to the public Internet, the DNS-01 challenge type has long been the only choice. DNS-01 works well.
