---
title: "Monitoring Vector's per-component memory usage"
url: "https://vector.dev/blog/tracking-allocations/"
date: "Wed, 14 Dec 2022 00:00:00 +0000"
author: ""
feed_url: "https://vector.dev/blog/index.xml"
---
<p>We are excited to announce that Vector now has support for exposing per-component memory usage metrics. This work addresses an often-requested feature from users who want to understand how Vector uses memory, and what parts of their configurations are responsible for high memory usage.</p>


<h2 id="trying-it-out">
 Trying it out
 <a class="ml-2 relative" href="#trying-it-out">
 <svg class="absolute inset-0 h-full h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
 <path d="M7 20l4-16m2 16l4-16M6 9h14M4 15h14" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
 </svg>
 </a>
</h2><p><img alt="vector top with allocation tracing" src="https://vector.dev/img/blog/vector-top-allocation-tracking.png" /></p>
