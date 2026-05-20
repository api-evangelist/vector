---
title: "Adaptive request concurrency. Resilient observability at scale."
url: "https://vector.dev/blog/adaptive-request-concurrency/"
date: "Tue, 24 Nov 2020 00:00:00 +0000"
author: ""
feed_url: "https://vector.dev/blog/index.xml"
---
Observability pipelines have become critical infrastructure in the current technological landscape, which is why we’ve built Vector to provide extremely high throughput with the tiniest resource footprint we can manage ( Rust is a huge help here). But this is not enough in the real world: your observability pipeline needs to provide optimal performance and efficiency while also being a good infrastructure citizen and playing nicely with services like Elasticsearch and Clickhouse . And so we’re excited to announce that Vector version 0.11 includes support for Adaptive Request Concurrency…
