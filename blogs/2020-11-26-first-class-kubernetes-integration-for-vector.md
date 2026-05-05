---
title: "First-class Kubernetes integration for Vector"
url: "https://vector.dev/blog/kubernetes-integration/"
date: "Thu, 26 Nov 2020 00:00:00 +0000"
author: ""
feed_url: "https://vector.dev/blog/index.xml"
---
<p>After months of development, <a class="inline-block" href="https://github.com/vectordotdev/vector/pulls?q=is%3Apr&#43;sort%3Aupdated-desc&#43;kubernetes&#43;is%3Aclosed" rel="noopener" target="_blank">over 100 pull requests</a>, and intensive QA in clusters producing over 20 terabytes of event data a day, we&rsquo;re pleased to announce our first-class <a class="inline-block" href="https://kubernetes.io" rel="noopener" target="_blank">Kubernetes</a> integration for Vector in <a href="https://vector.dev/releases/0.11.0/">version 0.11</a>. We strove to make even this initial integration rock solid and production ready because we aim to make Vector the default pipeline for all Kubernetes observability data.</p>
<p>To cut straight to the chase, checkout the <a href="https://vector.dev/docs/setup/installation/platforms/kubernetes/#install">installation instructions</a>, otherwise read on for the details.</p>
