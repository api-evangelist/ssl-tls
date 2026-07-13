---
title: "More Memory Safety for Let’s Encrypt: Deploying ntpd-rs"
url: "https://letsencrypt.org/2024/06/24/ntpd-rs-deployment.html"
date: "2024-06-24"
feed_url: "https://letsencrypt.org/feed.xml"
---
When we look at the general security posture of Let’s Encrypt, one of the things that worries us most is how much of the operating system and network infrastructure is written in unsafe languages like C and C++. The CA software itself is written in memory safe Golang, but from our server operating systems to our network equipment, lack of memory safety routinely leads to vulnerabilities that need patching. Partially for the sake of Let’s Encrypt, and partially for the sake of the wider Internet, we started a new project called Prossimo in 2020.
