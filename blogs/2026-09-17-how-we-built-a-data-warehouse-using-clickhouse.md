---
title: "How We Built a Data Warehouse Using ClickHouse"
url: "https://letsencrypt.org/2026/09/17/clickhouse.html"
date: "2026-09-17"
feed_url: "https://letsencrypt.org/feed.xml"
---
When the scripts that generate the data for letsencrypt.org/stats broke yet again, we decided to retire it rather than repair it. Let’s Encrypt issues six to ten million certificates each day , producing a large volume of logs that keeps growing. It became increasingly time-consuming and difficult to answer questions about our own issuance like “how many certificates use the ‘shortlived’ profile.” Using raw logs, this requires finding, parsing and extracting relevant portions of loglines.
