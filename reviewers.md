---
title: Reviewers and Meta-Reviewers
layout: default
weight: 5
---

<h1>{{ site.data.conference.short_name }} {{ site.data.conference.year }} Reviewers and Meta-Reviewers </h1>

<h2>Top Reviewers</h2>

{%- if site.data.top_reviewers -%}
<ul>
	{%- for reviewer in site.data.top_reviewers -%}
	<li> {{reviewer.FirstName}} {{reviewer.MiddleInitial}} {{reviewer.LastName}}</li>
	{%- endfor -%}
</ul>
{%- endif -%}

<h2>Senior Meta-Reviewers</h2>

{%- if site.data.senior -%}
<ul>
	{%- for reviewer in site.data.senior -%}
	<li> {{reviewer.FirstName}} {{reviewer.MiddleInitial}} {{reviewer.LastName}}</li>
	{%- endfor -%}
</ul>
{%- endif -%}

<h2>Meta-Reviewers</h2>

{%- if site.data.meta_reviewers -%}
<ul>
	{%- for reviewer in site.data.meta_reviewers -%}
	<li> {{reviewer.FirstName}} {{reviewer.MiddleInitial}} {{reviewer.LastName}}</li>
	{%- endfor -%}
</ul>
{%- endif -%}

<h2>Reviewers</h2>

{%- if site.data.reviewers -%}
<ul>
	{%- for reviewer in site.data.reviewers -%}
	<li> {{reviewer.FirstName}} {{reviewer.MiddleInitial}} {{reviewer.LastName}}</li>
	{%- endfor -%}
</ul>
{%- endif -%}