---
title: "Adaptive request concurrency. Resilient observability at scale."
url: "https://vector.dev/blog/adaptive-request-concurrency/"
date: "Tue, 24 Nov 2020 00:00:00 +0000"
author: ""
feed_url: "https://vector.dev/blog/index.xml"
---
<p>Observability pipelines have become critical infrastructure in the current technological landscape, which is why we&rsquo;ve built <a href="https://vector.dev/">Vector</a> to provide extremely high throughput with the tiniest resource footprint we can manage (<a class="inline-block" href="https://rust-lang.org" rel="noopener" target="_blank">Rust</a> is a huge help here). But this is not enough in the real world: your observability pipeline needs to provide optimal performance and efficiency while <em>also</em> being a good infrastructure citizen and playing nicely with services like <a href="https://vector.dev/docs/reference/configuration/sinks/elasticsearch/">Elasticsearch</a> and <a href="https://vector.dev/docs/reference/configuration/sinks/clickhouse/">Clickhouse</a>.</p>
<p>And so we&rsquo;re excited to announce that Vector version 0.11 includes support for <strong>Adaptive Request Concurrency</strong> (ARC) in all of its HTTP-based <a href="https://vector.dev/docs/reference/configuration/sinks/">sinks</a>. This feature does away with static rate limits and automatically optimizes HTTP concurrency limits based on downstream service responses. The underlying <a href="#how-it-works">mechanism</a> is a feedback loop inspired by TCP congestion control algorithms.</p>
