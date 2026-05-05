---
title: "The new GraphQL API for Vector"
url: "https://vector.dev/blog/graphql-api/"
date: "Tue, 08 Dec 2020 00:00:00 +0000"
author: ""
feed_url: "https://vector.dev/blog/index.xml"
---
<div class="admonition no-prose rounded-xl border-3 px-3 py-3.5 lg:px-5 lg:py-4 border-yellow-400">
 <div class="flex items-center">
 <div class="flex-shrink-0">
 <svg class="h-6 w-6 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
 

 

 

 
 
 <path d="M8.257 3.099c.765-1.36 2.722-1.36 3.486 0l5.58 9.92c.75 1.334-.213 2.98-1.742 2.98H4.42c-1.53 0-2.493-1.646-1.743-2.98l5.58-9.92zM11 13a1 1 0 11-2 0 1 1 0 012 0zm-1-8a1 1 0 00-1 1v3a1 1 0 002 0V6a1 1 0 00-1-1z" fill-rule="evenodd">
 

 

 
 </svg>
 </div>
 <div class="ml-6 flex flex-col m-0 space-y-1.5">
 

 <div class="tracking-tight leading-snug dark:prose-dark prose max-w-none">
 The Vector observability API migrated from GraphQL to gRPC in version 0.55.0.
 </div>
 </div>
 </div>
</div>


<p>Although Vector is an observability tool, it&rsquo;s nonetheless important to be able
to observe Vector itself, especially in production environments where it serves
as critical infrastructure. That&rsquo;s why we&rsquo;re excited to announce the new <a class="inline-block" href="https://vector.dev/docs/reference/api/" rel="noopener" target="_blank">Vector
GraphQL API</a>, available in
<a class="inline-block" href="https://vector.dev/releases/0.11.0/" rel="noopener" target="_blank">v0.11.0</a>.</p>
