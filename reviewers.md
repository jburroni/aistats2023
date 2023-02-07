---
title: Reviewers and Meta-Reviewers
layout: default
weight: 5
---

<h1>{{ site.data.conference.short_name }} {{ site.data.conference.year }} Reviewers and Meta-Reviewers </h1>

AISTATS is possible thanks to the tireless work of the whole community, including a large team of reviewers and area chairs. They are essential to selecting a good program, and to providing constructive feedback to authors. The program chairs wish to give a special thank you to all our reviewers and area chairs for their hard work.

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