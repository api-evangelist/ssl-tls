---
title: Shorter Certificate Lifetimes and Rate Limits
url: https://letsencrypt.org/2026/02/24/rate-limits-45-day-certs.html
date: '2026-02-24'
author: ''
feed_url: https://letsencrypt.org/feed.xml
---
As previously announced , over the next two years we will be switching the default certificate lifetime from 90 days to 64 days, and then 45 days. This will ultimately double the number of certificate renewal requests each day: today we expect renewal around day 60 (of a 90-day certificate), while in the future we expect renewal around day 30 (of a 45-day certificate). If you use an ACME client that supports ARI , this will happen automatically. The good news for subscribers is that you don’t need any changes to your rate limits, whether you are using our default limits or have requested an override. Our rate limits affect issuance for new domain names (or groups of domain names), but renewals are exempt . So, for instance, if you are managing a set of 15,000 certificates that you continually renew, and create 250 new certificates (with new domain names) each day, you will be well within our limits both before and after the transition. The 250 new certificates daily will still be well under our New Orders per Account limit of 300 per day. And the 15,000 existing certificates will continue to be unaffected by rate limits, whether your ACME client is renewing them every sixty days or every thirty.
